# The Master Career Inventory

The master inventory is the canonical, comprehensive record of your career. It is not intended to be sent to employers.

## Suggested sections

1. Career summary and target roles.
2. Employment timeline.
3. Each role: responsibilities, scope, teams, authority, technologies.
4. Projects: business problem, architecture, decisions, implementation, outcomes.
5. Leadership and influence examples.
6. Vendor and partner relationships.
7. Production operations, reliability, and incident response.
8. Technical skills grouped by actual depth.
9. Education and certifications.
10. Claims requiring validation.
11. Interview story bank.

## Recommended private repository layout

    career-tools/
    ├── AGENTS.md
    ├── README.md
    ├── career/
    │   └── master-career-inventory.md
    ├── resume-sources/
    ├── generated-resumes/
    ├── companies/
    │   └── company-slug/
    │       ├── company-research.md
    │       ├── job-posting.md
    │       ├── match.md
    │       └── recruiters.md
    └── prompts/

## Record evidence, not just keywords

Weak: "Used AWS, Java, and Kafka on modernization projects."

Stronger: "Implemented Kafka consumers that processed policy lifecycle events and synchronized updates to downstream systems. Personally owned consumer implementation and production troubleshooting; the platform team owned broker operations. Confirm exact consumer count before using a number."

The stronger version explains context, contribution, boundaries, and uncertainty.

## Track depth honestly

- **Hands-on:** designed or implemented directly.
- **Technical leadership:** guided implementation or reviewed decisions.
- **Architecture influence:** shaped tradeoffs while another person or team held final authority.
- **Operational:** supported, monitored, or troubleshot in production.
- **Exposure:** worked alongside the technology but cannot claim meaningful proficiency.

## Keep team outcomes distinct

Write "coordinated a team that delivered..." when accurate. Write "implemented..." only when you personally did the implementation. Leadership is valuable without pretending to have written every line of code.

## Update rules

- Add new facts when confirmed.
- Preserve historical source resumes.
- Do not rewrite career facts to match a job posting.
- Keep unresolved questions in the inventory.
- Never copy internal validation notes into an employer-facing resume.
- Separate personal projects from employer work.
