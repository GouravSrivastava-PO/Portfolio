# Gourav Srivastava
### Product Manager · Data-Driven Products · ML, Mobile & Gaming · B2B SaaS & Fintech

---

> I build products where business complexity meets engineering precision —  
> turning ambiguous enterprise problems into structured, measurable, and shipped solutions.

3.5 years in product management and 8+ years of total experience, across B2B SaaS, AI-powered automation, fintech platforms with customers in 100+ countries, and now B2C iGaming. CSPO certified · B.Tech, MBA.

**Currently:** Technical Project Manager at Techindustan, running the discovery phase of a B2C casino (iGaming) platform for the client Stake, working with the client and engineering on requirements, scope and delivery planning.

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
| **Data & Experimentation** | SQL analysis of large-scale and real-time data to find anomalies, trends and data-quality issues; planning and measuring A/B tests against defined success metrics |
| **AI & ML Products** | ML and prediction-model products, including recommendation and personalisation; designing prompts and AI workflows |
| **Platform Thinking** | Designing for scale — API-first integrations, automation pipelines, configurability over one-off customisation |

---

## Impact at a Glance

| Company | Product | Role | Outcome |
|---|---|---|---|
| **Techindustan** (current) | B2C Casino Platform (iGaming) | Technical Project Manager | Leading discovery: requirements, scope & delivery planning with client and engineering |
| **Basware** | Financial Reporting & Consolidation Platform | Technical Product Owner | Velocity ↑15% · Sprint completion >80% sustained · Data-quality issues found via SQL & fixed · Self-service tooling adopted by 3 teams |
| **Connoisseur Infotech** | AI Resume Parser + ERP Integrations | Product Owner | 5 ERP & communication integrations shipped · Sprint completion 0 → 80%+ · Post-launch defects reduced |
| **Comprinno Technology** | Incident & Project Automation | Associate Project Manager | Client feedback turnaround ↓80% · Manual incident steps eliminated · Exceptional Execution award 2023 |

---

## Case Studies

---

### 01 · Financial Reporting Platform
`Enterprise SaaS` · `Fintech` · `Multi-entity Consolidation` · `SAFe Delivery`

*Basware · Technical Product Owner · Nov 2024 – Jun 2026*

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
- Validated consolidation and dashboard numbers with SQL, found data-quality issues (incorrect numbers, mismatches) and got them fixed

**Outcomes**

- Team velocity improved ~15% through backlog hygiene and upstream clarity on requirements
- Sprint completion rate sustained consistently above 80%
- Reduced manual reporting effort and improved financial data confidence across multi-entity consolidation
- Self-service tooling adopted across 3 teams

📁 [View Case Study →](./case-studies/Financial-Reporting-Platform)

---

### 02 · Incident Management Automation
`Platform Integration` · `Prometheus · PagerDuty · Jira Service Management · Slack` · `MTTA / MTTR`

*Comprinno Technology · Associate Project Manager · Jan 2023 – Jul 2024*

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

- Client feedback turnaround reduced by ~80% through the Jira–Slack integration
- Manual incident creation and stakeholder notification steps fully eliminated
- Established a scalable, auditable pipeline with end-to-end traceability from alert to resolution

📁 [View Case Study →](./case-studies/Jira-Service-Desk-Integration)

---

### 03 · AI Resume Parser
`AI / NLP` · `Recruiting Technology` · `0→1 Product` · `ERP Integration`

*Connoisseur Infotech · Product Owner · Jul 2024 – Nov 2024*

**The Problem**

Recruiters were spending the majority of their screening time on low-signal, high-volume work: manually extracting data from resumes, re-applying evaluation criteria inconsistently, and delaying shortlisting decisions because the pipeline couldn't keep pace with candidate volume.

**The Insight**

The bottleneck was not evaluator judgment — recruiters were good at their job. The problem was the upstream cost of getting candidates *to* the evaluation stage. Automating structured extraction (not scoring, not final decisions) would free recruiter capacity for the work that actually required human judgment, while improving consistency on the work that did not.

**What I Did**

- Ran structured discovery interviews with recruiters and hiring managers to validate the hypothesis: screening time, not evaluation quality, was the primary constraint
- Defined the product scope: resume parsing (PDF and DOCX), structured candidate data extraction, AI-generated candidate summaries, and job-to-candidate scoring — deliberately excluding interview scheduling and offer management to keep focus on the highest-value layer
- Set hard accuracy and performance thresholds in acceptance criteria (parsing accuracy >95%, processing time <10 seconds per resume) rather than leaving quality as a post-launch conversation
- Designed the prompts and AI workflows behind extraction and candidate summaries
- Delivered 5 ERP and communication integrations, including real-time event and notification flows, connecting the parser to downstream recruitment and onboarding workflows
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

- Operational efficiency improved across recruiter workflows
- Post-launch defects reduced by writing negative scenarios and edge cases into acceptance criteria
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

### 05 · Gaming Platform Auth: Delivery Plan Against a Fixed Launch Date
`iGaming` · `Multi-tenant Platform` · `Compliance & KYC` · `Interview Exercise`

**The Problem**

A multi-tenant online gaming platform needed authentication and authorization delivered for a licence-fixed launch in Canada (excluding Ontario), with LATAM to follow. Four engineering teams were involved, the identity vendor was not yet chosen, and compliance and legal had to sign off on KYC, responsible gaming and data residency.

**What I Did**

- Planned a 16-week phased delivery (T-16 → T-0) around an MVP slice: one brand, one market, web, where a real player can log in and place one real-money bet, before expanding to all brands and partners
- Mapped the critical path across four teams, compliance and the vendor, and named the vendor decision as the dependency blocking three teams
- Built a RAID log where every risk has a concrete trigger (e.g. "no signed contract by T-13"), not "monitor closely"
- Wrote a go/no-go checklist with a hard "No" condition per item (e.g. a self-excluded test player can place a bet), plus an amber stakeholder update and calls on six judgement scenarios

📁 [View Exercise →](./Interview-Assignment)

---

## Repository Structure

```
Portfolio/
├── case-studies/             # Full case studies: PRDs, user stories, acceptance criteria, metrics
│   ├── Financial-Reporting-Platform/
│   ├── AI-Resume-Parser/
│   ├── Jira-Service-Desk-Integration/
│   └── Release-Notes/
├── Interview-Assignment/     # Gaming platform auth delivery plan (brief + response)
├── agile-artifacts/          # Roadmap, acceptance criteria, user story examples
├── backlog/                  # Prioritisation framework with an applied example
├── Comprinno/                # Jira Service Desk walkthrough video, execution award
├── resume/                   # Current resume
└── product-metrics.md        # Quantified outcomes by company and role
```

📄 [Download resume](./resume/Gourav_Srivastava_Resume_ProductManager.docx)

---

## Certifications

- **CSPO**: Certified Scrum Product Owner · Scrum Alliance
- **SAFe® 6.0**: Complete Scaled Agile Framework In-Depth
- **AWS Certified Cloud Practitioner**
- **Machine Learning for PMs**: Managing ML Projects · ML Foundations for Product Managers · Human Factors in AI (Duke University)
- **Generative AI for Product Managers**
- **Oracle ERP**: Functional Principles of EBS & SaaS (SCM)

---

## Connect

**LinkedIn:** [linkedin.com/in/gouravs26](https://www.linkedin.com/in/gouravs26)  
**GitHub:** [github.com/GouravSrivastava-PO](https://github.com/GouravSrivastava-PO)

