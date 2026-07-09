# Send Manna Too LLC Decision Register

## 1. Document Control

Version: 0.1
Status: Approved
Owner: Send Manna Too LLC
Canonical Source: Markdown in Git repository
Applies To: Material governance, architecture, release-scope, operating-model, exception, and standards decisions
Effective Date: 2026-07-08
Review Cycle: At least annually or upon material governance, business, legal, commercial, or operating-model change

## 2. Purpose

This register records material decisions for the Send Manna Too LLC Business Governance Framework.

The purpose is to preserve decision traceability, prevent undocumented scope expansion, support auditability, and maintain one source of truth for governance decisions.

Routine edits, ordinary commits, command history, and non-material working notes do not belong in this register.

## 3. Decision Entry Format

Each decision entry should use the following structure:

- Decision ID
- Decision title
- Date
- Status
- Decision owner
- Decision type
- Applies to
- Context
- Decision
- Rationale
- Impact
- Related artifacts

## 4. Decision Status Values

- Proposed: The decision is under consideration and is not yet approved.
- Approved: The decision is accepted and active.
- Superseded: The decision has been replaced by a later approved decision.
- Deferred: The decision is not active and may be reconsidered later.
- Rejected: The decision was considered and not accepted.

## 5. Decision Log

## DEC-0001: Freeze Release 0.1 Governance Architecture

Date: 2026-07-08
Status: Approved
Decision Owner: Send Manna Too LLC
Decision Type: Architecture / Scope
Applies To: Release 0.1 Foundation

### Context

The framework needed a stable foundation before disciplined execution could begin.

### Decision

The Release 0.1 governance architecture is frozen unless a proposed change materially improves the framework and is documented through an approved decision.

### Rationale

A frozen architecture prevents uncontrolled expansion, duplicate guidance, and unstable document design during the foundation release.

### Impact

New ideas default to the Future Considerations Register unless formally approved for inclusion.

### Related Artifacts

- docs/Foundation/Release-0.1-Development-Plan.md
- docs/Foundation/Send-Manna-Too-LLC-Constitution.md
- FUTURE-CONSIDERATIONS.md

## DEC-0002: Adopt Controlled Document Hierarchy

Date: 2026-07-08
Status: Approved
Decision Owner: Send Manna Too LLC
Decision Type: Architecture / Standard
Applies To: All framework documents

### Context

The framework requires a clear hierarchy so each document has one primary purpose and conflicts are resolved consistently.

### Decision

The approved hierarchy is Constitution, Policies, Standards, Frameworks, Procedures / Playbooks, Templates / Checklists / Scripts, and Records.

### Rationale

A controlled hierarchy reduces duplication, improves traceability, and supports long-term maintainability.

### Impact

All framework documents must align to the hierarchy and placement rules defined in the Document Hierarchy Standard.

### Related Artifacts

- docs/Foundation/Send-Manna-Too-LLC-Constitution.md
- docs/Standards/Document-Hierarchy-Standard.md

## DEC-0003: Use Markdown and Git as the Authoritative Source of Truth

Date: 2026-07-08
Status: Approved
Decision Owner: Send Manna Too LLC
Decision Type: Operating Model / Source of Truth
Applies To: All framework documents and publication outputs

### Context

The framework needs a durable, auditable, version-controlled source of truth.

### Decision

Markdown in the repository is the canonical source. Git is the authoritative version history. GitHub provides remote backup, synchronization, and review support.

### Rationale

This approach preserves traceability, reduces publication-format drift, and supports controlled change management.

### Impact

Word, PDF, PowerPoint, and other formatted outputs are publication formats, not authoritative sources, unless an approved exception states otherwise.

### Related Artifacts

- docs/Foundation/Send-Manna-Too-LLC-Constitution.md
- docs/Standards/Document-Quality-Standard.md

## DEC-0004: Require Controlled Document Development Lifecycle

Date: 2026-07-08
Status: Approved
Decision Owner: Send Manna Too LLC
Decision Type: Standard / Operating Model
Applies To: All Release 0.1 documents and future framework documents

### Context

The framework requires disciplined execution and review gates to ensure quality, auditability, and maintainability.

### Decision

Documents must follow the approved lifecycle: planning, outline review, draft, technical review, executive review, red team review, editorial review, approval, Git commit, GitHub push, and baseline.

### Rationale

The lifecycle reduces quality risk, prevents unmanaged scope expansion, and supports executive-ready deliverables.

### Impact

No document may bypass lifecycle steps unless an exception is documented, justified, and approved.

### Related Artifacts

- docs/Standards/Document-Quality-Standard.md

## DEC-0005: Require Final Deliverable Publication Controls

Date: 2026-07-08
Status: Approved
Decision Owner: Send Manna Too LLC
Decision Type: Standard / Publication
Applies To: Final client-facing, partner-facing, executive, and publication-ready deliverables

### Context

Final deliverables require consistent branding, confidentiality marking, and page numbering.

### Decision

Final publication-ready deliverables must include the Send Manna Too LLC logo in the header where supported, a footer confidentiality marking of Property and Confidential, and page numbering in the format Page 1 of X Pages where supported.

### Rationale

This protects brand consistency, confidentiality posture, professionalism, and publication quality.

### Impact

The requirement is implemented in the Document Quality Standard and may later be supported by controlled publication templates.

### Related Artifacts

- docs/Standards/Document-Quality-Standard.md
- FUTURE-CONSIDERATIONS.md

## DEC-0006: Use GitHub Desktop as Temporary Push Workaround

Date: 2026-07-08
Status: Approved
Decision Owner: Send Manna Too LLC
Decision Type: Operating Model / Exception
Applies To: Repository push workflow

### Context

Command-line Git push authentication is not fully working. GitHub Desktop push is working successfully.

### Decision

Use Terminal for local validation, editing, staging, commits, and post-push synchronization checks. Use GitHub Desktop to push commits until command-line authentication is fixed or formally changed.

### Rationale

This allows disciplined progress without blocking on authentication troubleshooting.

### Impact

Post-push validation must confirm local and remote synchronization from Terminal.

### Related Artifacts

- DECISIONS-LOG.md

## DEC-0007: Adopt Controlled Publication Template Requirements

Date: 2026-07-09
Status: Approved
Decision Owner: Send Manna Too LLC
Decision Type: Standard / Publication
Applies To: Release 0.2 publication template requirements

### Context

Release 0.2 requires controlled requirements for Word, PDF, and PowerPoint publication outputs.

### Decision

Adopt controlled publication template requirements for Word, PDF, and PowerPoint outputs while preserving Markdown in Git as the authoritative source of truth.

### Rationale

Controlled requirements reduce formatting drift, improve professionalism, and support traceability from publication outputs back to approved source content.

### Impact

Publication outputs must align with approved template requirements and must not replace canonical Markdown source records.

### Related Artifacts

- docs/Templates/Word-Publication-Template-Requirements.md
- docs/Templates/PDF-Publication-and-Export-Approach.md
- docs/Templates/PowerPoint-Publication-Template-Requirements.md

## DEC-0008: Adopt Controlled Publication and Export Procedure

Date: 2026-07-09
Status: Approved
Decision Owner: Send Manna Too LLC
Decision Type: Procedure / Publication
Applies To: Publication-ready outputs

### Context

Publication outputs require a repeatable procedure so Word, PDF, and PowerPoint files are generated, validated, and stored consistently.

### Decision

Adopt the Publication and Export Procedure as the controlled process for producing publication-ready outputs.

### Rationale

A controlled procedure reduces output drift, supports confidentiality markings, preserves traceability, and reinforces that publication formats are not authoritative source records.

### Impact

Publication outputs must be validated and traceable before approval or distribution.

### Related Artifacts

- docs/Procedures/Publication-and-Export-Procedure.md

## DEC-0009: Adopt Controlled Release Closeout Procedure

Date: 2026-07-09
Status: Approved
Decision Owner: Send Manna Too LLC
Decision Type: Procedure / Release Management
Applies To: Framework release closeout

### Context

Framework releases require consistent validation, approval, synchronization, tagging, backup, checksum validation, and handoff.

### Decision

Adopt the Release Closeout Procedure as the controlled process for closing framework releases.

### Rationale

A controlled closeout process improves recoverability, auditability, and release discipline.

### Impact

Future releases must follow the closeout procedure unless an approved exception is recorded.

### Related Artifacts

- docs/Procedures/Release-Closeout-Procedure.md

## DEC-0010: Defer Command-Line Git Push Authentication Remediation

Date: 2026-07-09
Status: Approved
Decision Owner: Send Manna Too LLC
Decision Type: Operating Model / Exception
Applies To: Repository push workflow

### Context

Command-line Git push authentication remains unresolved, while GitHub Desktop push remains available and validated.

### Decision

Defer command-line Git push authentication remediation from Release 0.2 unless it can be resolved without delaying primary release deliverables.

### Rationale

Release 0.2 should prioritize controlled publication and closeout capabilities without being blocked by authentication troubleshooting.

### Impact

GitHub Desktop remains the approved temporary push workaround. Terminal-based post-push validation remains required.

### Related Artifacts

- DEC-0006
- docs/Releases/Release-0.2-Publication-Templates-and-Operating-Closeout-Plan.md
