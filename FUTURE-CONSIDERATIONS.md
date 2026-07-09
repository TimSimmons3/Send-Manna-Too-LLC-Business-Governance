# Send Manna Too LLC Future Considerations Register

## 1. Document Control

Version: 0.1
Status: Approved
Owner: Send Manna Too LLC
Canonical Source: Markdown in Git repository
Applies To: Future governance, operating-model, publication, commercial, partner, client-engagement, template, and framework improvement ideas
Effective Date: 2026-07-08
Review Cycle: At least annually or during release planning

## 2. Purpose

This register captures ideas, enhancements, backlog items, and potential future work that may be useful but are not approved for current release scope.

The purpose is to prevent uncontrolled scope expansion while preserving useful ideas for future review.

Items in this register are not approved requirements unless they are separately adopted through the Decision Register, an approved standard, or a later release plan.

## 3. Entry Format

Each future consideration should use the following structure:

- Future consideration ID
- Title
- Date added
- Status
- Category
- Priority
- Applies to
- Context
- Consideration
- Rationale
- Current disposition
- Related artifacts

## 4. Status Values

- Proposed: Captured for future review.
- Accepted for Backlog: Worth preserving for future planning but not approved for current scope.
- Partially Implemented: A related requirement has been adopted, but additional future work remains.
- Implemented: Completed and no longer active as a future consideration.
- Deferred: Intentionally postponed.
- Rejected: Considered and not accepted.

## 5. Future Considerations

## FC-0001: Controlled Publication Templates for Final Deliverables

Date Added: 2026-07-08
Status: Partially Implemented
Category: Publication / Templates / Quality
Priority: Medium
Applies To: Final client-facing, partner-facing, executive, and publication-ready deliverables

### Context

Final Send Manna Too LLC documents and deliverables require consistent branding, confidentiality marking, and page numbering.

The underlying publication requirement has been adopted in the Document Quality Standard and recorded in the Decision Register.

### Consideration

Create controlled Word, PDF, and PowerPoint publication templates that include the Send Manna Too LLC logo, Property and Confidential footer marking, and Page 1 of X Pages numbering where technically supported.

### Rationale

Controlled templates will reduce formatting drift, improve professionalism, support confidentiality posture, and help final deliverables remain traceable to the canonical Markdown source.

### Current Disposition

The requirement is approved. Release 0.2 implements controlled publication requirements and procedures. Release 0.3 has implemented controlled publication artifact specifications, a controlled branding asset record, a PowerPoint publication template artifact, and PDF export expectations. The Word binary publication template artifact remains open because the logo placement defect must be corrected or an approved exception is documented before approval.

### Related Artifacts

- docs/Standards/Document-Quality-Standard.md
- DECISIONS-LOG.md
- docs/Templates/Word-Publication-Template-Requirements.md
- docs/Templates/PDF-Publication-and-Export-Approach.md
- docs/Templates/PowerPoint-Publication-Template-Requirements.md
- docs/Procedures/Publication-and-Export-Procedure.md

## FC-0002: Remediate Word Publication Template Logo Placement

Date Added: 2026-07-09
Status: Accepted for Backlog
Category: Publication / Templates / Quality
Priority: Medium
Applies To: Word publication template artifact

### Context

Release 0.3 clarified that the approved Send Manna Too LLC logo should appear as a smaller, upper-left brand element similar to a professional webpage header, letterhead, or business report.

The PowerPoint publication template achieved the intended logo placement. The generated Word DOCX artifact did not visually satisfy the same placement requirement.

### Consideration

Create or remediate the Word publication template artifact so the approved logo is scaled down, positioned in the upper-left area, and visually consistent with professional business-document presentation.

### Rationale

Correcting the Word template will align the Word binary artifact with the approved Release 0.3 specification and reduce future publication rework.

### Current Disposition

Accepted for backlog. The Word DOCX artifact is not approved and must not be treated as a controlled publication artifact until the logo placement defect is corrected or an approved exception is documented.

### Related Artifacts

- artifacts/Publication-Templates/Word/Send-Manna-Too-LLC-Word-Publication-Template.md
- artifacts/Publication-Templates/Validation/Release-0.3-Word-Template-Defect-Record.md
- artifacts/Publication-Templates/PowerPoint/Send-Manna-Too-LLC-PowerPoint-Publication-Template.pptx
