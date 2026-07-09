# Release 0.2 - Publication Templates and Operating Closeout Plan

## Document Control

| Field | Value |
| --- | --- |
| Document | Release 0.2 Publication Templates and Operating Closeout Plan |
| Owner | Send Manna Too LLC |
| Status | Approved |
| Canonical Source | Markdown in Git |
| Release | 0.2 |

## Purpose

This plan defines the controlled scope, deliverables, validation gates, and closeout criteria for Release 0.2 of the Send Manna Too LLC Business Governance Framework.

Release 0.2 builds on the approved Release 0.1 foundation by defining controlled publication templates and operating closeout procedures without changing the frozen Release 0.1 governance architecture.

## Release Objective

Create a controlled, repeatable publication and closeout capability for governance framework documents so that final deliverables can be exported consistently while preserving Markdown in Git as the authoritative source of truth.

## Scope

Release 0.2 includes:

- Controlled Word publication template requirements.
- Controlled PDF publication and export approach.
- Controlled PowerPoint publication template requirements.
- Publication and export procedure.
- Release closeout procedure.
- Required updates to the Decision Register, Future Considerations Register, and Change Log.

## Optional Scope

The following item may be addressed only if it does not delay the primary Release 0.2 deliverables:

- Command-line Git push authentication remediation.

If command-line Git push authentication is not resolved in Release 0.2, GitHub Desktop remains the approved temporary push workaround.

## Out of Scope

Release 0.2 does not include:

- Changes to the frozen Release 0.1 governance hierarchy.
- New business policies unrelated to publication or release closeout.
- Client-facing advisory content.
- Commercial templates.
- Partner governance content.
- Knowledge management content.
- Non-canonical Word, PDF, or PowerPoint files as source-of-truth records.

## Planned Deliverables

| Deliverable | Planned Path | Purpose |
| --- | --- | --- |
| Release 0.2 Plan | docs/Releases/Release-0.2-Publication-Templates-and-Operating-Closeout-Plan.md | Defines scope, gates, and closeout criteria for Release 0.2. |
| Word Publication Template Requirements | docs/Templates/Word-Publication-Template-Requirements.md | Defines controlled requirements for Word-formatted deliverables. |
| PDF Publication and Export Approach | docs/Templates/PDF-Publication-and-Export-Approach.md | Defines how PDFs are produced from canonical Markdown or approved publication formats. |
| PowerPoint Publication Template Requirements | docs/Templates/PowerPoint-Publication-Template-Requirements.md | Defines controlled requirements for presentation-format deliverables. |
| Publication and Export Procedure | docs/Procedures/Publication-and-Export-Procedure.md | Defines repeatable steps for producing publication-ready outputs. |
| Release Closeout Procedure | docs/Procedures/Release-Closeout-Procedure.md | Defines repeatable release validation, approval, tagging, backup, and closeout steps. |

## Quality Gates

Release 0.2 deliverables must satisfy the following gates before approval:

- Required files are present.
- Markdown files contain only ASCII characters.
- Markdown files contain no trailing whitespace.
- Final Release 0.2 deliverables contain no unresolved placeholder status markers.
- Each document has one primary purpose.
- Duplicate guidance is avoided.
- Canonical source-of-truth language remains aligned with Release 0.1 decisions.
- Publication formats are treated as controlled outputs, not authoritative sources.
- Decision Register is updated for new governance decisions.
- Future Considerations Register is updated for deferred items.
- Change Log is updated for Release 0.2.
- Git working tree is clean at closeout.
- Local main and origin/main are synchronized at closeout.

## Required Decisions

Release 0.2 is expected to require decisions for:

- Controlled publication template requirements.
- Controlled publication and export procedure.
- Controlled release closeout procedure.
- Whether command-line Git push authentication remains deferred or is remediated.

## Risks and Controls

| Risk | Control |
| --- | --- |
| Publication templates become treated as authoritative records. | Reaffirm that Markdown in Git remains canonical. |
| Word, PDF, or PowerPoint outputs drift from approved Markdown. | Require export controls and version traceability. |
| Duplicate procedural guidance appears across documents. | Keep each document purpose-specific and cross-reference instead of duplicating. |
| Scope expands into unrelated governance content. | Add a decision record before expanding Release 0.2 scope. |
| GitHub Desktop workaround creates sync ambiguity. | Require Terminal-based post-push validation. |

## Closeout Criteria

Release 0.2 may be closed only when:

- Planned deliverables are complete and reviewed.
- Required decisions are recorded.
- Deferred items are recorded in the Future Considerations Register.
- Change Log includes the Release 0.2 closeout entry.
- Validation gates pass.
- Release 0.2 approval commit is created.
- Release 0.2 closeout commit is created.
- GitHub push is completed.
- Terminal validation confirms local and remote alignment.
- Release tag is created.
- Backup package and checksum are created.
- Backup package is copied to the approved backup location.
- Backup checksum validation passes.

## Working Process

Use the established controlled workflow:

1. Plan.
2. Implement.
3. Validate.
4. Review.
5. Approve.
6. Commit.
7. Push.
8. Validate synchronization.
9. Tag.
10. Backup.
11. Checksum-validate.
12. Close out.

## Initial Hold Point

After this plan is created, validate the file for ASCII, trailing whitespace, completeness, and path correctness before creating additional Release 0.2 deliverables.
