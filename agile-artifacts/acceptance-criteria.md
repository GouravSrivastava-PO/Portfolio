# Acceptance Criteria

How I write acceptance criteria: testable, with numbers wherever quality matters, and with the unhappy paths written down before development starts rather than found in UAT.

The examples below come from products in this portfolio and use the thresholds from those projects. Some unhappy-path scenarios were written for this portfolio to show the approach.

---

## Example 1: Resume upload & parsing (AI Resume Parser)

**Story:** As a recruiter, I want a resume parsed automatically when I upload it, so that I don't have to re-type candidate details.

```gherkin
Scenario: Successful parse
  Given I am a logged-in recruiter
  When I upload a valid PDF or DOCX resume
  Then name, contact information, skills, experience and education are extracted
  And the candidate profile is shown within 10 seconds

Scenario: Unsupported file type
  Given I am a logged-in recruiter
  When I upload a file that is not PDF or DOCX
  Then the upload is rejected
  And I see a message listing the accepted formats

Scenario: Partially unreadable resume
  Given a resume where a field cannot be extracted
  When parsing completes
  Then the missing field is flagged for manual review
  And the rest of the profile is still saved
```

**Quality bar:** parsing accuracy above 95% on the agreed test set.

---

## Example 2: Automatic incident ticket (Jira Service Management integration)

**Story:** As an operations engineer, I want a JSM ticket created automatically when PagerDuty receives a critical alert, so that incident response starts without manual work.

```gherkin
Scenario: Critical alert creates a ticket
  Given PagerDuty receives a critical alert for a mapped service
  When the alert is triggered
  Then a JSM incident ticket is created within 60 seconds
  And its priority is mapped from the PagerDuty severity
  And it is assigned to the owner of that service
  And a Slack notification is posted to the incident channel

Scenario: Alert for an unmapped service
  Given PagerDuty receives an alert for a service with no ownership mapping
  When the ticket is created
  Then it is routed to the default on-call queue
  And it is labelled "unmapped-service" so the mapping can be fixed
```

---

## Example 3: Report generation (Financial Reporting Platform)

```gherkin
Scenario: Report available quickly
  Given a finance user is logged in
  When the user generates a report
  Then the report is available within 5 seconds
```

---

## My checklist before a story is "Ready"

* At least one happy path and one unhappy path
* Any quality expectation has a number (time, accuracy, error rate)
* QA and the developer have read the criteria in refinement, before the sprint starts
* Out-of-scope behaviour is stated where it might be assumed
