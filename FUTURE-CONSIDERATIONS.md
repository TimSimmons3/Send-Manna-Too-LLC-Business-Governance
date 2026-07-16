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
Status: Implemented
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

Implemented. Release 0.2 established controlled publication requirements and procedures. Release 0.3 established publication artifact specifications, the controlled branding asset record, the PowerPoint publication template artifact, and PDF export expectations. Release 0.4 remediated and approved the Word DOCX publication template. Releases 0.5 and 0.6 validated publication workflow use and repeatability against two canonical Markdown sources.

The controlled publication-template capability is complete. Production publication of the complete governance framework is separate end-stage roadmap work governed by DEC-0011 and is not an open template requirement.

### Related Artifacts

- docs/Standards/Document-Quality-Standard.md
- DECISIONS-LOG.md
- docs/Templates/Word-Publication-Template-Requirements.md
- docs/Templates/PDF-Publication-and-Export-Approach.md
- docs/Templates/PowerPoint-Publication-Template-Requirements.md
- docs/Procedures/Publication-and-Export-Procedure.md
- artifacts/Publication-Templates/Word/Send-Manna-Too-LLC-Word-Publication-Template.docx
- artifacts/Publication-Templates/PowerPoint/Send-Manna-Too-LLC-PowerPoint-Publication-Template.pptx
- artifacts/Publication-Samples/Release-0.5/Send-Manna-Too-LLC-Document-Hierarchy-Standard-Sample-Publication.docx
- artifacts/Publication-Samples/Release-0.6/Send-Manna-Too-LLC-Document-Quality-Standard-Sample-Publication.docx
- docs/Releases/Release-1.5-Core-Governance-Policy-Set-Completion-Review-and-Next-Phase-Planning-Record.md

## FC-0002: Remediate Word Publication Template Logo Placement

Date Added: 2026-07-09
Status: Implemented
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

Implemented in Release 0.4. The Word DOCX artifact was regenerated, visually validated on Mac, checksum-recorded, and committed at the controlled publication artifact path.

### Related Artifacts

- artifacts/Publication-Templates/Word/Send-Manna-Too-LLC-Word-Publication-Template.md
- artifacts/Publication-Templates/Validation/Release-0.3-Word-Template-Defect-Record.md
- artifacts/Publication-Templates/PowerPoint/Send-Manna-Too-LLC-PowerPoint-Publication-Template.pptx

### Release 0.4 Remediation Update

Implementation Outcome: Completed in Release 0.4.

On 2026-07-09, the Word DOCX publication template was regenerated at the controlled path:

artifacts/Publication-Templates/Word/Send-Manna-Too-LLC-Word-Publication-Template.docx

The logo placement was manually visually validated on Mac and confirmed to satisfy the Release 0.4 remediation objective:

1. Smaller upper-left logo placement.
2. Professional business-report, letterhead, or webpage-header style.
3. Footer includes Property and Confidential.
4. Page numbering follows Page 1 of X Pages where technically supported.
5. No unintended client data observed.

DOCX SHA-256:

f2a4f3e98a60bd7acd0e372f6efec1d337845e365a5f7e5e8d27c6312005c5a5

FC-0002 was implemented in Release 0.4. Release tag and backup controls remain part of the final release packaging process.

## FC-0003: Replace Interim USB Backup and Reassess Cloud Encryption

Date Added: 2026-07-16
Status: Deferred
Category: Private Commercial Operations / Backup / Recovery / Security
Priority: High
Applies To: Release 2.6 G2 private authoritative source, independent backup, recovery, and future cloud-storage use
Risk Reference: RSK-2.6-001

### Context

Release 2.6 temporarily uses a FileVault-protected local-only private authoritative source and an encrypted 64 GB SanDisk USB flash drive as the independent backup destination.

The USB was formatted as APFS (Encrypted), a representative non-sensitive artifact was backed up and restored, the source, backup, and restored SHA-256 values matched, byte comparison passed, and APFS volume verification completed successfully.

Advanced Data Protection for iCloud is currently off. Therefore, iCloud Drive is not approved as the authoritative private commercial source under the interim design. Google Drive and OneDrive synchronization are also not approved as independent backup methods without separately controlled client-side encryption, versioning, and recovery validation.

### Consideration

Replace or supplement the interim USB flash backup with a more durable independent recovery solution, preferably:

1. An encrypted external SSD or external hard drive; or
2. A client-side encrypted, versioned cloud-backup destination separate from the authoritative source.

Before any future use of iCloud Drive as the authoritative private commercial source:

1. Configure an approved Apple Account recovery method.
2. Enable and validate Advanced Data Protection.
3. Confirm the private folder is not shared.
4. Repeat G2 access, encryption, backup, and representative recovery validation.
5. Update the private repository control and backup-recovery evidence.

### Rationale

The interim USB flash drive provides encrypted independent recovery, but it has lower durability, automation, capacity, failure visibility, and physical resilience than a dedicated external SSD, external hard drive, managed network backup, or client-side encrypted cloud-backup service.

The current design also lacks offsite or geographic separation. Theft, fire, flood, physical damage, loss, media failure, missed manual backups, or capacity exhaustion could affect recoverability.

Advanced Data Protection is not required while the authoritative source remains local-only and protected by FileVault. It becomes a gating requirement if iCloud Drive is later proposed as the authoritative private source.

### Current Disposition

Deferred and temporarily accepted with compensating controls.

The interim design may support a G2 Passed with Conditions decision only after the local-only authoritative source, access restrictions, encryption, backup procedure, representative recovery, and private evidence records are fully validated.

Required compensating controls:

1. Keep the authoritative source outside iCloud Drive, Google Drive, OneDrive, and public Git.
2. Keep FileVault enabled.
3. Keep the USB encrypted.
4. Connect the USB only for controlled backup or recovery activity.
5. Store the USB securely and separately from the Mac when practical.
6. Perform a backup after each material private-record change.
7. Perform periodic checksum and representative recovery testing.
8. Monitor available capacity and media errors.
9. Preserve private backup and recovery evidence under `PRV-COM-2.6-001` and `PRV-COM-2.6-009`.
10. Reopen G2 immediately after an encryption, backup, restore, checksum, access-control, or media-integrity failure.

Required reassessment triggers:

1. Before recurring live commercial operations begin.
2. Before the private commercial source exceeds 10 GB.
3. After any USB error, failed backup, failed restore, or checksum difference.
4. When a suitable durable backup device or controlled encrypted cloud-backup option becomes available.
5. During Release 2.6 closeout and each later applicable release or annual review.
6. Before iCloud Drive is used as an authoritative private commercial source.

### Related Artifacts

- `docs/Releases/Release-2.6-Private-Commercial-Operations-Foundation-Plan.md`
- `docs/Standards/Private-Commercial-Operations-and-Confidential-Records-Standard.md`
- `docs/Standards/Pricing-and-Commercial-Approval-Standard.md`
- `docs/Checklists/Private-Commercial-Artifact-Inventory-and-Control-Matrix.md`
- `docs/Checklists/Commercial-Model-Validation-and-Reconciliation-Checklist.md`
- `docs/Checklists/Commercial-Scenario-and-KPI-Control-Matrix.md`
- `docs/Releases/Release-2.6-Private-Commercial-Operations-Foundation-Record.md`
- `docs/Releases/Release-2.6-Private-Commercial-Operations-Foundation-Closeout.md`
- `PRV-COM-2.6-001`
- `PRV-COM-2.6-009`
