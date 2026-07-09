# Release 0.5 Publication Workflow Validation and Operating Use Test Plan

## Project

Send Manna Too LLC Business Governance Framework

## Release

Release 0.5 - Publication Workflow Validation and Operating Use Test

## Status

Planned

## Purpose

The purpose of Release 0.5 is to validate that the approved Word publication template can be used in an operating workflow to produce a clean, readable, branded publication artifact from an existing canonical Markdown governance document.

Release 0.5 is an operating use test. It does not expand the governance architecture, create new policy content, or change the authoritative document hierarchy unless a defect or controlled improvement is identified and approved.

## Release Scope

Release 0.5 will:

1. Validate the repository starts from the approved Release 0.4 closeout baseline.
2. Use the approved Word publication template to produce one sample publication output from an existing Markdown governance document.
3. Confirm that Markdown remains the canonical source of record.
4. Confirm that Word output is treated as a publication-only artifact.
5. Validate publication branding, footer language, page numbering, readability, layout, and document hygiene.
6. Identify any workflow gaps or template refinements.
7. Record results in the appropriate release documentation, change records, and future considerations if needed.
8. Close out the release through commit, push, tag, local backup, iCloud backup, and checksum validation.

## Out of Scope

Release 0.5 will not:

1. Draft new governance policies, standards, frameworks, or procedures.
2. Redesign the governance architecture.
3. Change the Release 0.1 frozen document hierarchy.
4. Replace Markdown as the canonical source format.
5. Convert all governance documents into Word.
6. Add broad publication automation unless a specific defect requires a controlled remediation item.
7. Modify branding standards outside the already approved publication requirements.

## Source Baseline

The source baseline for Release 0.5 is Release 0.4.

Expected latest commit:

`5da407d Document Release 0.4 closeout`

Expected local tag:

`release-0.4-word-publication-template-remediation-closeout`

Expected approved Word publication template:

`artifacts/Publication-Templates/Word/Send-Manna-Too-LLC-Word-Publication-Template.docx`

Expected approved Word publication template SHA-256:

`f2a4f3e98a60bd7acd0e372f6efec1d337845e365a5f7e5e8d27c6312005c5a5`

## Candidate Source Document

The preferred candidate source document for the operating use test is:

`docs/Document-Hierarchy-Standard.md`

Reason:

This document is appropriate for a first publication workflow test because it is governance-relevant, structurally meaningful, and should allow validation of headings, body text, readability, branding, footer, and page numbering without introducing new governance content.

If this document is unavailable or unsuitable after inspection, another existing Markdown governance document may be selected and the reason must be recorded in the Release 0.5 closeout.

## Planned Publication Output

Planned sample publication artifact:

`artifacts/Publication-Samples/Release-0.5/Send-Manna-Too-LLC-Document-Hierarchy-Standard-Sample-Publication.docx`

Optional supporting validation notes may be created at:

`artifacts/Publication-Samples/Release-0.5/Release-0.5-Publication-Workflow-Validation-Notes.md`

## Validation Criteria

Release 0.5 will be considered successful if the following validation criteria pass:

1. Repository begins from a clean synchronized Release 0.4 baseline.
2. Approved Word publication template checksum matches the recorded Release 0.4 checksum.
3. Selected Markdown source document exists and remains unchanged unless a controlled release update is required.
4. Sample Word publication output is created in the controlled Release 0.5 sample publication path.
5. Word output opens successfully on Mac.
6. Branding is present and visually appropriate.
7. Footer includes `Property and Confidential`.
8. Page numbering follows `Page 1 of X Pages` where technically supported.
9. Document is readable by a non-technical business audience.
10. No unintended client data, unrelated project data, secrets, credentials, or personal data are introduced.
11. Markdown remains canonical.
12. Word output is clearly treated as publication-only.
13. Any workflow gaps are recorded in the appropriate release closeout or Future Considerations Register.
14. `CHANGELOG.md` is updated.
15. Release 0.5 closeout record is created.
16. Markdown ASCII validation passes.
17. Markdown trailing whitespace validation passes.
18. Git repository is clean after commit and synchronization.
19. Release 0.5 tag is created and validated.
20. Local backup zip is created from the Release 0.5 tag.
21. Backup zip is copied to iCloud.
22. iCloud backup checksum validation passes.

## Risks and Controls

| Risk | Control |
|---|---|
| Word output is treated as authoritative | Reconfirm Markdown in Git remains canonical |
| Template formatting does not work with real governance content | Use an existing Markdown document for an operating use test |
| Branding or footer regression occurs | Validate header, footer, and page numbering in the generated DOCX |
| Manual conversion introduces content drift | Compare source document purpose and sample output for obvious omissions or unintended additions |
| Broad policy drafting expands the release | Keep Release 0.5 limited to workflow validation |
| Hidden formatting or package defects appear in DOCX | Validate DOCX package integrity and perform manual Mac visual review |
| Backup or synchronization evidence is incomplete | Capture commit, tag, checksum, local backup, iCloud copy, and checksum validation evidence |

## Planned Release Artifacts

Release 0.5 is expected to create or update the following artifacts:

1. `docs/Releases/Release-0.5-Publication-Workflow-Validation-and-Operating-Use-Test-Plan.md`
2. `docs/Releases/Release-0.5-Publication-Workflow-Validation-and-Operating-Use-Test-Closeout.md`
3. `artifacts/Publication-Samples/Release-0.5/Send-Manna-Too-LLC-Document-Hierarchy-Standard-Sample-Publication.docx`
4. `artifacts/Publication-Samples/Release-0.5/Release-0.5-Publication-Workflow-Validation-Notes.md`
5. `CHANGELOG.md`
6. `FUTURE-CONSIDERATIONS.md`, only if a future item is identified

## Planned Git Commit Strategy

Recommended commits:

1. `Add Release 0.5 publication workflow validation plan`
2. `Add Release 0.5 sample publication workflow output`
3. `Document Release 0.5 closeout`

## Planned Release Tag

Recommended local tag:

`release-0.5-publication-workflow-validation-operating-use-test-closeout`

## Approval Gate

Release 0.5 may proceed after the Release 0.5 plan is created, validated, committed, pushed, and synchronized.

## Release Owner

Send Manna Too LLC

## Notes

This release is intentionally narrow. The goal is to prove that the publication workflow works in practice before broader publication production begins.
