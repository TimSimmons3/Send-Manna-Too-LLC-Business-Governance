# Release 2.6 Cross-Release Readiness Pull-Forward Change Control

## Document Control

| Field | Value |
| --- | --- |
| Organization | Send Manna Too LLC |
| Framework | Business Governance Framework |
| Change Control | `CC-2.6-001` |
| Decision | `DEC-0020` |
| Status | Approved |
| Effective Date | 2026-07-18 |
| Owner and Approver | Founder and Managing Member |
| Active Numbered Release | Release 2.6 |
| Change Type | Controlled scope and sequencing clarification |
| Canonical Format | Markdown in Git |
| Public Classification | Public governance record; no confidential commercial values or private evidence |
| Next Release-Closeout Decision | Expected `DEC-0021` only if that identifier remains unused |

## 1. Purpose

Authorize a bounded Cross-Release Readiness Pull-Forward Workstream during
Release 2.6 so Send Manna Too LLC can complete the maximum defensible planning,
architecture, requirements, evidence design, test design, and reviewer-package
preparation without opening another numbered release or creating unsupported
claims.

## 2. Change Description

The approved roadmap sequence remains unchanged:

`Release 2.6 -> Release 2.7 -> Release 2.8 -> Release 2.9 -> Release 2.10`

Releases 3.0 and 3.1 remain non-concurrent conditional sibling branches.
Releases 3.2 and 3.3 remain evidence-triggered.

This change authorizes pre-release preparation that reduces later rework and
professional-review cost. It does not authorize later-release implementation,
approval, closeout, external execution, or reliance.

## 3. Authorized Work Packages

| ID | Work Package | Authorized Output |
| --- | --- | --- |
| `CRW-0001` | Common company and authority brief | Entity, authority, signature, service-scope, information-boundary, and insurance-fact structure |
| `CRW-0002` | Master business-requirements and assumptions register | Cross-release requirements, assumptions, evidence, dependencies, fallbacks, and rework impacts |
| `CRW-0003` | Master qualified-review and reviewer-package workstream | Consolidated questions, common reviewer core, release-specific modules, response format, and scope controls |
| `CRW-0004` | Release 2.6 pre-review model development | Architecture, fields, formulas, controls, test cases, assumptions, provisional management inputs, and reviewer-ready Candidates |
| `CRW-0005` | Releases 2.7 through 2.10 preparation | Requirements, taxonomies, schemas, fictional scenarios, traceability, acceptance criteria, and test designs |
| `CRW-0006` | Releases 3.0 through 3.3 preparation | Eligibility, start-gate, evidence, KPI, stop-condition, remediation, and service-qualification templates |
| `CRW-0007` | Integrated traceability and red-team review | Cross-release source-to-control-to-artifact-to-test mapping, objection handling, misuse review, and remediation tracking |

## 4. Mandatory Status Boundary

Every pull-forward artifact shall be labeled:

`Pre-release preparation - non-authoritative`

A pull-forward artifact shall not be represented as:

1. An opened or active later release.
2. An approved later-release deliverable.
3. Counsel-reviewed, legally approved, final, enforceable, or executable.
4. Professionally reviewed unless exact qualified evidence exists.
5. Evidence of operating effectiveness, compliance, profitability, market
   acceptance, or scalability.
6. Authorization for a client, vendor, contract, price, invoice, demonstration,
   commission, collection action, pilot, service expansion, or external reliance.

## 5. Scope Boundaries

The workstream shall:

1. Preserve one active numbered release: Release 2.6.
2. Preserve one principal Release 2.6 control domain.
3. Preserve the approved roadmap and dependency order.
4. Keep later-release work preparatory, reversible, and non-authoritative.
5. Keep protected values and evidence outside public Git.
6. Use fictional or sanitized scenarios for public validation.
7. Distinguish management metrics from accounting measures.
8. Keep legal, tax, accounting, insurance, regulatory, and other qualified
   conclusions pending applicable review.
9. Stop affected work when an authority, information, dependency, review, or
   evidence gate fails.
10. Preserve source, version, owner, status, assumption, dependency, review,
    fallback, and residual-risk traceability.

The workstream shall not:

1. Open Release 2.7 or any later numbered release.
2. Modify a later-release approved baseline because none is active.
3. Execute or approve contracts.
4. Select, contact, or engage a vendor or client through later-release authority.
5. Conduct a live demonstration or pilot.
6. Approve actual vendor compensation or attribution.
7. Approve external pricing, invoicing, collection, or delivery.
8. Publish confidential commercial values, private formulas, live-party
   information, private paths, credentials, signatures, or privileged advice.
9. Circumvent Release 2.6 G3 or professional-review restrictions.
10. Treat preparation as release completion.

## 6. Change-Control Effects

1. `DEC-0020` is consumed by this material change.
2. The expected Release 2.6 closeout decision becomes `DEC-0021`, subject to
   identifier reconfirmation immediately before implementation.
3. The Release 2.6 plan remains authoritative except as expressly supplemented
   by this change control.
4. This record authorizes the two new Release 2.6 public paths created with it.
5. The Release 2.5 roadmap, carryforward register, public-private boundary, and
   DEC-0019 remain controlling.
6. No Future Considerations update is required because this is controlled work,
   not an optional deferred idea.
7. No private artifact is approved or altered by this public change control.

## 7. Change Acceptance Criteria

The change is effective only when:

1. This record exists exactly once.
2. `DEC-0020` exists exactly once in `DECISIONS-LOG.md`.
3. The risk register contains unique `RSK-2.6-001` through `RSK-2.6-009`
   identifiers.
4. The changelog records the change.
5. All files are ASCII, have one final newline, and contain no trailing
   whitespace or protected path.
6. The repository diff contains only the five authorized paths.
7. The independent change-control gate passes.
8. The changes are separately reviewed, committed, synchronized, and confirmed
   clean before relying on this authority.

## 8. Point-Counterpoint and Fallback

| Objection | Counterpoint | Control | Fallback | Residual Risk |
| --- | --- | --- | --- | --- |
| Pull-forward work creates a second active release | Preparation is not release implementation | Mandatory non-authoritative label, one-active-release gate, and scope checks | Suspend CRW work and continue Release 2.6 only | Future readers may still overstate readiness |
| Early design may cause rework | Mature preparation reduces discovery and reviewer cost | Assumption registers, provisional labels, modular architecture, and review deltas | Revert affected module to the last validated baseline | Qualified reviewers may require material redesign |
| Cross-release work may delay Release 2.6 | Parallel preparation can dilute focus | Release 2.6 critical path retains priority and work-in-process limits apply | Pause CRW-0005 through CRW-0007 | Calendar delay remains possible |
| Public preparation may expose sensitive strategy | Public traceability can exist without values | Public-private boundary, sanitized examples, and confidentiality scan | Move affected content to controlled private evidence | Inference risk cannot be eliminated |
| Reviewer packages may become too broad | Consolidation should reduce repeated discovery | Narrow questions, minimum-necessary excerpts, capped scope, and issue registers | Split packages by discipline and decision | Reviewers may still request additional context |

## 9. Risks and Monitoring

The authoritative risk-tracking record for this change is:

`docs/Releases/Release-2.6-Cross-Release-Readiness-Risk-Register.md`

`RSK-2.6-001` remains an existing carryforward risk linked to `FC-0003`.
New risks `RSK-2.6-002` through `RSK-2.6-009` are created by or materially
affected by this change.

## 10. Approval

The Founder and Managing Member approves this controlled change on
2026-07-18.

Approval authorizes the bounded work packages in Section 3 subject to every
boundary, risk control, stop condition, and later release gate in this record.

Approval does not authorize future-release implementation or external activity.
