---
title: "GitHub Setup"
---

# GitHub Setup and ChatGPT Integration

GitHub provides version history, durable Markdown files, reviewable changes, and a workspace for repeated job-search tasks.

## Create two repositories

### Private career workspace

Create a private repository such as `career-tools`. Store your master inventory, original resumes, company and job-posting research, role assessments, tailored resumes, application notes, and reusable prompts here.

Keep it private. A public repository is not appropriate for detailed career history, contact details, or application records.

### Public playbook

Use this repository for generic guidance, examples, and reusable templates. Do not copy private candidate data into it.

## Connect GitHub to ChatGPT

The exact UI can change, but the general process is:

1. Open ChatGPT settings and find the connected apps area.
2. Connect GitHub.
3. Complete GitHub authorization.
4. Grant access only to repositories needed for the task, where repository selection is available.
5. Ask ChatGPT to inspect the private career-tools repository and confirm which files it can read.

A GitHub integration may expose repository contents and, depending on permissions and supported actions, allow changes. Review requested permissions and limit repository access.

## Repository instructions

Put an `AGENTS.md` at the root of the private repository. Explain which file is canonical, which files must be read before generating a resume, how to create company and opportunity folders, accuracy and confidentiality rules, and whether changes require pull requests.

## Recommended private workspace

Use one Title Case company folder per employer or target company. Keep research that applies to the company at its root, and create a separate opportunity folder for every distinct job posting or application.

    career-tools/
    ├── AGENTS.md
    ├── README.md
    ├── career/
    │   └── master-career-inventory.md
    ├── resume-sources/
    │   └── original resumes...
    ├── companies/
    │   ├── Home Depot/
    │   │   ├── company-research.md
    │   │   ├── recruiters.md
    │   │   ├── base-resumes/
    │   │   └── job-roles/
    │   │       └── 2026-11 - Staff Engineer/
    │   │           ├── job-posting.md
    │   │           ├── match.md
    │   │           ├── application-notes.md
    │   │           └── resume.md
    │   ├── Monarch Money/
    │   │   ├── company-research.md
    │   │   ├── recruiters.md
    │   │   ├── base-resumes/
    │   │   └── job-roles/
    │   │       ├── 2026-11 - Future Engineering Opportunities/
    │   │       └── 2026-12 - Staff Software Engineer/
    │   └── USAA/
    │       ├── base-resumes/
    │       └── job-roles/
    └── prompts/
        ├── inventory-interview.md
        ├── full-company-and-role-search.md
        └── resume-generation.md

### Folder rules

- Company folder names use recognizable Title Case with spaces (for example, `Home Depot`, `Hub Spot`, `Monarch Money`, `USAA`). Do not use lowercase company slugs.
- `company-research.md` and `recruiters.md` are shared across opportunities at that company.
- `base-resumes/` holds reusable company-level resume starting points, optionally grouped by role family or positioning.
- Every distinct posting/application gets its own folder under `job-roles/`. A readable name such as `YYYY-MM - Role Title` keeps repeated roles separate.
- Keep the posting, role match, application status/notes, and final tailored resume together in that opportunity folder. Never overwrite one role's materials with another role's.
- A general talent pipeline application still gets its own opportunity folder, clearly labeled as a pipeline rather than a confirmed requisition.
- Preserve source resumes unchanged under `resume-sources/`; they are evidence, not the canonical inventory or final tailored resumes.

## What GitHub MCP means

MCP (Model Context Protocol) is one way an AI application can connect to external tools and data. The ChatGPT GitHub app/integration can let the assistant search repositories, read files, and perform supported GitHub actions. Exact capabilities depend on the connected app, permissions, and product configuration.

You do not need to build your own MCP server for this workflow. Use the supported GitHub integration and verify its current permissions before asking it to write.

## Security checklist

- Keep the personal career workspace private.
- Never commit credentials, access tokens, private keys, or confidential employer data.
- Avoid uploading customer/member information, proprietary diagrams, source code, or internal-only documents.
- Review AI-generated commits and diffs.
- Use least-privilege repository access.
- Enable two-factor authentication on GitHub.
- Use branch protection and required reviews if others can contribute.
