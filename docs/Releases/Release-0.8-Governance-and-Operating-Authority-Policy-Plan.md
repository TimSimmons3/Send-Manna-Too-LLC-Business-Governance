# Release 0.8 Governance and Operating Authority Policy Plan

## Document Control

| Field | Value |
| --- | --- |
| Project | Send Manna Too LLC Business Governance Framework |
| Release | 0.8 |
| Release Name | Governance and Operating Authority Policy |
| Document Type | Release Plan |
| Status | Draft for controlled execution |
| Canonical Source | Markdown in Git |

## Objective

Draft and approve the first controlled governance policy for Send Manna Too LLC: Governance and Operating Authority Policy.

## Scope

Release 0.8 is limited to one primary policy document:

- `docs/Foundation/Governance-and-Operating-Authority-Policy.md`

The policy will define governance authority, decision rights, approval expectations, exception handling, accountability, controlled operating discipline, and relationship to the Constitution.

## Out of Scope

Release 0.8 will not:

- Draft any other governance policy.
- Change the Release 0.1 governance architecture.
- Change the document hierarchy.
- Change publication procedures or templates.
- Generate Word, PDF, or PowerPoint publication artifacts unless separately approved after Markdown source approval.
- Replace or duplicate existing standards, procedures, templates, or release records.

## Source Documents for Alignment

Release 0.8 will align to the following existing governance sources:

- Constitution
- Document Hierarchy Standard
- Document Quality Standard
- Release 0.7 Core Governance Policy Set Planning Record
- Release 0.7 Core Governance Policy Set Planning Closeout

## Planned Deliverables

Release 0.8 deliverables are:

1. `docs/Releases/Release-0.8-Governance-and-Operating-Authority-Policy-Plan.md`
2. `docs/Foundation/Governance-and-Operating-Authority-Policy.md`
3. `docs/Releases/Release-0.8-Governance-and-Operating-Authority-Policy-Closeout.md`
4. Updated `CHANGELOG.md`

## Execution Sequence

1. Validate the clean Release 0.7 baseline.
2. Create this Release 0.8 plan.
3. Inventory source governance documents for alignment and duplicate guidance risk.
4. Draft the Governance and Operating Authority Policy.
5. Validate hierarchy alignment, purpose separation, ASCII, trailing whitespace, and Markdown quality.
6. Review and approve the Markdown policy source.
7. Update the changelog.
8. Create Release 0.8 closeout.
9. Commit, push, tag, back up, copy to iCloud, and checksum-validate after closeout.

## Quality Gates

Release 0.8 must pass the following gates:

- Working tree clean before execution.
- Branch `main` aligned with `origin/main` before execution.
- Release 0.7 tag validated before execution.
- Policy has one primary purpose.
- Policy does not duplicate the Constitution, standards, procedures, templates, or release records.
- Policy aligns to the approved document hierarchy.
- Markdown files are ASCII-clean.
- Markdown files contain no trailing whitespace.
- `git diff --check` passes before commit.
- Markdown in Git remains the authoritative source.

## Approval Criteria

Release 0.8 is complete when:

- The Governance and Operating Authority Policy is created and approved in Markdown.
- The policy is validated against the approved governance architecture.
- The changelog is updated.
- Release 0.8 closeout is created.
- All Release 0.8 files are committed and pushed.
- A Release 0.8 tag is created and validated.
- A clean backup zip is created from the Release 0.8 tag.
- The backup is copied to iCloud.
- Checksum validation passes.

## Risk Controls

Primary Release 0.8 risks and controls:

| Risk | Control |
| --- | --- |
| Scope creep into other policies | Limit Release 0.8 to one policy only. |
| Duplicate governance guidance | Validate against the Constitution, standards, and Release 0.7 planning record. |
| Architecture drift | Do not change the Release 0.1 governance architecture. |
| Publication confusion | Keep DOCX, PDF, and PowerPoint out of scope unless separately approved. |
| Source control ambiguity | Keep Markdown in Git as canonical. |

## Release Decision

Release 0.8 is approved to proceed to controlled policy drafting after this plan is created, reviewed, validated, committed, and synchronized.
