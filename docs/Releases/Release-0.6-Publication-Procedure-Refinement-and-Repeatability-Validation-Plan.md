# Release 0.6 Publication Procedure Refinement and Repeatability Validation Plan

## Release Objective
Validate that the approved publication workflow is repeatable against a second canonical governance Markdown document and determine whether minor publication procedure clarification is needed.

## Scope
1. Confirm the clean Release 0.5 baseline.
2. Use docs/Standards/Document-Quality-Standard.md as the second repeatability source document.
3. Generate one controlled Word publication sample from the approved Word publication template.
4. Validate DOCX package integrity, required document parts, footer text, page numbering fields, and expected source title presence.
5. Manually review the generated Word publication output on Mac.
6. Record whether the Release 0.5 source-path discrepancy requires a minor publication procedure clarification.
7. Update records, CHANGELOG, and closeout after validation.

## Out of Scope
1. Broad governance policy drafting.
2. Governance architecture changes.
3. New document hierarchy rules.
4. New publication branding requirements.
5. Treating Word, PDF, or PowerPoint files as authoritative sources.

## Source and Output Paths
Source Markdown: docs/Standards/Document-Quality-Standard.md
Approved Word template: artifacts/Publication-Templates/Word/Send-Manna-Too-LLC-Word-Publication-Template.docx
Planned output directory: artifacts/Publication-Samples/Release-0.6
Planned sample output: artifacts/Publication-Samples/Release-0.6/Send-Manna-Too-LLC-Document-Quality-Standard-Sample-Publication.docx

## Validation Criteria
1. Repository starts clean and synchronized from Release 0.5.
2. Approved Word template checksum matches the Release 0.4 approved checksum.
3. Source Markdown exists at the canonical standards path.
4. Generated DOCX package opens as a valid DOCX archive.
5. Required DOCX package parts are present.
6. Footer contains Property and Confidential.
7. PAGE and NUMPAGES fields are present where technically supported.
8. Source document title is present in generated DOCX document XML.
9. Manual Mac visual review confirms branding, readability, footer, page numbering, and absence of unintended data.
10. Markdown files pass ASCII and trailing whitespace checks.

## Decision Point
If repeatability validation identifies only a source-path clarification need, update the publication/export procedure narrowly and record the rationale. If no procedure update is needed, record that conclusion and proceed to closeout.

## Planned Closeout
After validation, create a Release 0.6 closeout record, update CHANGELOG.md, commit, push using GitHub Desktop if needed, validate synchronization, tag locally, create a release backup zip, copy it to iCloud, and checksum-validate the iCloud backup.
