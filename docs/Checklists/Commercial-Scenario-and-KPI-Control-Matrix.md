# Commercial Scenario and KPI Control Matrix

## Document Control

| Field | Value |
| --- | --- |
| Document | Commercial Scenario and KPI Control Matrix |
| Document Type | Control Matrix |
| Control Area | Private Commercial Operations |
| Owner | Send Manna Too LLC |
| Approving Authority | Send Manna Too LLC governance authority |
| Status | Approved |
| Version | 1.0 |
| Release | Release 2.6 |
| Effective Date | 2026-07-16 |
| Review Cycle | At least annually and upon material change to commercial models, rate cards, scenarios, KPI formulas, data sources, assumptions, capacity, collections, exceptions, private authoritative sources, G2 or G3 status, qualified-review requirements, incidents, backup, recovery, or applicable obligations |
| Canonical Source | `docs/Checklists/Commercial-Scenario-and-KPI-Control-Matrix.md` |
| Canonical Format | Markdown in Git after controlled validation and approval |
| Public Repository Classification | Public unpopulated control matrix governed through B-09 mixed workflows |
| Private Evidence Classification | B-02 and B-06 private evidence; B-10 content is prohibited from public Git |
| Publication Formats | No production Word, PDF, or PowerPoint framework publication is authorized by this matrix |

## 1. Purpose

This matrix defines the public governance method for creating, validating, approving, using, reviewing, preserving, and superseding private commercial scenarios and commercial key performance indicators.

It supports:

1. `OW-0025` cost, effort, margin, contingency, and price-boundary modeling.
2. `OW-0026` pricing exceptions, strategic investment, nonprofit, and pro bono controls.
3. `OW-0027` invoicing, payment, expense, travel, remobilization, collection, and bad-debt controls.
4. `OW-0028` commercial scenarios and capacity-profitability KPIs.
5. `OW-0029` approval history, version control, preservation, backup, recovery, and supersession.

This matrix does not populate private values, approve actual scenarios or KPI results, establish G2 or G3 completion, authorize external activity, or establish legal, tax, accounting, insurance, regulatory, technical, market, effectiveness, scalability, security, or compliance conclusions.

## 2. Scope

This matrix applies to:

1. `PRV-COM-2.6-002` confidential internal rate card when used by scenarios or KPIs.
2. `PRV-COM-2.6-003` cost, effort, margin, contingency, and price-boundary model.
3. `PRV-COM-2.6-004` pricing-exception, strategic-investment, nonprofit, and pro bono register.
4. `PRV-COM-2.6-005` invoicing, payment, expense, travel, remobilization, collection, and bad-debt model.
5. `PRV-COM-2.6-006` commercial scenario, capacity, and KPI model.
6. `PRV-COM-2.6-007` commercial approval, version, and supersession history.
7. `PRV-COM-2.6-008` qualified-review status and advice record when triggered.
8. `PRV-COM-2.6-009` private backup and recovery validation record.
9. `PRV-COM-2.6-010` populated private commercial artifact inventory.

The public repository may contain this unpopulated matrix and sanitized conclusions only.

The populated scenario model, KPI values, thresholds, assumptions, and evidence remain private.

## 3. Explicit Exclusions

This matrix does not:

1. Replace the Pricing and Commercial Approval Standard.
2. Replace the Private Commercial Operations and Confidential Records Standard.
3. Replace the Private Commercial Artifact Inventory and Control Matrix.
4. Replace the Commercial Model Validation and Reconciliation Checklist.
5. Create actual rates, prices, margins, costs, reserves, capacity values, scenario outputs, KPI values, or thresholds.
6. Create a private repository.
7. Approve a private rate card or commercial model.
8. Authorize client, vendor, contract, invoice, collection, delivery, or pilot activity.
9. Create vendor referral, compensation, demonstration, or sales-closure governance.
10. Define tax, accounting, legal, insurance, or regulatory treatment.
11. Authorize records disposition.
12. Authorize production framework publication.
13. Represent a scenario as a proven forecast.
14. Represent a management KPI as a generally accepted accounting measure without applicable qualified review.

## 4. Governing Authority

This matrix is subordinate to and shall preserve:

1. The Send Manna Too LLC Constitution.
2. The Document Hierarchy Standard.
3. The Document Quality Standard.
4. The Governance and Operating Authority Policy.
5. The Commercial and Contracting Governance Policy.
6. The Information Handling and Confidentiality Policy.
7. The Records Evidence and Retention Policy.
8. The External Deliverable Governance Policy.
9. The Cross-Policy Exception, Escalation, Noncompliance, and Corrective-Action Procedure.
10. The Private Commercial Operations and Confidential Records Standard.
11. The Pricing and Commercial Approval Standard, Version 2.0.
12. The Private Commercial Artifact Inventory and Control Matrix.
13. The Commercial Model Validation and Reconciliation Checklist.
14. DEC-0017.
15. DEC-0018.
16. DEC-0019.
17. The Release 2.5 Public and Private Artifact Boundary.
18. The Release 2.5 Dependency and Sequencing Map.
19. The approved Release 2.6 plan.

The stricter applicable requirement controls.

## 5. Core Principles

Commercial scenarios and KPIs shall be:

1. Purpose specific.
2. Traceable to approved private sources.
3. Version controlled.
4. Explicit about assumptions.
5. Explicit about limitations.
6. Reproducible.
7. Independently recomputable when material.
8. Reconciled to approved models and records.
9. Conservative when evidence is weak.
10. Clear about qualified-review status.
11. Separated into public controls and private populated evidence.
12. Protected from public disclosure.
13. Reviewed for staleness.
14. Approved before reliance.
15. Restricted when G2 or applicable G3 requirements remain open.
16. Preserved and recoverable.
17. Superseded through controlled evidence.
18. Free from unsupported precision.
19. Free from implied guarantees.
20. Free from claims of predictive accuracy without evidence.

## 6. Controlled Status Values

Use only:

1. Proposed.
2. Draft.
3. Candidate.
4. Under review.
5. Qualified review pending.
6. Approved.
7. Active.
8. Suspended.
9. Superseded.
10. Closed.
11. Rejected.
12. Preserved.
13. Incident affected.

A state shall not be inferred from file existence, formula completion, visual appearance, or informal discussion.

## 7. Scenario Validation Result Values

Use only:

1. Not started.
2. In progress.
3. Pass.
4. Pass with conditions.
5. Fail.
6. Not applicable.
7. Revalidation required.
8. Suspended.

A scenario result shall identify the exact version and permitted use.

## 8. KPI Data-Quality Status Values

Use only:

1. Not assessed.
2. Insufficient.
3. Limited.
4. Acceptable with conditions.
5. Acceptable.
6. Revalidation required.
7. Suspended.

Data quality shall not be inferred from completeness alone.

## 9. Scenario Evidence Fields

Each private scenario record shall identify:

| Field | Required | Control Expectation |
| --- | --- | --- |
| Scenario identifier | Yes | Use a stable private evidence reference |
| Model evidence identifier | Yes | Link to `PRV-COM-2.6-003` or `PRV-COM-2.6-006` |
| Scenario name or category | Yes | Keep sensitive names private |
| Purpose | Yes | State the authorized decision use |
| Scenario owner | Yes | Identify accountability |
| Model version | Yes | Identify the exact model version |
| Rate-card version | Conditional | Required when rate inputs are used |
| Input-set version | Yes | Identify the exact input set |
| Assumption-set version | Yes | Identify the exact assumption set |
| Status | Yes | Use an approved status |
| Validation result | Yes | Use an approved result |
| G2 status | Yes | Use the approved gate status |
| G3 status | Yes | Use the approved gate status |
| Qualified-review status | Yes | Identify status and trigger |
| Effective date | Conditional | Required for approved or active scenarios |
| Review date | Yes | Identify staleness review |
| Approval date | Conditional | Required for approved or active scenarios |
| Approver | Conditional | Required for approved or active scenarios |
| Limitations | Yes | State material limits |
| Open conditions | Yes | State none or identify restrictions |
| Related exceptions | Conditional | Use evidence identifiers only |
| Backup status | Yes | Identify readiness |
| Recovery status | Yes | Identify representative recovery status |
| Preservation state | Yes | Identify preservation status |
| Supersession state | Yes | Identify current or superseded relationship |
| Residual risk | Yes | Identify accepted, open, remediating, or escalated risk |
| Public-summary status | Yes | Identify whether sanitized disclosure is authorized |

## 10. KPI Definition Fields

Each private KPI definition shall identify:

| Field | Required | Control Expectation |
| --- | --- | --- |
| KPI identifier | Yes | Use a stable private evidence reference |
| KPI name | Yes | Use an approved business name |
| Purpose | Yes | State the decision supported |
| Definition | Yes | State what is measured |
| Formula | Yes | Provide the complete private formula |
| Numerator | Conditional | Required for ratio metrics |
| Denominator | Conditional | Required for ratio metrics |
| Unit | Yes | Identify currency, percentage, count, time, or other unit |
| Direction | Yes | Identify whether higher, lower, or range is preferred |
| Source | Yes | Identify approved source categories |
| Data owner | Yes | Identify accountability |
| Review owner | Yes | Identify review accountability |
| Frequency | Yes | Identify calculation cadence |
| Period | Yes | Identify reporting period |
| Threshold or decision rule | Conditional | Required when approved; remains private |
| Exception method | Yes | Define exceptions |
| Qualified-review status | Yes | Identify review status |
| Data-quality requirement | Yes | Define minimum evidence quality |
| Missing-data treatment | Yes | Define behavior |
| Zero-denominator treatment | Conditional | Required for ratio metrics |
| Rounding method | Yes | Define rounding |
| Limitation | Yes | State material limitations |
| Preservation requirement | Yes | Identify preservation state |
| Public-summary treatment | Yes | Identify sanitized disclosure rule |
| Version | Yes | Identify exact definition version |
| Effective date | Conditional | Required for approved or active KPIs |
| Review date | Yes | Identify next review |
| Approver | Conditional | Required for approved or active KPIs |
| G2 status | Yes | Identify gate status |
| G3 status | Yes | Identify gate status |
| Backup status | Yes | Identify readiness |
| Recovery status | Yes | Identify representative recovery status |
| Residual risk | Yes | Identify risk status |

## 11. Required Scenario Set

The private model shall include, as applicable:

| Scenario | Purpose | Minimum Required Treatment |
| --- | --- | --- |
| Conservative | Assess lower-demand, higher-cost, higher-effort, or slower-collection conditions | Conservative evidence and assumptions; no concealed favorable input |
| Expected | Assess the most supportable current planning case | Best-supported inputs with explicit limitations |
| Favorable | Assess improved conditions without treating them as guaranteed | Clearly separated favorable assumptions and sensitivity |
| Capacity stress | Assess overcommitment, reduced availability, or increased non-delivery effort | Capacity units, periods, and displacement effect |
| Collection delay | Assess slower payment, disputes, or aging | Billing timing, collection lag, cash effect, and bad-debt assumptions |
| Scope expansion | Assess additional effort, review, deliverables, or dependencies | Scope version, effort, schedule, and change-pricing effect |
| Qualified-review cost | Assess legal, tax, accounting, insurance, or technical review burden | Trigger, cost source, timing, and restriction |
| Travel or remobilization | Assess travel, cancellation, restart, or disruption | Time, cost, schedule, and approval effects |
| Exception or strategic investment | Assess discounts, concessions, nonprofit, pro bono, or strategic capacity use | Exception linkage, capacity, margin, and precedent effect |
| Zero revenue or no engagement | Assess the absence of external revenue or approved engagement | Fixed obligations, preservation needs, and no unsupported operating assumption |

Each scenario remains private when populated.

## 12. Scenario Construction Controls

For each scenario, verify:

- [ ] Purpose is documented.
- [ ] Decision supported is documented.
- [ ] Model version is identified.
- [ ] Rate-card version is identified when applicable.
- [ ] Input-set version is identified.
- [ ] Assumption-set version is identified.
- [ ] Sources are identified.
- [ ] Units are identified.
- [ ] Periods are identified.
- [ ] Capacity assumption is identified.
- [ ] Collection assumption is identified.
- [ ] Cost assumption is identified.
- [ ] Effort assumption is identified.
- [ ] Contingency is identified.
- [ ] Exception linkage is identified.
- [ ] Qualified-review status is identified.
- [ ] Output set is identified.
- [ ] Sensitivities are identified.
- [ ] Limitations are identified.
- [ ] Owner review is documented.
- [ ] Approval status is documented.
- [ ] G2 status is documented.
- [ ] G3 status is documented.
- [ ] Backup status is documented.
- [ ] Recovery status is documented.
- [ ] Supersession status is documented.
- [ ] Public-summary status is documented.

## 13. Scenario Isolation Controls

Verify:

- [ ] Each scenario has a distinct identifier.
- [ ] Each scenario changes only intended variables.
- [ ] Shared inputs are version controlled.
- [ ] Scenario-specific assumptions are separated.
- [ ] Scenario-specific overrides are visible.
- [ ] Scenario changes do not alter the approved base model.
- [ ] Scenario outputs can be reproduced.
- [ ] Scenario outputs reconcile to the base model.
- [ ] Cross-scenario contamination is absent.
- [ ] Cached values are refreshed.
- [ ] Scenario labels are unambiguous.
- [ ] Favorable assumptions are not embedded in the expected case.
- [ ] Conservative assumptions are not selectively omitted.
- [ ] Scenario version history is preserved.
- [ ] Superseded scenarios are restricted from active use.

## 14. Scenario Sensitivity Controls

For each material scenario, assess:

- [ ] Effort sensitivity.
- [ ] Rate sensitivity.
- [ ] Direct-cost sensitivity.
- [ ] Travel-cost sensitivity.
- [ ] Remobilization sensitivity.
- [ ] Qualified-review-cost sensitivity.
- [ ] Contingency sensitivity.
- [ ] Capacity sensitivity.
- [ ] Collection-delay sensitivity.
- [ ] Scope-expansion sensitivity.
- [ ] Rework sensitivity.
- [ ] Exception sensitivity.
- [ ] Discount sensitivity.
- [ ] Bad-debt sensitivity.
- [ ] Timing sensitivity.
- [ ] Source-quality sensitivity.
- [ ] Assumption-staleness sensitivity.
- [ ] Recovery-dependency sensitivity.

Sensitivity results shall identify the affected output, direction, range, limitation, and decision effect.

## 15. Scenario Boundary and Adverse-Case Tests

Perform, as applicable:

- [ ] Zero-input test.
- [ ] Minimum-input test.
- [ ] Expected-input test.
- [ ] Maximum-input test.
- [ ] Negative-value test.
- [ ] Missing-input test.
- [ ] Duplicate-input test.
- [ ] Invalid-date test.
- [ ] Invalid-unit test.
- [ ] Extreme-capacity test.
- [ ] Delayed-collection test.
- [ ] High-rework test.
- [ ] High-qualified-review-cost test.
- [ ] Travel disruption test.
- [ ] Remobilization disruption test.
- [ ] Exception-expiration test.
- [ ] Stale-rate-card test.
- [ ] Superseded-model test.
- [ ] Recovery-restored-version test.
- [ ] Rounding-boundary test.

Verify that expected behavior is defined and actual behavior matches it.

## 16. Scenario Approval Controls

A scenario may be approved only when:

1. G2 has passed.
2. Applicable G3 requirements have been satisfied.
3. The authoritative private source is approved.
4. The model version is approved.
5. Inputs and assumptions are classified.
6. Formula and scenario validation pass.
7. The scenario reconciles to the base model.
8. Material limitations are documented.
9. Required qualified review is complete or an approved limited-purpose restriction applies.
10. Open findings are closed or subject to an approved restriction.
11. Backup and representative recovery pass.
12. Preservation and supersession controls are complete.
13. Residual risk is approved.

Scenario approval does not prove predictive accuracy or authorize external execution.

## 17. Required KPI Set

The private KPI model shall define, at minimum:

1. Available delivery capacity.
2. Committed capacity.
3. Capacity utilization.
4. Billable realization.
5. Contribution or management margin.
6. Estimate variance.
7. Billing timeliness.
8. Collection cycle.
9. Aging exposure.
10. Exception utilization.
11. Pro bono and strategic capacity use.
12. Revenue concentration.
13. Pipeline concentration when later authorized.
14. Bad-debt rate.
15. Model staleness.
16. Recovery readiness.

The required KPI set defines governance categories, not approved private formulas or thresholds.

## 18. KPI-01 Available Delivery Capacity

| Control | Requirement |
| --- | --- |
| Purpose | Identify delivery capacity available for authorized work during a defined period |
| Unit | Approved time or capacity unit |
| Required sources | Working-time basis, known non-delivery obligations, approved leave or unavailability, and other approved capacity constraints |
| Required controls | Period consistency, source dates, owner, review cadence, and limitation |
| Key risks | Overstatement, omitted administrative work, omitted travel, omitted qualified-review time |
| Required tests | Zero capacity, partial capacity, full capacity, period conversion, and source-staleness tests |
| Qualified-review status | Not generally an accounting measure; assess labor, tax, or other triggers when applicable |
| Public boundary | Formula categories may be public; actual capacity values and thresholds remain private |

## 19. KPI-02 Committed Capacity

| Control | Requirement |
| --- | --- |
| Purpose | Identify capacity committed to approved obligations |
| Unit | Same approved capacity unit and period as available capacity |
| Required sources | Approved engagements, approved internal commitments, approved pro bono or strategic commitments, and applicable non-delivery obligations |
| Required controls | Approval status, effective dates, commitment version, and supersession |
| Key risks | Treating pipeline as commitment, double counting, stale commitments |
| Required tests | Duplicate commitment, expired commitment, overlapping period, and superseded-record tests |
| Public boundary | Actual commitments and values remain private |

## 20. KPI-03 Capacity Utilization

| Control | Requirement |
| --- | --- |
| Purpose | Compare committed or used capacity to available delivery capacity |
| Formula category | Approved committed or used capacity divided by approved available delivery capacity |
| Numerator | Approved committed or used capacity |
| Denominator | Approved available delivery capacity |
| Required controls | Matching period, matching units, zero-denominator control, source reconciliation |
| Key risks | Overstated utilization, omitted non-delivery work, denominator manipulation |
| Required tests | Zero denominator, zero numerator, full utilization, over-capacity, and period mismatch |
| Public boundary | Actual values and thresholds remain private |

## 21. KPI-04 Billable Realization

| Control | Requirement |
| --- | --- |
| Purpose | Compare realized or approved billable value to an approved reference value |
| Formula category | Approved realized or billable value divided by an approved reference value |
| Required sources | Approved invoices, approved pricing records, or another qualified private source |
| Required controls | Definition of realized, billed, earned, and collected; period and status alignment |
| Key risks | Mixing billed, earned, and collected amounts; accounting mislabeling |
| Qualified-review status | Accounting or tax review may be required depending on use |
| Public boundary | Actual values, formulas, and thresholds remain private |

## 22. KPI-05 Contribution or Management Margin

| Control | Requirement |
| --- | --- |
| Purpose | Provide an internal management measure of commercial contribution |
| Formula category | Approved price or revenue basis less approved cost basis, expressed as an amount or ratio |
| Required sources | Approved pricing model, approved cost sources, and qualified-review status |
| Required controls | Cost scope, allocation treatment, period, rounding, and limitations |
| Key risks | Mislabeling as generally accepted accounting margin, omitted costs, unsupported allocations |
| Qualified-review status | Accounting and tax status shall be explicit |
| Public boundary | Actual formula details, values, and thresholds remain private |

## 23. KPI-06 Estimate Variance

| Control | Requirement |
| --- | --- |
| Purpose | Compare approved estimated effort or cost to actual or current evidence |
| Formula category | Difference or ratio between approved estimate and approved actual or current evidence |
| Required controls | Exact estimate version, actual-source authority, unit and period alignment |
| Key risks | Comparing incompatible versions, incomplete actual evidence, selective periods |
| Required tests | Zero variance, positive variance, negative variance, missing actual, and revised-estimate tests |
| Public boundary | Actual values and thresholds remain private |

## 24. KPI-07 Billing Timeliness

| Control | Requirement |
| --- | --- |
| Purpose | Measure elapsed time or compliance between an approved billing trigger and invoice issuance |
| Required sources | Approved billing trigger, milestone evidence, and invoice record |
| Required controls | Business-day or calendar-day method, timezone, status, and exception treatment |
| Key risks | Invalid trigger date, delayed source evidence, draft invoice treated as issued |
| Qualified-review status | Bookkeeping and invoicing administration status shall be explicit |
| Public boundary | Actual invoice dates, client identity, and values remain private |

## 25. KPI-08 Collection Cycle

| Control | Requirement |
| --- | --- |
| Purpose | Measure elapsed time between invoice issuance and approved payment or closure event |
| Required sources | Approved invoice and payment or closure records |
| Required controls | Partial payment, dispute, settlement, write-off, and reopen treatment |
| Key risks | Treating unpaid or disputed invoices as collected, excluding slow payments selectively |
| Qualified-review status | Bookkeeping, tax, and counsel triggers shall be assessed |
| Public boundary | Actual party, invoice, payment, and collection details remain private |

## 26. KPI-09 Aging Exposure

| Control | Requirement |
| --- | --- |
| Purpose | Identify approved receivable exposure by elapsed time or another approved aging basis |
| Required sources | Approved accounts-receivable and invoice records |
| Required controls | Aging date, bucket logic, dispute treatment, settlement, write-off, and bad-debt status |
| Key risks | Incorrect aging date, duplicate invoices, unsupported bucket treatment |
| Qualified-review status | Accounting, tax, and counsel status shall be explicit |
| Public boundary | Values, parties, buckets, and thresholds remain private |

## 27. KPI-10 Exception Utilization

| Control | Requirement |
| --- | --- |
| Purpose | Measure approved commercial exceptions relative to an approved population |
| Required sources | Approved exception register and applicable pricing or opportunity records |
| Required controls | Exception categories, denominator definition, expiration, and supersession |
| Key risks | Missing exceptions, inconsistent denominator, concealed repeated concessions |
| Required tests | Zero exceptions, expired exceptions, duplicate exceptions, and category reconciliation |
| Public boundary | Actual exception counts, rates, identities, and thresholds remain private |

## 28. KPI-11 Pro Bono and Strategic Capacity Use

| Control | Requirement |
| --- | --- |
| Purpose | Measure capacity used for approved pro bono, nonprofit, or strategic-investment work |
| Required sources | Approved exception or strategic-investment register and capacity model |
| Required controls | Category, approval, period, capacity unit, outcome, and closure |
| Key risks | Treating no-charge work as costless, hidden capacity displacement, missing approval |
| Public boundary | Actual capacity values, parties, and thresholds remain private |

## 29. KPI-12 Revenue Concentration

| Control | Requirement |
| --- | --- |
| Purpose | Identify dependence on an approved revenue or commercial-value population |
| Required sources | Approved private bookkeeping, invoice, or revenue evidence |
| Required controls | Population definition, period, party aggregation, and qualified-review status |
| Key risks | Incomplete population, incorrect party grouping, accounting misstatement |
| Qualified-review status | Accounting and tax status shall be explicit |
| Public boundary | Actual values, parties, percentages, and thresholds remain private |

## 30. KPI-13 Pipeline Concentration

| Control | Requirement |
| --- | --- |
| Purpose | Identify concentration in later-authorized pipeline or opportunity information |
| Activation boundary | Remains inactive until later release authority permits pipeline use |
| Required controls | Clear separation from approved commitments and realized activity |
| Key risks | Treating unapproved pipeline as revenue or commitment |
| Public boundary | Opportunity identities, values, probabilities, and thresholds remain private |
| Release boundary | Release 2.6 defines the KPI category only and does not authorize populated pipeline data |

## 31. KPI-14 Bad-Debt Rate

| Control | Requirement |
| --- | --- |
| Purpose | Measure approved bad-debt or write-off evidence relative to an approved population |
| Required sources | Approved bookkeeping, write-off, and accounts-receivable records |
| Required controls | Period, authority, settlement treatment, recovery, and qualified-review status |
| Key risks | Unauthorized write-off, tax misstatement, denominator inconsistency |
| Qualified-review status | Accounting and tax status shall be explicit |
| Public boundary | Actual values and thresholds remain private |

## 32. KPI-15 Model Staleness

| Control | Requirement |
| --- | --- |
| Purpose | Identify models, inputs, assumptions, or sources requiring review |
| Formula category | Approved elapsed time, event trigger, or status comparison |
| Required sources | Model inventory, review dates, source dates, and change events |
| Required controls | Staleness trigger, exception, review owner, and revalidation status |
| Key risks | Using outdated rates, assumptions, formulas, or qualified advice |
| Public boundary | Sensitive model details and thresholds remain private |

## 33. KPI-16 Recovery Readiness

| Control | Requirement |
| --- | --- |
| Purpose | Identify whether required private artifacts have current backup and representative recovery evidence |
| Required sources | `PRV-COM-2.6-009` backup and recovery validation record |
| Required controls | Artifact coverage, correct version, test date, result, limitations, and retest |
| Key risks | Treating backup existence as recoverability, stale recovery evidence |
| Required tests | Missing backup, failed restore, wrong version, incomplete restore, and restricted-access tests |
| Public boundary | Sensitive recovery details remain private |

## 34. KPI Formula Validation Controls

For each KPI, verify:

- [ ] KPI identifier is present.
- [ ] Name is present.
- [ ] Purpose is present.
- [ ] Definition is present.
- [ ] Formula is present privately.
- [ ] Numerator is present when applicable.
- [ ] Denominator is present when applicable.
- [ ] Unit is present.
- [ ] Direction is present.
- [ ] Sources are present.
- [ ] Data owner is present.
- [ ] Review owner is present.
- [ ] Frequency is present.
- [ ] Period is present.
- [ ] Threshold or decision rule is present when approved.
- [ ] Exception method is present.
- [ ] Qualified-review status is present.
- [ ] Data-quality requirement is present.
- [ ] Missing-data treatment is present.
- [ ] Zero-denominator treatment is present when applicable.
- [ ] Rounding method is present.
- [ ] Limitation is present.
- [ ] Preservation requirement is present.
- [ ] Public-summary treatment is present.
- [ ] Version is present.
- [ ] Approval is present when required.
- [ ] G2 status is present.
- [ ] G3 status is present.
- [ ] Backup status is present.
- [ ] Recovery status is present.
- [ ] Residual risk is present.

## 35. KPI Data-Quality Controls

Verify:

- [ ] Source is authoritative or explicitly classified otherwise.
- [ ] Source date is present.
- [ ] Effective date is present when applicable.
- [ ] Review date is present.
- [ ] Source version is present.
- [ ] Completeness is assessed.
- [ ] Accuracy is assessed.
- [ ] Timeliness is assessed.
- [ ] Consistency is assessed.
- [ ] Uniqueness is assessed.
- [ ] Validity is assessed.
- [ ] Reconciliation is complete.
- [ ] Missing data is identified.
- [ ] Duplicate data is identified.
- [ ] Unknown data is not silently defaulted.
- [ ] Manual adjustments are visible.
- [ ] Qualified-review status is present.
- [ ] Limitations are documented.
- [ ] Data-quality status is assigned.
- [ ] Residual risk is documented.

## 36. KPI Recalculation and Independent Recomputation

Verify:

- [ ] The KPI recalculates using current approved inputs.
- [ ] Recalculation errors are absent.
- [ ] Material formulas are independently recomputed.
- [ ] Recomputed inputs match approved sources.
- [ ] Recomputed units and periods match.
- [ ] Recomputed outputs match after documented rounding.
- [ ] Zero-denominator behavior operates as designed.
- [ ] Missing-data behavior operates as designed.
- [ ] Differences are identified.
- [ ] Differences are explained.
- [ ] Unexplained differences are absent.
- [ ] Recalculation evidence is preserved.
- [ ] Independent recomputation evidence is preserved.
- [ ] Owner review is not represented as independent assurance.

## 37. KPI Reconciliation Controls

Reconcile, as applicable:

- [ ] Source record to KPI input.
- [ ] Model version to KPI calculation.
- [ ] Rate-card version to KPI calculation.
- [ ] Scenario version to KPI calculation.
- [ ] Exception record to KPI calculation.
- [ ] Invoice or collection source to KPI calculation.
- [ ] Capacity source to KPI calculation.
- [ ] Approval record to active KPI version.
- [ ] Supersession history to current KPI version.
- [ ] Backup-restored version to approved version.
- [ ] Public summary to sanitized private status.

Required identifiers, versions, periods, units, fields, and approval states shall reconcile exactly.

## 38. KPI Threshold and Decision-Rule Controls

When a threshold or decision rule is approved, verify:

- [ ] Purpose is documented.
- [ ] Rationale is documented.
- [ ] Source is documented.
- [ ] Owner is documented.
- [ ] Approver is documented.
- [ ] Effective date is documented.
- [ ] Review date is documented.
- [ ] Direction is documented.
- [ ] Action is documented.
- [ ] Exception method is documented.
- [ ] Qualified-review status is documented.
- [ ] Sensitivity is assessed.
- [ ] False-positive risk is assessed.
- [ ] False-negative risk is assessed.
- [ ] Public disclosure is prohibited when commercially sensitive.
- [ ] Staleness trigger is documented.
- [ ] Supersession is controlled.
- [ ] Residual risk is documented.

A threshold shall not be inferred from an isolated model result.

## 39. G2 and G3 Boundary Controls

Before populated scenarios or KPIs are approved or relied upon:

- [ ] G2 has passed.
- [ ] Any G2 conditions are documented.
- [ ] Applicable G3 requirements are satisfied.
- [ ] Any limited-purpose G3 decision identifies exact scope.
- [ ] Remaining G3 restrictions are documented.
- [ ] No broad conclusion is inferred from limited-purpose review.
- [ ] Qualified-review triggers are assessed.
- [ ] Required qualified review is complete or use is restricted.
- [ ] Gate evidence is preserved privately.
- [ ] No public artifact is represented as gate evidence.

Public unpopulated structures may be approved while G2 or G3 remains open.

## 40. Backup and Recovery Controls

Verify:

- [ ] Backup method is approved.
- [ ] Backup scope includes models, scenarios, KPI definitions, and required dependencies.
- [ ] Backup owner is identified.
- [ ] Backup trigger or frequency is defined.
- [ ] Secondary encrypted copy or equivalent recovery capability exists.
- [ ] Backup access is restricted.
- [ ] Integrity evidence exists.
- [ ] Correct version can be identified.
- [ ] Representative recovery has been performed.
- [ ] Restored scenario and KPI records are readable.
- [ ] Restored records are complete.
- [ ] Formulas are preserved.
- [ ] Relationships are preserved.
- [ ] Restored inputs reconcile.
- [ ] Restored outputs reconcile.
- [ ] Access remains restricted.
- [ ] Recovery limitations are documented.
- [ ] Failed recovery tests are remediated and retested.
- [ ] Recovery evidence is preserved.
- [ ] Residual risk is approved.

Backup existence alone does not prove recoverability.

## 41. Preservation and Supersession Controls

Verify:

- [ ] Preservation state is documented.
- [ ] No-disposition boundary is applied.
- [ ] Approved scenario and KPI versions are preserved.
- [ ] Source and assumption evidence is preserved.
- [ ] Validation evidence is preserved.
- [ ] Approval evidence is preserved.
- [ ] Qualified-review evidence is preserved.
- [ ] Exception evidence is preserved.
- [ ] Backup and recovery evidence is preserved.
- [ ] Superseded versions are preserved.
- [ ] Active-use links point to the current approved version.
- [ ] Stale versions are restricted.
- [ ] Closure does not imply disposition.
- [ ] Disposition is not performed without authority.

## 42. Public Summary Controls

A public summary may state:

1. Evidence identifier.
2. Scenario or KPI category.
3. Sanitized status.
4. Validation-result category.
5. G2 status category.
6. G3 status category.
7. Qualified-review status category.
8. Data-quality status category.
9. Backup status category.
10. Recovery status category.
11. Whether an open condition exists.
12. Whether use is permitted or blocked.

A public summary shall not state:

1. Actual values.
2. Sensitive thresholds.
3. Private formulas.
4. Private paths.
5. Account details.
6. Party identities.
7. Substantive qualified advice.
8. Contract terms.
9. Signatures.
10. Credentials.
11. Recovery details.
12. Sensitive incident facts.
13. Information that permits reasonable reconstruction of protected substance.

## 43. Stop Conditions

Stop approval, reliance, or affected use when:

1. G2 has not passed.
2. Applicable G3 requirements are incomplete.
3. The private authoritative source is not identified.
4. The model, scenario, or KPI version is unclear.
5. A material source is missing.
6. An assumption is represented as evidence.
7. A material formula is undocumented.
8. A formula cannot be independently recomputed.
9. A scenario or KPI cannot reconcile.
10. A hidden or unauthorized override exists.
11. Units, periods, signs, or currencies are materially inconsistent.
12. A required qualified review is missing.
13. An exception lacks authority or evidence.
14. A stale version may be used.
15. Backup is missing.
16. Recovery fails.
17. A private value is proposed for public Git.
18. A material finding remains open without an approved restriction.
19. External activity is proposed without authority.
20. Release 2.7 or later work begins.
21. A stricter requirement conflicts with this matrix.

## 44. Fallbacks

| Condition | Required Fallback |
| --- | --- |
| G2 fails | Stop private population and reliance; repair or replace the private source and retest |
| G3 remains incomplete | Restrict affected population, approval, conclusion, and live use |
| Source evidence is weak | Use a labeled assumption or range and conservative scenario |
| Scenario fails | Correct the scenario logic and retest all dependent outputs |
| KPI fails | Correct the formula, source, or data-quality control and retest |
| Independent recomputation differs | Investigate, correct, reconcile, and retest |
| Qualified review is pending | Restrict the affected conclusion or use |
| Rate card or model is stale | Revalidate or replace before reliance |
| Backup fails | Repair backup and revalidate |
| Recovery fails | Repair recovery and repeat representative recovery |
| Public summary is unsafe | Aggregate, redact, restrict, delay, or keep private |
| Record state is unclear | Apply the more restrictive state |
| Material finding remains open | Defer approval or approve only a documented restricted use |
| Disposition authority is unclear | Preserve the record |
| Confidential exposure occurs | Contain, preserve evidence, remediate, and revalidate |

## 45. Validation Requirements

This matrix shall be validated for:

1. Alignment with the Release 2.6 plan.
2. Alignment with the Pricing and Commercial Approval Standard, Version 2.0.
3. Alignment with the Private Commercial Operations and Confidential Records Standard.
4. Alignment with the Private Commercial Artifact Inventory and Control Matrix.
5. Alignment with the Commercial Model Validation and Reconciliation Checklist.
6. Coverage of required scenarios.
7. Coverage of all sixteen required KPI categories.
8. G2 and G3 treatment.
9. Scenario fields and controls.
10. KPI definition fields and controls.
11. Source and assumption controls.
12. Formula controls.
13. Sensitivity and adverse-case controls.
14. Data-quality controls.
15. Recalculation and independent recomputation.
16. Reconciliation.
17. Threshold and decision-rule controls.
18. Backup and recovery.
19. Preservation and supersession.
20. Public-summary controls.
21. Stop conditions.
22. Fallbacks.
23. No confidential values.
24. No live-party information.
25. No credentials or recovery material.
26. No private paths or sensitive configuration.
27. No unsupported qualified conclusion.
28. No Release 2.7 implementation.
29. No records-disposition authority.
30. ASCII.
31. Final newline.
32. Trailing whitespace.
33. Tab characters.
34. Unresolved markers.
35. Markdown headings and tables.
36. Exact changed path.
37. Checksum.
38. `git diff --check`.
39. Synchronization and clean working tree.

## 46. Acceptance Criteria

This matrix may be approved only when:

1. It is an unpopulated public control.
2. Populated scenarios, formulas, KPI values, and thresholds remain private.
3. The required scenario set is complete.
4. All sixteen KPI categories are defined.
5. Scenario and KPI fields are complete.
6. G2 and G3 treatment is correct.
7. Source, assumption, formula, sensitivity, data-quality, recalculation, and reconciliation controls are complete.
8. Backup, recovery, preservation, and supersession controls are complete.
9. Public-summary controls prevent disclosure.
10. No actual confidential value appears.
11. No live-party information appears.
12. No credential, recovery detail, privileged advice, private path, or sensitive configuration appears.
13. No external activity is authorized.
14. No Release 2.7 implementation is authorized.
15. No retention period or disposition authority is created.
16. Validation and repository controls pass.
17. Governance authority approves the matrix.

## 47. Approval Boundary

Approval of this matrix approves:

1. The public unpopulated scenario governance method.
2. The public unpopulated KPI governance categories.
3. The required scenario and KPI control fields.
4. The scenario validation, sensitivity, and approval method.
5. The KPI definition, data-quality, formula, recalculation, reconciliation, and threshold-control method.
6. The G2 and G3 boundary method.
7. The backup, recovery, preservation, supersession, stop, fallback, and public-summary controls.

Approval does not:

1. Approve a private repository.
2. Establish G2 completion.
3. Establish G3 completion.
4. Create, populate, approve, or validate an actual private scenario or KPI record.
5. Approve actual rates, prices, margins, costs, thresholds, scenarios, KPI values, forecasts, or accounting measures.
6. Approve a client, vendor, contract, invoice, collection action, delivery, or pilot.
7. Authorize Release 2.7 implementation.
8. Authorize records disposition.
9. Authorize production framework publication.
10. Establish legal, tax, accounting, insurance, regulatory, technical, market, effectiveness, scalability, security, or compliance conclusions.

This approved matrix becomes active only after controlled validation, commit, synchronization, and confirmation against a clean repository baseline.
