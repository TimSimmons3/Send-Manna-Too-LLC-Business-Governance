# Release 1.2 - Third-Party and Partner Governance Policy Plan

## Release Objective

Draft and approve the fifth controlled governance policy: Third-Party and Partner Governance Policy.

## Source Path

`docs/Foundation/Third-Party-and-Partner-Governance-Policy.md`

## Release Type

Policy-only governance release.

## Planning Decision

Release automation tooling is deferred.

Release 1.2 will not create or modify release automation scripts, release templates, publication workflows, or supporting tooling unless separately approved.

## Baseline

Release 1.1 - Information Handling and Confidentiality Policy is complete and closed out.

Baseline commit: `2121ab9 Document Release 1.1 closeout`

Baseline tag: `release-1.1-information-handling-and-confidentiality-policy-closeout`

## In Scope

Release 1.2 will define governance expectations for third-party and partner relationships, including:

- Third-party and partner governance principles
- Referral partners
- Subcontractors
- Vendors
- External collaborators
- Partner qualification
- Partner authorization
- Partner role clarity
- Partner information sharing boundaries
- Partner confidentiality expectations
- Client-facing partner involvement
- Partner-related commercial boundaries
- Partner-related evidence expectations
- Partner conflicts of interest
- Partner performance and conduct concerns
- Partner risk escalation
- Partner exceptions
- Relationship to client engagement governance
- Relationship to commercial and contracting governance
- Relationship to information handling and confidentiality governance
- Relationship to future records and external deliverable policies

## Out of Scope

Release 1.2 will not create:

- Vendor security technical control standards
- Cybersecurity assessment procedures
- Procurement procedures
- Third-party onboarding checklists
- Referral agreement templates
- Subcontractor agreement templates
- NDA clauses
- Legal advice
- Contract templates
- Records retention schedules
- External deliverable review procedures
- Publication workflow changes
- Word, PDF, or PowerPoint publication artifacts
- Changes to the frozen Release 0.1 governance architecture

## Source Documents for Review

Before drafting, review:

- `docs/Foundation/Send-Manna-Too-LLC-Constitution.md`
- `docs/Standards/Document-Hierarchy-Standard.md`
- `docs/Standards/Document-Quality-Standard.md`
- `docs/Foundation/Governance-and-Operating-Authority-Policy.md`
- `docs/Foundation/Client-Engagement-Governance-Policy.md`
- `docs/Foundation/Commercial-and-Contracting-Governance-Policy.md`
- `docs/Foundation/Information-Handling-and-Confidentiality-Policy.md`
- `docs/Releases/Release-0.7-Core-Governance-Policy-Set-Planning-Record.md`
- `CHANGELOG.md`

## Drafting Guardrails

- Maintain Release 0.1 governance architecture.
- Keep Markdown in Git as the canonical source.
- Create one policy only.
- Keep the document governance-level.
- Avoid duplicate guidance.
- Avoid legal advice and contract-template language.
- Avoid vendor cybersecurity technical control detail.
- Avoid procurement procedure detail.
- Avoid records retention detail.
- Avoid external deliverable governance detail.
- Avoid publication workflow detail.

## Validation Requirements

- Release 1.1 baseline is clean and synchronized.
- Release 1.1 tag points to `2121ab9`.
- Required source documents are present.
- Target Release 1.2 policy does not already exist before drafting.
- Release 1.2 plan is created, validated, committed, pushed, and synchronized before drafting.
- Source review is completed before drafting.
- Draft policy avoids duplicate guidance.
- Draft policy remains governance-level.
- Draft policy avoids legal advice and contract-template language.
- Draft policy avoids vendor cybersecurity technical control detail.
- Draft policy avoids records retention, external deliverable, and publication detail.
- Markdown ASCII validation passes.
- Markdown trailing whitespace validation passes.
- `git diff --check` passes.
- `CHANGELOG.md` is updated.
- Release 1.2 closeout record is created.
- Final closeout commit is pushed and synchronized.
- Local Release 1.2 tag is created and validated.
- Local backup zip is created from the tag.
- SHA-256 checksum file is created and validated.
- Backup zip and checksum file are copied to iCloud.
- iCloud checksum matches local checksum.
- Final sanity check passes.

## Planned Deliverables

- `docs/Releases/Release-1.2-Third-Party-and-Partner-Governance-Policy-Plan.md`
- `docs/Foundation/Third-Party-and-Partner-Governance-Policy.md`
- `docs/Releases/Release-1.2-Third-Party-and-Partner-Governance-Policy-Closeout.md`
- Updated `CHANGELOG.md`

## First Implementation Step After Plan Approval

Review the required source documents for hierarchy alignment, duplicate guidance risk, and Release 1.2 scope boundaries before drafting the policy.
