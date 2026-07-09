# Release 0.4 Word Publication Template Remediation Plan

## Release

Release 0.4 - Word Publication Template Remediation

## Status

Complete

## Purpose

Release 0.4 remediates the open Word publication template logo placement defect carried forward from Release 0.3 as FC-0002.

The objective is to produce, validate, approve, and commit a controlled Word DOCX publication template only after the logo placement defect is corrected and visually validated.

## Scope

Release 0.4 is limited to Word publication template remediation.

In scope:

- Validate the current repository state before work begins.
- Review the existing Word publication template specification.
- Review the Release 0.3 Word template defect record.
- Create or regenerate a Word DOCX publication template.
- Correct the logo placement so that it is:
  - smaller
  - upper-left aligned
  - professionally positioned
  - consistent with a business report, letterhead, or webpage-header style
  - not oversized
- Confirm the footer includes Property and Confidential.
- Confirm page numbering follows Page 1 of X Pages where technically supported.
- Validate the Word DOCX visually on Mac.
- Update the Word defect record.
- Update FC-0002 in FUTURE-CONSIDERATIONS.md.
- Update CHANGELOG.md.
- Create a Release 0.4 closeout record.
- Commit, push, synchronize, tag, back up, copy to iCloud, and checksum-validate after approval.

Out of scope:

- Changing the frozen Release 0.1 governance architecture.
- Reworking the PowerPoint artifact.
- Reworking the branding PNG.
- Changing PDF export expectations unless required to reflect the approved Word remediation.
- Adding new publication artifact types.
- Expanding the release scope without a decision record.

## Authoritative Source Rules

Markdown in Git remains canonical.

The Word DOCX is a publication artifact only.

The Word DOCX must not be treated as approved until the Release 0.4 validation criteria pass.

Any prior generated Word DOCX download remains unapproved and must not be committed unless corrected and validated.

## Inputs

Primary inputs:

- docs/Releases/Release-0.3-Publication-Artifact-Templates-Closeout.md
- artifacts/Publication-Templates/Word/Send-Manna-Too-LLC-Word-Publication-Template.md
- artifacts/Publication-Templates/Validation/Release-0.3-Word-Template-Defect-Record.md
- docs/Checklists/Publication-Artifact-Validation-Checklist.md
- FUTURE-CONSIDERATIONS.md
- CHANGELOG.md

Branding input:

- artifacts/Publication-Templates/Branding/SMT-V2-Horizontal-Premium-Locked.png

## Acceptance Criteria

Release 0.4 is complete only when all criteria pass:

1. The repository starts from a clean synchronized Release 0.3 closeout state.
2. The Word DOCX artifact exists at the approved controlled path.
3. The Word logo is visually confirmed as smaller and upper-left aligned.
4. The logo does not appear oversized.
5. The visual result is consistent with professional business-report or letterhead styling.
6. The footer includes Property and Confidential.
7. Page numbering follows Page 1 of X Pages where technically supported.
8. The Word DOCX opens successfully on Mac.
9. The Word DOCX checksum is recorded.
10. The Release 0.3 Word defect record is updated with the remediation result.
11. FC-0002 is updated in FUTURE-CONSIDERATIONS.md.
12. CHANGELOG.md records Release 0.4.
13. A Release 0.4 closeout record is created.
14. The approved Word DOCX artifact is committed only after validation passes.
15. The repository is clean and synchronized after push.
16. A Release 0.4 local tag is created.
17. A clean release backup zip is created, copied to iCloud, and checksum-validated.

## Validation Plan

Validation will include:

- Git state validation.
- Required file presence checks.
- Markdown ASCII check.
- Markdown trailing whitespace check.
- Unresolved placeholder marker check.
- Word DOCX file presence check after remediation.
- Word DOCX checksum capture.
- Manual visual validation on Mac.
- Footer validation.
- Page numbering validation where technically supported.
- Defect record validation.
- Future considerations validation.
- Changelog validation.
- Final repository synchronization validation.
- Release tag validation.
- Backup checksum validation.

## Release Control

No Word DOCX artifact may be committed until the visual validation confirms the logo placement defect has been corrected.

If the defect cannot be remediated in Release 0.4, the release must either remain open or close with an explicit approved exception and updated defect record.

## Planned Closeout Evidence

Expected closeout evidence will include:

- Final Word DOCX controlled artifact path.
- Final Word DOCX SHA-256 checksum.
- Updated defect record.
- Updated FC-0002 status.
- Updated CHANGELOG.md.
- Release 0.4 closeout record.
- Final Git commit hash.
- Final Git tag.
- Local backup zip path.
- Backup SHA-256 checksum.
- iCloud backup validation result.
