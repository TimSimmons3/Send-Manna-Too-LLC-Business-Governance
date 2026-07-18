# Release 2.6 Cross-Release Readiness Risk Register

## Document Control

| Field | Value |
| --- | --- |
| Organization | Send Manna Too LLC |
| Framework | Business Governance Framework |
| Related Change Control | `CC-2.6-001` |
| Related Decision | `DEC-0020` |
| Status | Approved and Active |
| Effective Date | 2026-07-18 |
| Owner | Founder and Managing Member |
| Scope | Risks created, increased, or materially affected by the Cross-Release Readiness Pull-Forward Workstream |
| Review Cadence | Weekly during active pull-forward work; at each gate, material change, reviewer response, and Release 2.6 closeout |
| Escalation Rule | Stop the affected activity when a High risk control fails or evidence is insufficient |

## 1. Register Rules

1. `RSK-2.6-001` remains authoritative through its existing FC-0003 linkage;
   this register mirrors it for consolidated monitoring and does not replace
   the existing primary record.
2. `RSK-2.6-002` through `RSK-2.6-009` are new active risks.
3. Every risk requires an owner, inherent severity, controls, trigger,
   response, residual severity, status, and review cadence.
4. A risk may close only with evidence that its closure criteria and
   dependent controls are satisfied.
5. Risk acceptance does not override a release, authority, information,
   qualified-review, contract, insurance, or external-execution gate.

## 2. Risk Summary

| Risk ID | Short Title | Inherent | Residual | Status |
| --- | --- | --- | --- | --- |
| `RSK-2.6-001` | Interim private-backup durability and concentration | High | Low to Moderate | Open - existing primary record remains FC-0003 |
| `RSK-2.6-002` | De facto second active release | High | Low to Moderate | Open - controlled |
| `RSK-2.6-003` | Premature reliance on preparatory artifacts | High | Moderate | Open - controlled |
| `RSK-2.6-004` | Qualified-review rework | High | Moderate | Open - controlled |
| `RSK-2.6-005` | Reviewer scope and cost expansion | Medium | Low to Moderate | Open - controlled |
| `RSK-2.6-006` | Stale or inconsistent cross-release dependencies | High | Low to Moderate | Open - controlled |
| `RSK-2.6-007` | Public-private information leakage | High | Low to Moderate | Open - controlled |
| `RSK-2.6-008` | Traceability fragmentation | Medium | Low | Open - controlled |
| `RSK-2.6-009` | Release 2.6 schedule dilution | High | Low to Moderate | Open - controlled |

## 3. Detailed Risk Records

### RSK-2.6-001

| Field | Value |
| --- | --- |
| Risk Statement | Existing carryforward: interim removable-media backup and lack of a durable offsite private backup. |
| Cause | Existing condition documented through FC-0003. |
| Impact | Loss, corruption, concentration, or delayed recovery of private evidence. |
| Inherent Severity | High |
| Owner | Founder and Managing Member |
| Preventive and Detective Controls | Maintain FileVault, owner-only permissions, encrypted controlled backup, checksum validation, recovery testing, capacity monitoring, and separate physical storage when practical. |
| Trigger or KRI | Backup error, restore error, checksum mismatch, media issue, private source approaching 10 GB, recurring live operations, or Release 2.6 closeout. |
| Required Response | Reopen G2, stop affected reliance, recover from validated evidence, and implement durable backup remediation. |
| Residual Severity | Low to Moderate |
| Status | Open - existing primary record remains FC-0003 |
| Review Cadence | Weekly during active work and after every material change or gate result |
| Related Change | `CC-2.6-001` / `DEC-0020` |

### RSK-2.6-002

| Field | Value |
| --- | --- |
| Risk Statement | Scope leakage creates a de facto second active numbered release. |
| Cause | Later-release preparation is mistaken for implementation. |
| Impact | Violation of DEC-0019 sequencing, fragmented authority, and unreliable closeout evidence. |
| Inherent Severity | High |
| Owner | Founder and Managing Member |
| Preventive and Detective Controls | Mandatory non-authoritative labeling, one-active-release checks, explicit exclusions, separate release plans, and no later-release approval language. |
| Trigger or KRI | Artifact status or language implies active, approved, implemented, completed, executable, or externally authorized later-release work. |
| Required Response | Stop the affected workstream, correct status and claims, perform no-loss review, and reapprove the change if scope materially changed. |
| Residual Severity | Low to Moderate |
| Status | Open - controlled |
| Review Cadence | Weekly during active work and after every material change or gate result |
| Related Change | `CC-2.6-001` / `DEC-0020` |

### RSK-2.6-003

| Field | Value |
| --- | --- |
| Risk Statement | Pre-release artifacts are relied upon as legally, financially, operationally, or commercially approved. |
| Cause | Preparation artifacts are mature enough to appear final. |
| Impact | Unsupported decisions, contract positions, pricing, or external commitments. |
| Inherent Severity | High |
| Owner | Founder and Managing Member |
| Preventive and Detective Controls | Status labels, reliance prohibitions, qualified-review fields, approval gates, version controls, and reviewer-evidence references. |
| Trigger or KRI | Any use in an external decision, negotiation, contract, invoice, pricing action, collection action, demonstration, or pilot. |
| Required Response | Withdraw the artifact from use, notify affected decision owners, obtain qualified review, and document corrective action. |
| Residual Severity | Moderate |
| Status | Open - controlled |
| Review Cadence | Weekly during active work and after every material change or gate result |
| Related Change | `CC-2.6-001` / `DEC-0020` |

### RSK-2.6-004

| Field | Value |
| --- | --- |
| Risk Statement | Unresolved professional-review questions cause material model or contract rework. |
| Cause | Legal, accounting, tax, insurance, or regulatory assumptions are embedded too early. |
| Impact | Duplicated effort, delayed release completion, and inconsistent artifacts. |
| Inherent Severity | High |
| Owner | Founder and Managing Member |
| Preventive and Detective Controls | Modular architecture, assumption register, provisional fields, decision brackets, reviewer question traceability, and fallback treatments. |
| Trigger or KRI | Reviewer rejects an assumption, identifies a missing requirement, or requires a different treatment. |
| Required Response | Isolate the affected module, preserve prior evidence, apply the approved delta, rerun tests, and reconcile dependent artifacts. |
| Residual Severity | Moderate |
| Status | Open - controlled |
| Review Cadence | Weekly during active work and after every material change or gate result |
| Related Change | `CC-2.6-001` / `DEC-0020` |

### RSK-2.6-005

| Field | Value |
| --- | --- |
| Risk Statement | Reviewer packages are overbroad and increase professional fees or turnaround time. |
| Cause | Too much repository context or poorly bounded questions are sent. |
| Impact | Higher charges, delayed responses, unnecessary privileged or confidential disclosure. |
| Inherent Severity | Medium |
| Owner | Founder and Managing Member |
| Preventive and Detective Controls | Common two-page context, discipline-specific modules, closed-ended questions, minimum-necessary excerpts, response template, capped scope, and secure delivery. |
| Trigger or KRI | Reviewer requests broad discovery, cannot quote a bounded fee, or identifies unclear scope. |
| Required Response | Narrow or split the package, remove irrelevant material, agree a fixed or capped fee, and defer optional advice. |
| Residual Severity | Low to Moderate |
| Status | Open - controlled |
| Review Cadence | Weekly during active work and after every material change or gate result |
| Related Change | `CC-2.6-001` / `DEC-0020` |

### RSK-2.6-006

| Field | Value |
| --- | --- |
| Risk Statement | Cross-release assumptions and dependencies become inconsistent or stale. |
| Cause | Multiple preparatory artifacts evolve at different rates. |
| Impact | Conflicting definitions, formulas, clause positions, tests, or evidence expectations. |
| Inherent Severity | High |
| Owner | Founder and Managing Member |
| Preventive and Detective Controls | Master requirements and assumptions registers, stable IDs, dependency mapping, version dates, source hierarchy, and reconciliation before promotion. |
| Trigger or KRI | Same term, assumption, requirement, or dependency has conflicting values or statuses across artifacts. |
| Required Response | Freeze dependent work, identify the authoritative source, reconcile all affected artifacts, and rerun traceability checks. |
| Residual Severity | Low to Moderate |
| Status | Open - controlled |
| Review Cadence | Weekly during active work and after every material change or gate result |
| Related Change | `CC-2.6-001` / `DEC-0020` |

### RSK-2.6-007

| Field | Value |
| --- | --- |
| Risk Statement | Public pull-forward preparation exposes confidential strategy, values, private paths, or live-party information. |
| Cause | Cross-release artifacts aggregate sensitive commercial and legal context. |
| Impact | Commercial harm, privacy breach, privilege loss, or public-private boundary failure. |
| Inherent Severity | High |
| Owner | Founder and Managing Member |
| Preventive and Detective Controls | Public-private classification, sanitized scenarios, prohibited-token scan, minimum-necessary public references, and controlled private evidence. |
| Trigger or KRI | Protected value, party, path, credential, signature, private formula, or privileged content appears in public Git or a public reviewer package. |
| Required Response | Stop staging and transmission, remove the content, assess exposure, preserve incident evidence, and reopen the information-boundary gate. |
| Residual Severity | Low to Moderate |
| Status | Open - controlled |
| Review Cadence | Weekly during active work and after every material change or gate result |
| Related Change | `CC-2.6-001` / `DEC-0020` |

### RSK-2.6-008

| Field | Value |
| --- | --- |
| Risk Statement | Decision, risk, requirement, and evidence traceability fragments across releases. |
| Cause | Preparation work is created without stable IDs or crosswalks. |
| Impact | Orphaned requirements, missed controls, duplicate work, and weak auditability. |
| Inherent Severity | Medium |
| Owner | Founder and Managing Member |
| Preventive and Detective Controls | CRW IDs, RSK IDs, source-to-control-to-artifact-to-test mapping, decision references, evidence identifiers, and release-specific promotion criteria. |
| Trigger or KRI | Artifact cannot identify its source, owner, status, dependency, review requirement, test, or downstream release. |
| Required Response | Withhold promotion, complete the crosswalk, merge duplicates, and record unresolved gaps as risks or conditions. |
| Residual Severity | Low |
| Status | Open - controlled |
| Review Cadence | Weekly during active work and after every material change or gate result |
| Related Change | `CC-2.6-001` / `DEC-0020` |

### RSK-2.6-009

| Field | Value |
| --- | --- |
| Risk Statement | Cross-release preparation dilutes focus and delays Release 2.6 critical-path completion. |
| Cause | Too many work packages are active simultaneously. |
| Impact | Delayed G3, reviewer outreach, substantive model population, and Release 2.6 closeout. |
| Inherent Severity | High |
| Owner | Founder and Managing Member |
| Preventive and Detective Controls | Release 2.6 priority rule, work-in-process limits, dependency-based sequencing, weekly status review, and pause authority. |
| Trigger or KRI | Release 2.6 critical milestone slips, CRW work exceeds available capacity, or unresolved work grows for two consecutive reviews. |
| Required Response | Pause CRW-0005 through CRW-0007, finish the Release 2.6 critical path, and rebaseline remaining preparation. |
| Residual Severity | Low to Moderate |
| Status | Open - controlled |
| Review Cadence | Weekly during active work and after every material change or gate result |
| Related Change | `CC-2.6-001` / `DEC-0020` |

## 4. Closure and Escalation

1. Open High risks are reviewed before each material promotion, reviewer
   transmission, release gate, and external-use decision.
2. A failed control requires immediate stop, evidence preservation, impact
   assessment, remediation, and retest.
3. New material risks receive the next unused `RSK-2.6-###` identifier.
4. Closed risks remain in the register with closure evidence and date.
5. Release 2.6 closeout shall reconcile every risk to Open, Accepted,
   Transferred, Deferred, or Closed with evidence.
