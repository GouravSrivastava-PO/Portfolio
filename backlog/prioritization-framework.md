# Backlog Prioritization

How I decide what goes first, shown on a real backlog: the AI Resume Parser.

## The lenses

Each candidate item is judged on four questions before it gets a MoSCoW label:

| Lens | Question I ask |
|---|---|
| **Business value** | Does it move the success metric we committed to (screening time ↓ 50%)? |
| **Customer impact** | How many recruiters feel it, and how often? |
| **Effort** | How big is it relative to everything else, and does it need new integrations? |
| **Risk reduction** | Does it remove a risk that would block later work (data quality, adoption)? |

## Applied example: AI Resume Parser MVP

| Backlog item | Value | Impact | Effort | Risk reduction | Decision | Reasoning |
|---|---|---|---|---|---|---|
| PDF/DOCX upload + file validation | High | Every recruiter, every resume | Low | High | **Must** | Nothing works without it |
| Structured data extraction | High | Every resume | Medium | High | **Must** | Removes the biggest manual task; all scoring depends on clean data |
| Job-to-candidate match score | High | Shortlisting | Medium | Medium | **Must** | Directly cuts screening time |
| AI-generated candidate summary | Medium | Shortlisting | Medium | Low | **Should** | Speeds up review, but extraction alone already saves time |
| ERP & communication integrations | High | Adoption | High | High | **Should** (phase 4) | Critical for adoption, but only worth building once parsing is accurate |
| Recruiter dashboard: search & filters | Medium | Daily use | Medium | Low | **Could** | Useful; recruiters can work from the ranked list first |
| Interview scheduling | Low for this metric | Different workflow | High | None | **Won't** | Out of scope: doesn't reduce screening time |
| Offer management / payroll | None for this metric | Different users | High | None | **Won't** | Out of scope |

*The High/Medium/Low ratings are illustrative, reconstructed for this portfolio from the PRD scope and phasing. They are relative judgements, not computed scores.*

## Rules I hold to

* **The metric decides ties.** If two items are close, the one that moves the committed metric goes first.
* **Foundations before features.** Data quality (extraction) comes before what's built on it (scoring, dashboards). I made the same call on the Basware consolidation platform.
* **"Won't" is written down.** Out-of-scope items are documented so they don't creep back in mid-sprint.
* **Re-prioritise on evidence.** Feedback from weekly user conversations can move items between Should and Could.
