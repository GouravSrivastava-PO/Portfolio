# Product Roadmap: AI Resume Parser

`Connoisseur Infotech` · Jul 2024 – Nov 2024 · Outcome-based roadmap

The roadmap was sequenced around the one hypothesis discovery confirmed: **screening time, not evaluation quality, is the recruiter's main constraint.** Each phase had to reduce that time or unlock the next phase that would.

| Phase | Theme | What ships | Why now | Exit criteria |
|---|---|---|---|---|
| **1. Discover** | Validate the problem | Recruiter & hiring-manager interviews, scope decision, success metrics | Avoid building scoring or scheduling before knowing where the time goes | Hypothesis confirmed; in/out of scope agreed; metrics & targets set before build |
| **2. MVP: Parse** | Remove manual data entry | PDF/DOCX upload, structured extraction (name, contact, skills, experience, education) | Highest-volume manual task; everything downstream depends on clean data | Parsing accuracy >95%, processing <10 s per resume |
| **3. Assist** | Speed up shortlisting | Job-to-candidate match score, AI-generated candidate summary, ranked list | Only valuable once extraction is reliable | Match accuracy >85%; recruiters use summaries in screening |
| **4. Integrate** | Fit the existing workflow | 5 ERP & communication integrations, real-time event & notification flows | Adoption depends on data flowing into the tools recruiters already use | Each integration passes data-contract & error-handling acceptance criteria |
| **5. Scale** | Reliability & adoption | Error handling, monitoring, adoption tracking | Move from working to dependable | Availability 99.9%, error rate <2%, adoption >70% |

## Deliberately not on the roadmap

* **Interview scheduling** and **offer management:** adjacent problems, but they don't reduce screening time.
* **Automated hiring decisions:** the tool supports recruiter judgment and doesn't replace it.

## How the roadmap was kept honest

* Every phase maps to a metric in [Success Metrics](../case-studies/AI-Resume-Parser/SUCCESS_METRICS.md).
* A phase was not "done" until its exit criteria were met, not when its stories were closed.
