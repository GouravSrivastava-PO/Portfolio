# Gourav Srivastava
### Technical Product Owner · B2B SaaS · AI Products · Enterprise Fintech Platforms

---

> I build products where business complexity meets engineering precision —  
> turning ambiguous enterprise problems into structured, measurable, and shipped solutions.

10+ years of experience across enterprise product delivery. 3.5+ years as a dedicated Technical Product Owner across B2B SaaS, AI-powered automation, and fintech platforms serving Fortune 500 clients.

I operate at the layer where product strategy meets execution: defining *what* to build and *why*, aligning engineering and business stakeholders around shared outcomes, and holding the line on measurable impact over output.

---

## What I Bring

| Dimension | In practice |
|---|---|
| **Product Strategy** | Framing the right problem before solutioning; translating ambiguity into a testable hypothesis and a prioritised roadmap |
| **Discovery & Research** | Structuring stakeholder interviews, synthesising user pain into ranked opportunity areas with business context |
| **Execution Rigour** | End-to-end backlog ownership — epics, user stories, acceptance criteria, sprint planning, DoR/DoD, and release governance |
| **Metrics & Outcomes** | Defining success *before* building; separating input metrics from output metrics; designing for measurability from day one |
| **Stakeholder Alignment** | Navigating multi-stakeholder environments across finance, engineering, operations, and C-suite without losing delivery momentum |
| **Platform Thinking** | Designing for scale — API-first integrations, automation pipelines, configurability over one-off customisation |

---

## Impact at a Glance

| Company | Product | Role | Outcome |
|---|---|---|---|
| **Basware** | Financial Reporting & Consolidation Platform | Technical Product Owner | Velocity ↑15% · Sprint completion >80% sustained · Multi-entity consolidation standardised |
| **Connoisseur Infotech** | AI Resume Parser + ERP Integrations | Product Owner | 5 ERP integrations shipped · Operational efficiency ↑20% · Sprint completion 0 → 80%+ |
| **Comprinno Technology** | Incident & Project Automation | Associate PM | Client feedback turnaround ↓80% · SLA adherence improved · Manual incident steps eliminated |

---

## Case Studies

---

### 01 · Financial Reporting Platform
`Enterprise SaaS` · `Fintech` · `Multi-entity Consolidation` · `SAFe Delivery`

**The Problem**

Enterprise finance teams were consolidating data across multiple business units and legal entities through a fragile patchwork of spreadsheets and manual reconciliation. Reporting cycles were slow, error-prone, and invisible to executive stakeholders until deadlines had already slipped.

**The Insight**

The data existed. The problem was the absence of a standardised consolidation structure that could aggregate across entities without custom workarounds for each business unit. Solving for data structure before dashboards was the right delivery sequence — a call that prevented a common trap: building visibility on top of unreliable foundations.

**What I Did**

- Drove product discovery through finance controller and CFO-office interviews to separate the actual bottleneck (consolidation accuracy) from the stated request (better dashboards)
- Prioritised consolidation capabilities in the roadmap before reporting enhancements — a deliberate sequencing decision anchored in reducing data risk upstream
- Introduced SAFe sprint cadence and a Definition of Ready (DoR) gate to eliminate mid-sprint scope ambiguity and unplanned rework
- Aligned engineering, finance, and business unit stakeholders on a phased roadmap with clear entry/exit criteria per phase
- Owned end-to-end backlog: epics, story refinement, acceptance criteria, sprint planning, and release sign-off

**Outcomes**

- Team velocity improved ~15% through backlog hygiene and upstream clarity on requirements
- Sprint completion rate sustained consistently above 80%
- Reduced manual reporting effort and improved financial data confidence across multi-entity consolidation

📁 [View Case Study →](./case-studies/Financial-Reporting-Platform)

---

### 02 · Incident Management Automation
`Platform Integration` · `Prometheus · PagerDuty · Jira Service Management · Slack` · `MTTA / MTTR`

**The Problem**

Production incidents were being handled reactively across four disconnected tools. Engineers manually triaged alerts, hand-typed tickets, and notified stakeholders through separate channels — introducing compounding delays at every handoff. For a platform with enterprise SLA commitments, this was a structural risk, not a process gap.

**The Insight**

Every minute between detection and acknowledgement widens the blast radius. The fix was not better tooling in isolation — it was eliminating the human handoffs *between* tools entirely. The data needed to route and resolve each incident already existed across the stack; the workflow just wasn't connected.

**What I Did**

- Mapped the full incident lifecycle from Prometheus alert trigger to engineer resolution and identified five manual touchpoints that could be fully automated without reducing decision quality
- Defined the target-state workflow: Prometheus → AlertManager → PagerDuty → Jira Service Management → Slack, with zero manual intervention required for ticket creation, routing, or stakeholder notification
- Wrote user stories with hard acceptance criteria: ticket created within 60 seconds of alert, priority mapped from PagerDuty severity, service ownership routing automated, Slack notification triggered in parallel
- Coordinated delivery across engineering, operations, and support stakeholders with clear ownership boundaries at each integration point

**Outcomes**

- Client feedback and incident acknowledgement turnaround reduced by ~80%
- Manual incident creation and stakeholder notification steps fully eliminated
- Established a scalable, auditable pipeline with end-to-end traceability from alert to resolution

📁 [View Case Study →](./case-studies/Jira-Service-Desk-Integration)

---

### 03 · AI Resume Parser
`AI / NLP` · `Recruiting Technology` · `0→1 Product` · `ERP Integration`

**The Problem**

Recruiters were spending the majority of their screening time on low-signal, high-volume work: manually extracting data from resumes, re-applying evaluation criteria inconsistently, and delaying shortlisting decisions because the pipeline couldn't keep pace with candidate volume.

**The Insight**

The bottleneck was not evaluator judgment — recruiters were good at their job. The problem was the upstream cost of getting candidates *to* the evaluation stage. Automating structured extraction (not scoring, not final decisions) would free recruiter capacity for the work that actually required human judgment, while improving consistency on the work that did not.

**What I Did**

- Ran structured discovery interviews with recruiters and hiring managers to validate the hypothesis: screening time, not evaluation quality, was the primary constraint
- Defined the product scope: resume parsing (PDF and DOCX), structured candidate data extraction, AI-generated candidate summaries, and job-to-candidate scoring — deliberately excluding interview scheduling and offer management to keep focus on the highest-value layer
- Set hard accuracy and performance thresholds in acceptance criteria (parsing accuracy >95%, processing time <10 seconds per resume) rather than leaving quality as a post-launch conversation
- Delivered 5 ERP integrations connecting the parser to downstream recruitment and onboarding workflows
- Owned the full backlog across five epics from discovery through launch

**Success Metrics Defined Pre-Build**

| Metric | Target |
|---|---|
| Resume screening time | ↓ 50% |
| Candidate processing speed | ↑ 40% |
| Parsing accuracy | > 95% |
| Candidate match accuracy | > 85% |
| Hiring cycle time | ↓ 20% |

**Outcomes**

- Operational efficiency improved ~20% across recruiter workflows
- Sprint completion scaled from near-zero to 80%+ within one quarter through structured agile delivery

📁 [View Case Study →](./case-studies/AI-Resume-Parser)

---

### 04 · Release Notes Automation
`Internal Tooling` · `Workflow Automation` · `Jira + Confluence + AI`

**The Problem**

Post-sprint release notes were a 2-hour manual process every sprint: reviewing completed Jira stories one by one, writing summaries in inconsistent formats, and notifying stakeholders days after sprint close. A communication artefact that should take minutes was becoming a recurring delivery tax.

**The Insight**

The data needed to generate release notes already existed in Jira at sprint close — completed stories, story types, and feature descriptions. The gap was the translation layer between structured Jira data and readable stakeholder communication. This was an automation problem, not a writing problem.

**What I Did**

- Defined a trigger-based workflow: sprint close in Jira → completed stories extracted automatically → AI-generated summary → Confluence page published → stakeholders notified without manual intervention
- Enforced format standardisation *before* automating — resolving inconsistency at the source rather than embedding it into the pipeline
- Aligned stakeholders on a consistent release note structure so the output was immediately usable, not just fast

**Outcomes**

| Metric | Before | After |
|---|---|---|
| Release notes creation time | ~2 hours | ~10 minutes |
| Format consistency | Variable per sprint | Standardised |
| Stakeholder notification | Manual / delayed | Automatic at sprint close |

📁 [View Case Study →](./case-studies/Release-Notes)

---

## Repository Structure

```
Portfolio/
├── case-studies/             # Full case studies — PRDs, user stories, acceptance criteria, metrics
│   ├── Financial-Reporting-Platform/
│   ├── AI-Resume-Parser/
│   ├── Jira-Service-Desk-Integration/
│   └── Release-Notes/
├── agile-artifacts/          # Roadmaps, sprint planning, user story examples
├── backlog/                  # Prioritisation frameworks with applied examples
├── automations/              # Automation workflow documentation
├── resume/                   # Current CV
└── product-metrics.md        # Quantified outcomes by company and role
```

---

## Certifications

- **CSPO** — Certified Scrum Product Owner · Scrum Alliance
- **SAFe** — Practitioner (applied within Basware's scaled agile delivery model)
- **AWS Cloud Practitioner**
- **Oracle ERP SaaS SCM**
- **Generative AI for Product Management**

---

## Connect

**LinkedIn:** [linkedin.com/in/gouravs26](https://www.linkedin.com/in/gouravs26)  
**GitHub:** [github.com/GouravSrivastava-PO](https://github.com/GouravSrivastava-PO)

