# OctoAcme — Project Roles RACI Matrix

## Purpose
Provide a lightweight, single-page RACI (Responsible / Accountable / Consulted / Informed) reference for key project artifacts and activities. Use this matrix to clarify ownership, avoid duplication of effort, and ensure nothing falls through the cracks.

## RACI Key
| Symbol | Meaning |
|--------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; approves/signs off |
| **C** | **Consulted** — provides input before decisions or work is finalized |
| **I** | **Informed** — kept up-to-date on progress and decisions |

## Role Abbreviations
| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developer |
| QA | QA Engineer |
| UX | UX Designer |
| BA | Business Analyst |
| DevOps | DevOps Engineer |
| Sponsor | Stakeholder / Executive Sponsor |
| Advocate | Community Advocate |

---

## RACI Matrix

| Artifact / Activity | PM | PdM | Dev | QA | UX | BA | DevOps | Sponsor | Advocate |
|---|---|---|---|---|---|---|---|---|---|
| **Project One-pager / Charter** | R | C | I | I | I | C | I | A | I |
| **Stakeholder List & Comms Plan** | A/R | C | I | I | I | C | I | C | C |
| **Product Roadmap** | I | A/R | C | I | C | C | I | C | C |
| **Prioritized Backlog** | C | A/R | C | C | C | R | I | I | C |
| **Requirements / Functional Specs** | C | A | C | C | C | R | I | I | C |
| **UX Designs & Prototypes** | I | C | C | C | A/R | C | I | I | I |
| **Definition of Done (DoD)** | A | C | R | R | C | C | C | I | I |
| **Sprint / Iteration Plan** | A/R | C | R | C | C | C | I | I | I |
| **CI/CD Pipeline & Environments** | I | I | C | C | I | I | A/R | I | I |
| **Risk Register** | A/R | C | C | C | I | C | C | I | I |
| **Release Plan & Milestones** | A/R | C | C | C | I | I | C | C | I |
| **Go / No-Go Decision** | R | C | I | R | I | I | C | A | I |
| **Status Reports** | A/R | I | I | I | I | I | I | I | I |
| **Quality Gate Sign-off** | A | C | R | A/R | I | I | C | I | I |
| **Retrospective Actions** | A/R | C | R | C | C | C | C | I | C |
| **Community / Release Comms** | C | C | I | I | I | I | I | I | A/R |

---

## Notes
- Where two symbols appear (e.g., A/R), the same person is both accountable and doing the work.
- This matrix reflects typical ownership patterns; projects may adjust roles to fit team size and structure.
- Each artifact should have **exactly one Accountable (A)** owner. If your project assigns accountability differently, update accordingly.

## Related Docs
- [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) — full role definitions and responsibilities
- [`octoacme-project-management-overview.md`](octoacme-project-management-overview.md) — lifecycle and principles
- [`octoacme-project-initiation.md`](octoacme-project-initiation.md) — initiation checklist and one-pager template
- [`octoacme-project-planning.md`](octoacme-project-planning.md) — planning activities and Definition of Done
- [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md) — quality gates and execution workflow
