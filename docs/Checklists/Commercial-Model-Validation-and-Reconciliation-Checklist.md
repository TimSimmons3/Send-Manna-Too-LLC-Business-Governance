# Commercial Model Validation and Reconciliation Checklist

## Document Control

| Field | Value |
| --- | --- |
| Document | Commercial Model Validation and Reconciliation Checklist |
| Document Type | Checklist |
| Control Area | Private Commercial Operations |
| Owner | Send Manna Too LLC |
| Approving Authority | Send Manna Too LLC governance authority |
| Status | Approved |
| Version | 1.0 |
| Release | Release 2.6 |
| Effective Date | 2026-07-16 |
| Review Cycle | At least annually and upon material change to commercial models, rate cards, formulas, sources, assumptions, scenarios, KPIs, private authoritative sources, G2 or G3 status, qualified-review requirements, incidents, backup, recovery, or applicable obligations |
| Canonical Source | `docs/Checklists/Commercial-Model-Validation-and-Reconciliation-Checklist.md` |
| Canonical Format | Markdown in Git after controlled validation and approval |
| Public Repository Classification | Public unpopulated validation checklist governed through B-09 mixed workflows |
| Private Evidence Classification | B-02 and B-06 private evidence; B-10 content is prohibited from public Git |
| Publication Formats | No production Word, PDF, or PowerPoint framework publication is authorized by this checklist |

## 1. Purpose

This checklist defines the minimum validation, reconciliation, evidence, approval, and stop-condition requirements for private commercial models used by Send Manna Too LLC.

It governs validation of:

1. Confidential rate-card linkage.
2. Cost and effort inputs.
3. Margin and price-boundary calculations.
4. Complexity, risk, timing, travel, expense, remobilization, and contingency treatment.
5. Capacity and opportunity-cost treatment.
6. Pricing exceptions and strategic-investment decisions.
7. Invoicing, collection, settlement, write-off, and bad-debt assumptions.
8. Commercial scenarios.
9. Capacity and commercial KPIs.
10. Model versions, formulas, overrides, reconciliations, approvals, backup, recovery, preservation, and supersession.

This checklist does not create or populate a private model, establish G2 or G3 completion, approve actual commercial values, authorize external activity, or establish legal, tax, accounting, insurance, regulatory, technical, market, effectiveness, scalability, or compliance conclusions.

## 2. Scope

This checklist applies to:

1. `PRV-COM-2.6-002` confidential internal rate card when used as a model input.
2. `PRV-COM-2.6-003` cost, effort, margin, contingency, and price-boundary model.
3. `PRV-COM-2.6-004` pricing-exception, strategic-investment, nonprofit, and pro bono register when linked to a model.
4. `PRV-COM-2.6-005` invoicing, payment, expense, travel, remobilization, collection, and bad-debt model.
5. `PRV-COM-2.6-006` commercial scenario, capacity, and KPI model.
6. `PRV-COM-2.6-007` commercial approval, version, and supersession history.
7. `PRV-COM-2.6-008` qualified-review status and advice record when triggered.
8. `PRV-COM-2.6-009` private backup and recovery validation record.
9. `PRV-COM-2.6-010` populated private commercial artifact inventory.

This checklist may be approved and maintained publicly while G2 or G3 remains open.

It shall not be used to represent a populated private model as approved, reliable, recoverable, or ready for live use until all applicable gates and validation criteria pass.

## 3. Explicit Exclusions

This checklist does not:

1. Replace the Pricing and Commercial Approval Standard.
2. Replace the Private Commercial Operations and Confidential Records Standard.
3. Replace the Private Commercial Artifact Inventory and Control Matrix.
4. Create actual rates, prices, margins, costs, reserves, thresholds, scenarios, or KPI values.
5. Create a private repository.
6. Approve a rate card or commercial model.
7. Approve a client, vendor, contract, invoice, collection action, delivery, or pilot.
8. Create vendor referral, compensation, demonstration, or sales-closure controls.
9. Define legal remedies, tax treatment, accounting treatment, insurance coverage, or regulatory conclusions.
10. Authorize records disposition.
11. Authorize production framework publication.
12. Establish that a model is market validated, profitable, predictive, effective, scalable, secure, or compliant.

## 4. Governing Authority

This checklist is subordinate to and shall preserve:

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
13. DEC-0017.
14. DEC-0018.
15. DEC-0019.
16. The Release 2.5 Public and Private Artifact Boundary.
17. The Release 2.5 Dependency and Sequencing Map.
18. The approved Release 2.6 plan.

The stricter applicable requirement controls.

## 5. Use Instructions

For each validation:

1. Identify the model, version, purpose, owner, and evidence identifier.
2. Confirm G2 and applicable G3 status.
3. Confirm the private authoritative source.
4. Use only approved private evidence.
5. Complete every applicable checklist item.
6. Mark each item with an approved result.
7. Record evidence identifiers instead of sensitive private paths.
8. Record exceptions, failures, remediation, retesting, and residual risk.
9. Preserve the completed private validation record.
10. Publish only sanitized conclusions approved for disclosure.
11. Do not expose private values in public Git, screenshots, commit messages, issues, or validation output.
12. Do not approve or rely upon a model with an unresolved material failure.

## 6. Validation Result Values

Use only:

1. Not started.
2. In progress.
3. Pass.
4. Pass with conditions.
5. Fail.
6. Not applicable.
7. Revalidation required.
8. Suspended.

A result shall not be inferred from file existence, formula completion, visual appearance, or informal review.

## 7. Finding Severity Values

Use:

1. Critical.
2. High.
3. Moderate.
4. Low.
5. Observation.

Severity shall consider:

1. Financial effect.
2. Commercial decision effect.
3. Client or counterparty effect.
4. Formula propagation.
5. Scope of affected outputs.
6. Legal, tax, accounting, insurance, or regulatory dependency.
7. Confidentiality effect.
8. Recovery effect.
9. Likelihood of recurrence.
10. Detectability.

A severity label shall not replace documented rationale.

## 8. Model Validation Record Fields

The private validation record shall identify:

| Field | Required | Control Expectation |
| --- | --- | --- |
| Validation identifier | Yes | Use a stable private evidence reference |
| Model evidence identifier | Yes | Identify the applicable `PRV-COM` family |
| Model name or category | Yes | Keep sensitive names private |
| Business purpose | Yes | State the authorized use |
| Model owner | Yes | Identify accountability |
| Validator | Yes | Identify the person or qualified role |
| Validation date | Yes | Record the execution date |
| Model version | Yes | Identify the exact tested version |
| Rate-card version | Conditional | Required when a rate card is used |
| Scenario version | Conditional | Required when scenarios are tested |
| KPI version | Conditional | Required when KPI logic is tested |
| G2 status | Yes | Use the approved gate status |
| G3 status | Yes | Use the approved gate status |
| Qualified-review status | Yes | Identify status and trigger |
| Authoritative source category | Yes | Do not expose a sensitive path |
| Validation scope | Yes | Identify included and excluded components |
| Result | Yes | Use an approved validation result |
| Open conditions | Yes | State none or identify restrictions |
| Findings | Yes | State none or reference findings |
| Corrective-action status | Yes | State none, open, remediating, or closed |
| Retest status | Yes | State not required, pending, passed, or failed |
| Approval | Conditional | Required for final validation acceptance |
| Backup status | Yes | Identify backup readiness |
| Recovery status | Yes | Identify representative recovery status |
| Preservation state | Yes | Identify preservation status |
| Residual risk | Yes | Identify accepted, open, remediating, or escalated risk |
| Public-summary status | Yes | Identify whether a sanitized summary is authorized |

## 9. Pre-Validation Gate

Before model validation begins, verify:

- [ ] The model purpose is documented.
- [ ] The model owner is identified.
- [ ] The model version is identified.
- [ ] The authoritative private source category is identified.
- [ ] The applicable `PRV-COM` evidence identifier is identified.
- [ ] The validation scope is defined.
- [ ] The intended decision or use is defined.
- [ ] Applicable exclusions are defined.
- [ ] G2 status is identified.
- [ ] G3 status is identified.
- [ ] Qualified-review triggers are assessed.
- [ ] Required qualified review is requested or complete.
- [ ] The validator has authorized access.
- [ ] The validation does not require public disclosure of private values.
- [ ] A prior approved version is identified when version comparison applies.
- [ ] Required source records are available.
- [ ] Required backup and recovery evidence is available or the limitation is recorded.
- [ ] No stop condition already blocks validation or reliance.

Failure of the pre-validation gate blocks final approval.

## 10. G2 and G3 Boundary Review

Verify:

- [ ] G2 has passed before private population, approval, or reliance.
- [ ] Any G2 conditions are documented.
- [ ] Applicable G3 requirements are satisfied before private artifact approval.
- [ ] Any limited-purpose G3 result identifies the exact covered decision.
- [ ] Remaining G3 restrictions are documented.
- [ ] No broad G3 conclusion is inferred from limited-purpose review.
- [ ] No public control artifact is represented as private gate evidence.
- [ ] No model is used for live external activity while a blocking gate remains open.
- [ ] Any gate suspension or revalidation requirement is reflected in model status.
- [ ] Gate evidence is preserved privately.

Public unpopulated structures may be reviewed while either gate remains open.

## 11. Model Identity and Version Review

Verify:

- [ ] Model evidence identifier is present.
- [ ] Model purpose is present.
- [ ] Model version is present.
- [ ] Model status is present.
- [ ] Effective date is present when applicable.
- [ ] Approval date is present when applicable.
- [ ] Owner is identified.
- [ ] Validator is identified.
- [ ] Related rate-card version is identified.
- [ ] Related scenario version is identified.
- [ ] Related exception register version is identified.
- [ ] Related invoicing or collection model version is identified.
- [ ] Related public controls are identified.
- [ ] Superseded version is identified.
- [ ] Superseding version is identified when applicable.
- [ ] Change summary is present.
- [ ] Stale versions are restricted from active use.
- [ ] The tested version matches the version presented for approval.

## 12. Source and Input Inventory

Verify that every material input is inventoried with:

- [ ] Input name.
- [ ] Input description.
- [ ] Source class.
- [ ] Source owner.
- [ ] Source date.
- [ ] Effective date.
- [ ] Review date.
- [ ] Version.
- [ ] Unit.
- [ ] Period.
- [ ] Reliability.
- [ ] Relevance.
- [ ] Limitation.
- [ ] Qualified-review status.
- [ ] Approval status.
- [ ] Model use.
- [ ] Staleness trigger.
- [ ] Supersession reference.
- [ ] Evidence identifier.
- [ ] Confidentiality classification.

Verify:

- [ ] No material input is omitted.
- [ ] No input is represented more than once without purpose.
- [ ] Duplicate inputs are detected.
- [ ] Missing inputs are identified.
- [ ] Unknown inputs are restricted, escalated, conservatively modeled, or excluded.
- [ ] Input dates and periods align with the model purpose.
- [ ] Source records are authoritative or explicitly labeled otherwise.

## 13. Source Classification Review

Classify each material input as:

- [ ] Authoritative internal evidence.
- [ ] Qualified professional input.
- [ ] Contractual or legal input.
- [ ] Insurance input.
- [ ] Market or benchmark input.
- [ ] Vendor or third-party source.
- [ ] Owner assumption.
- [ ] Fictional test input.
- [ ] Derived value.
- [ ] Unknown or unresolved input.

Verify:

- [ ] The source class is accurate.
- [ ] An assumption is not represented as evidence.
- [ ] A benchmark is not represented as firm-specific evidence without applicability analysis.
- [ ] Qualified advice is not represented as broader than its scope.
- [ ] Fictional inputs are not represented as live evidence.
- [ ] Derived values identify their source formulas.
- [ ] Unknown inputs are not silently defaulted.
- [ ] Unsupported precision is absent.

## 14. Assumption Review

For each material assumption, verify:

- [ ] Assumption identifier is present.
- [ ] Description is present.
- [ ] Rationale is present.
- [ ] Owner is identified.
- [ ] Source or absence of source is identified.
- [ ] Effective date is present.
- [ ] Review date is present.
- [ ] Range or boundary is documented when applicable.
- [ ] Sensitivity is assessed.
- [ ] Affected outputs are identified.
- [ ] Qualified-review need is assessed.
- [ ] Approval is documented.
- [ ] Staleness trigger is documented.
- [ ] Replacement evidence is identified when expected.
- [ ] Limitation is disclosed.
- [ ] Residual risk is documented.

A material assumption shall not be hidden in a formula, comment, format, or default value.

## 15. Formula Inventory

For every material formula, verify:

- [ ] Formula identifier is present.
- [ ] Formula purpose is documented.
- [ ] Inputs are identified.
- [ ] Output is identified.
- [ ] Unit is identified.
- [ ] Period is identified.
- [ ] Sign convention is documented.
- [ ] Direction of effect is documented.
- [ ] Rounding method is documented.
- [ ] Boundary behavior is documented.
- [ ] Error handling is documented.
- [ ] Manual override capability is identified.
- [ ] Approval status is documented.
- [ ] Independent recomputation method is defined.
- [ ] Related source records are identified.
- [ ] Related scenario or KPI logic is identified.
- [ ] Version history is preserved.

Verify that the approved pricing formulas remain:

- [ ] `Base effort value = approved estimated hours x approved confidential rate`
- [ ] `Proposed fee = base effort value + approved complexity, risk, timing, expense, and contingency adjustments`

Any alternate final price requires documented rationale, effect, risk, capacity effect, collection effect, and approval.

## 16. Workbook, File, or System Structure Review

When applicable, verify:

- [ ] Expected files, workbooks, sheets, tables, modules, or records are present.
- [ ] Unexpected files, sheets, tables, modules, or records are absent or explained.
- [ ] Hidden sheets are reviewed.
- [ ] Hidden rows and columns are reviewed.
- [ ] Hidden cells or objects are reviewed.
- [ ] Comments and notes are reviewed.
- [ ] Named ranges are reviewed.
- [ ] External links are reviewed.
- [ ] Data connections are reviewed.
- [ ] Macros or scripts are reviewed when present.
- [ ] Protected cells or controlled-change methods are reviewed.
- [ ] Formula cells are distinguished from input cells.
- [ ] Input cells are distinguished from outputs.
- [ ] Stale cached values are not relied upon.
- [ ] Unsupported functions or platform dependencies are identified.
- [ ] Metadata is reviewed.
- [ ] Sensitive content is not exposed through hidden or embedded content.
- [ ] Structure supports backup and recovery.

## 17. Unit, Currency, Date, and Period Review

Verify:

- [ ] Currency is identified.
- [ ] Currency is consistent or conversion is documented.
- [ ] Units are identified.
- [ ] Units are consistent.
- [ ] Hours, days, weeks, months, or years are not mixed without conversion.
- [ ] Percentage and decimal representations are consistent.
- [ ] Dates are valid.
- [ ] Date formats are unambiguous.
- [ ] Start and end dates are logical.
- [ ] Periods align across inputs and outputs.
- [ ] Annual, monthly, weekly, and per-engagement values are distinguished.
- [ ] Prorating is documented.
- [ ] Tax periods are not inferred without qualified input.
- [ ] Rounding does not create a material unexplained difference.
- [ ] Sign conventions are consistent.
- [ ] Negative values are intentional and documented.

## 18. Scope and Effort Traceability

Verify that model effort traces to:

- [ ] Service.
- [ ] Scope version.
- [ ] Deliverables.
- [ ] Delivery phases.
- [ ] Qualification and planning.
- [ ] Commercial and contract review.
- [ ] Initiation.
- [ ] Interviews.
- [ ] Information review.
- [ ] Analysis.
- [ ] Drafting.
- [ ] Quality review.
- [ ] Client review support.
- [ ] Finalization.
- [ ] Publication and release validation.
- [ ] Delivery.
- [ ] Acceptance and closeout.
- [ ] Administration.
- [ ] Reasonable rework.
- [ ] Contingency.
- [ ] Travel time.
- [ ] Travel administration.
- [ ] Remobilization.
- [ ] Qualified-review coordination.
- [ ] Billing and collection administration.
- [ ] Private record administration.
- [ ] Capacity reservation.
- [ ] Strategic-investment, nonprofit, or pro bono capacity use.
- [ ] Recovery or evidence-restoration effort when applicable.

Verify:

- [ ] Less-visible governance and administration effort is not omitted.
- [ ] Estimate sources and reliability are documented.
- [ ] Actual-versus-estimate evidence is linked when available.
- [ ] Scope exclusions are reflected in the model.
- [ ] Out-of-scope effort is not silently included.

## 19. Rate-Card Linkage Review

Verify:

- [ ] Rate-card evidence identifier is present.
- [ ] Rate-card version is present.
- [ ] Rate-card status is approved and active for the intended use.
- [ ] Effective date is valid.
- [ ] Review date has not expired.
- [ ] Service or role mapping is correct.
- [ ] Pricing basis mapping is correct.
- [ ] Standard rate linkage is correct.
- [ ] Minimum approved rate or price-boundary linkage is correct.
- [ ] Fixed-fee assumptions are reflected.
- [ ] Complexity and risk treatment is reflected.
- [ ] Rush treatment is reflected.
- [ ] Travel treatment is reflected.
- [ ] Discount authority is reflected.
- [ ] Exception treatment is reflected.
- [ ] Source quality and staleness are acceptable.
- [ ] G2 and applicable G3 status permit reliance.
- [ ] Superseded rate-card versions are not used.

Actual rate values remain private.

## 20. Cost and Expense Input Review

Verify, as applicable:

- [ ] Direct effort value is supported.
- [ ] Pass-through costs are supported.
- [ ] Travel costs are supported.
- [ ] Remobilization costs are supported.
- [ ] Platform or tool costs are supported.
- [ ] Approved allocated operating costs are supported.
- [ ] Qualified-review costs are supported.
- [ ] Expense eligibility is defined.
- [ ] Expense preapproval requirements are reflected.
- [ ] Receipt or source evidence exists.
- [ ] Costs are not double counted.
- [ ] Fixed and variable costs are distinguished when relevant.
- [ ] Sunk costs are not treated as incremental without rationale.
- [ ] Owner assumptions are labeled.
- [ ] Accounting treatment is not inferred without qualified review.
- [ ] Tax treatment is not inferred without qualified review.

## 21. Complexity, Risk, and Contingency Review

Verify that applicable factors are assessed:

- [ ] Unclear scope.
- [ ] Multiple stakeholders.
- [ ] Compressed timing.
- [ ] Unusual review.
- [ ] Additional revisions.
- [ ] Difficult dependencies.
- [ ] High expected reliance.
- [ ] Complex acceptance.
- [ ] Extensive negotiation.
- [ ] Expanded information obligations.
- [ ] Specialized expertise.
- [ ] Travel.
- [ ] Scheduling disruption.
- [ ] Client-imposed tools or administration.
- [ ] Elevated legal, insurance, tax, regulatory, or professional-review needs.
- [ ] Capacity displacement.
- [ ] Collection risk.
- [ ] Payment delay.
- [ ] Remobilization.
- [ ] Revenue or client concentration.
- [ ] Source uncertainty.
- [ ] Model staleness.
- [ ] Private repository or recovery dependency.
- [ ] Strategic-investment, nonprofit, or pro bono capacity use.
- [ ] Third-party dependency.
- [ ] Material information-handling burden.
- [ ] Unusual approval or evidence burden.

Verify:

- [ ] Each material factor is priced, excluded, limited, escalated, or separately authorized.
- [ ] Contingency is linked to identified uncertainty.
- [ ] Contingency is not used to conceal missing scope.
- [ ] Risk adjustments are not duplicated.
- [ ] The selected treatment is approved.
- [ ] Residual risk is documented.

## 22. Capacity and Opportunity-Cost Review

Verify:

- [ ] Available delivery capacity is defined.
- [ ] Committed capacity is defined.
- [ ] Reserved capacity is identified.
- [ ] Non-delivery obligations are considered.
- [ ] Travel and administration are considered.
- [ ] Qualified-review time is considered.
- [ ] Pro bono or strategic capacity is considered.
- [ ] Capacity units and periods are consistent.
- [ ] Capacity assumptions are sourced or labeled.
- [ ] Opportunity cost is considered when material.
- [ ] Overcommitment risk is assessed.
- [ ] Capacity displacement is assessed.
- [ ] Capacity results are not represented as actual productivity.
- [ ] Later-authorized pipeline assumptions are separated from approved commitments.
- [ ] Capacity-sensitive outputs are tested under stress.

## 23. Price-Boundary and Management-Margin Review

Verify:

- [ ] Proposed price is traceable to approved inputs.
- [ ] Price boundary is defined privately.
- [ ] Price boundary rationale is documented.
- [ ] Applicable minimum approved rate is respected.
- [ ] Direct and variable cost treatment is documented.
- [ ] Contingency treatment is documented.
- [ ] Qualified-review cost treatment is documented.
- [ ] Capacity and opportunity-cost treatment is documented.
- [ ] Collection risk is documented.
- [ ] Exception effect is documented.
- [ ] Management margin formula is documented.
- [ ] Management margin is not labeled as a generally accepted accounting measure without review.
- [ ] Negative or below-boundary results are escalated.
- [ ] Manual changes are visible and approved.
- [ ] Outputs reconcile after rounding.

## 24. Payment, Collection, Travel, and Remobilization Review

Verify, as applicable:

- [ ] Billing basis is identified.
- [ ] Invoice trigger is identified.
- [ ] Invoice timing is identified.
- [ ] Deposit or advance-payment treatment is reflected.
- [ ] Milestone treatment is reflected.
- [ ] Due date assumptions are reflected.
- [ ] Payment method category is appropriate.
- [ ] Expense treatment is reflected.
- [ ] Travel authorization is reflected.
- [ ] Travel-time treatment is reflected.
- [ ] Travel-expense treatment is reflected.
- [ ] Cancellation treatment is reflected.
- [ ] Remobilization triggers are reflected.
- [ ] Remobilization treatment is reflected.
- [ ] Collection stages are reflected.
- [ ] Settlement assumptions are approved.
- [ ] Write-off assumptions are approved.
- [ ] Bad-debt assumptions are supported.
- [ ] Bookkeeping linkage is identified.
- [ ] G3 status supports the intended use.
- [ ] Counsel review supports legal-remedy assumptions when applicable.
- [ ] No live collection action is authorized by model approval.

## 25. Exception and Strategic-Investment Reconciliation

For each applicable exception, verify:

- [ ] Exception evidence identifier is present.
- [ ] Category is identified.
- [ ] Business rationale is documented.
- [ ] Scope effect is reflected.
- [ ] Effort effect is reflected.
- [ ] Schedule effect is reflected.
- [ ] Capacity effect is reflected.
- [ ] Financial effect is reflected.
- [ ] Margin effect is reflected.
- [ ] Collection effect is reflected.
- [ ] Client expectation risk is reflected.
- [ ] Precedent risk is reflected.
- [ ] Compensating control is reflected.
- [ ] Approver and authority are documented.
- [ ] Qualified-review status is documented.
- [ ] Effective date is valid.
- [ ] Expiration is valid.
- [ ] Maximum authorized use is respected.
- [ ] Related rate-card version is correct.
- [ ] Related model version is correct.
- [ ] Outcome and closure are tracked.
- [ ] Superseded exceptions are not used.
- [ ] Model outputs reconcile to the approved exception.

## 26. Scenario Validation

Validate, as applicable:

- [ ] Conservative scenario.
- [ ] Expected scenario.
- [ ] Favorable scenario.
- [ ] Capacity-stress scenario.
- [ ] Collection-delay scenario.
- [ ] Scope-expansion scenario.
- [ ] Qualified-review-cost scenario.
- [ ] Travel or remobilization scenario.
- [ ] Exception or strategic-investment scenario.
- [ ] Zero-revenue or no-engagement scenario.

For each scenario, verify:

- [ ] Purpose is documented.
- [ ] Model version is identified.
- [ ] Input set is identified.
- [ ] Input sources are identified.
- [ ] Assumption status is identified.
- [ ] Rate-card version is identified.
- [ ] Capacity assumption is identified.
- [ ] Collection assumption is identified.
- [ ] Cost assumption is identified.
- [ ] Contingency is identified.
- [ ] Output is identified.
- [ ] Sensitivity is identified.
- [ ] Limitation is identified.
- [ ] Owner review is documented.
- [ ] Qualified-review status is documented.
- [ ] Date is present.
- [ ] Supersession status is present.
- [ ] Scenario results reconcile to the base model.
- [ ] Scenario changes affect only intended variables.
- [ ] Scenario results are not represented as proven forecasts.

## 27. KPI Formula Validation

Validate, as applicable:

- [ ] Available delivery capacity.
- [ ] Committed capacity.
- [ ] Capacity utilization.
- [ ] Billable realization.
- [ ] Contribution or management margin.
- [ ] Estimate variance.
- [ ] Billing timeliness.
- [ ] Collection cycle.
- [ ] Aging exposure.
- [ ] Exception utilization.
- [ ] Pro bono and strategic capacity use.
- [ ] Revenue concentration.
- [ ] Pipeline concentration when later authorized.
- [ ] Bad-debt rate.
- [ ] Model staleness.
- [ ] Recovery readiness.

For each KPI, verify:

- [ ] Name is present.
- [ ] Purpose is present.
- [ ] Formula is present.
- [ ] Numerator is present.
- [ ] Denominator is present.
- [ ] Unit is present.
- [ ] Source is present.
- [ ] Data owner is present.
- [ ] Review owner is present.
- [ ] Frequency is present.
- [ ] Threshold or decision rule is present when approved.
- [ ] Exception method is present.
- [ ] Qualified-review status is present.
- [ ] Data-quality requirement is present.
- [ ] Limitation is present.
- [ ] Preservation requirement is present.
- [ ] Public-summary treatment is present.
- [ ] Formula recomputes independently.
- [ ] Zero-denominator behavior is controlled.
- [ ] Missing-data behavior is controlled.
- [ ] KPI is not mislabeled as an accounting measure.

Actual KPI values and sensitive thresholds remain private.

## 28. Range, Boundary, and Adverse-Case Testing

Perform, as applicable:

- [ ] Zero-input test.
- [ ] Minimum-input test.
- [ ] Expected-input test.
- [ ] Maximum-input test.
- [ ] Adverse-case test.
- [ ] Negative-value test.
- [ ] Missing-input test.
- [ ] Duplicate-input test.
- [ ] Invalid-date test.
- [ ] Invalid-unit test.
- [ ] Extreme-capacity test.
- [ ] Delayed-collection test.
- [ ] High-rework test.
- [ ] High-qualified-review-cost test.
- [ ] Travel or remobilization disruption test.
- [ ] Exception-expiration test.
- [ ] Stale-rate-card test.
- [ ] Superseded-version test.
- [ ] Recovery-restored-version test.
- [ ] Rounding-boundary test.

Verify:

- [ ] Expected behavior is defined.
- [ ] Actual behavior matches expected behavior.
- [ ] Unexpected results are investigated.
- [ ] Material failures are corrected and retested.
- [ ] Test evidence is preserved.

## 29. Circular Reference, External Link, and Hidden-Logic Review

Verify:

- [ ] Circular references are absent or intentionally controlled.
- [ ] External links are identified.
- [ ] External links are necessary.
- [ ] External links point to approved sources.
- [ ] Broken links are absent.
- [ ] Hidden formulas are reviewed.
- [ ] Hidden rows and columns are reviewed.
- [ ] Hidden sheets are reviewed.
- [ ] Hidden named ranges are reviewed.
- [ ] Embedded objects are reviewed.
- [ ] Comments and notes are reviewed.
- [ ] Macros or scripts are reviewed.
- [ ] Data connections are reviewed.
- [ ] Conditional formatting does not conceal logic.
- [ ] Protected cells do not prevent validation.
- [ ] Cached or stale values are not relied upon.
- [ ] Sensitive data is not exposed through metadata.
- [ ] Undocumented logic is absent.

## 30. Manual Override and Change-Control Review

Verify:

- [ ] Every manual override is identifiable.
- [ ] Override purpose is documented.
- [ ] Override owner is identified.
- [ ] Override approver is identified.
- [ ] Override date is present.
- [ ] Affected formula or output is identified.
- [ ] Business rationale is documented.
- [ ] Financial effect is documented.
- [ ] Scope effect is documented.
- [ ] Capacity effect is documented.
- [ ] Collection effect is documented.
- [ ] Qualified-review status is documented.
- [ ] Expiration or review date is documented.
- [ ] Compensating control is documented.
- [ ] Override is included in reconciliation.
- [ ] Override is preserved in version history.
- [ ] Hidden or silent overrides are absent.
- [ ] Unauthorized overrides result in failure.

## 31. Recalculation and Independent Recomputation

Verify:

- [ ] The model recalculates using the current approved inputs.
- [ ] Recalculation errors are absent.
- [ ] Material formulas are independently recomputed.
- [ ] Independent recomputation uses an approved method.
- [ ] Recomputed inputs match the authoritative source.
- [ ] Recomputed units and periods match.
- [ ] Recomputed outputs match after documented rounding.
- [ ] Differences are identified.
- [ ] Differences are explained.
- [ ] Unexplained differences are absent.
- [ ] Recalculation evidence is preserved.
- [ ] Independent recomputation evidence is preserved.
- [ ] Validator independence is described accurately.
- [ ] Owner review is not represented as independent assurance.

## 32. Reconciliation Requirements

Reconcile, as applicable:

- [ ] Source record to model input.
- [ ] Rate-card version to rate input.
- [ ] Scope version to effort estimate.
- [ ] Effort estimate to base effort value.
- [ ] Complexity and risk factors to adjustments.
- [ ] Travel and expense records to model treatment.
- [ ] Contingency rationale to contingency input.
- [ ] Capacity assumptions to capacity outputs.
- [ ] Collection assumptions to collection outputs.
- [ ] Exception record to model adjustment.
- [ ] Scenario inputs to scenario outputs.
- [ ] KPI source data to KPI outputs.
- [ ] Approval record to active version.
- [ ] Supersession history to current version.
- [ ] Backup-restored version to approved version.
- [ ] Public summary to sanitized private status.

The reconciliation record shall identify:

1. Record compared.
2. Version.
3. Date.
4. Expected result.
5. Actual result.
6. Difference.
7. Explanation.
8. Materiality.
9. Corrective action.
10. Approver.
11. Closure status.

Required identifiers, versions, fields, and approval states shall reconcile exactly.

## 33. Rounding and Tolerance Review

Unless a stricter approved requirement applies:

- [ ] Currency totals reconcile to the smallest unit supported by the authoritative record after documented rounding.
- [ ] Percentage calculations reconcile to the approved formula after documented rounding.
- [ ] Rounding method is consistent.
- [ ] Intermediate rounding is controlled.
- [ ] Final rounding is controlled.
- [ ] Display formatting does not conceal underlying differences.
- [ ] Tolerance is documented.
- [ ] Tolerance is approved.
- [ ] Tolerance is proportionate.
- [ ] Tolerance is not used to conceal formula error.
- [ ] Tolerance is not used to conceal missing evidence.
- [ ] Tolerance is not used to conceal unauthorized override.
- [ ] Unexplained differences are absent.
- [ ] Material differences require remediation and retesting.

A public tolerance value shall not be published when it would reveal sensitive commercial strategy.

## 34. Version Comparison

Compare the tested version to the prior approved version:

- [ ] Added inputs are identified.
- [ ] Removed inputs are identified.
- [ ] Changed inputs are identified.
- [ ] Added formulas are identified.
- [ ] Removed formulas are identified.
- [ ] Changed formulas are identified.
- [ ] Added outputs are identified.
- [ ] Removed outputs are identified.
- [ ] Changed outputs are identified.
- [ ] Assumption changes are identified.
- [ ] Rate-card changes are identified.
- [ ] Scenario changes are identified.
- [ ] KPI changes are identified.
- [ ] Exception changes are identified.
- [ ] Qualified-review changes are identified.
- [ ] Manual overrides are identified.
- [ ] Access or authoritative-source changes are identified.
- [ ] Backup or recovery changes are identified.
- [ ] Approval impact is assessed.
- [ ] Retesting scope is documented.
- [ ] Superseded version is preserved.
- [ ] Stale active use is prevented.

## 35. Approval and Qualified-Review Review

Verify:

- [ ] Model owner approval is documented.
- [ ] Approval authority is documented.
- [ ] Approval date is documented.
- [ ] Approved version is exact.
- [ ] Approval scope is documented.
- [ ] Assumptions are documented.
- [ ] Limitations are documented.
- [ ] Open conditions are documented.
- [ ] Exception status is documented.
- [ ] Qualified-review trigger assessment is documented.
- [ ] Required legal review is complete or restricted.
- [ ] Required tax review is complete or restricted.
- [ ] Required accounting review is complete or restricted.
- [ ] Required insurance review is complete or restricted.
- [ ] Required technical review is complete or restricted.
- [ ] Qualified-review conditions are reflected.
- [ ] Approval does not exceed the evidence.
- [ ] Owner approval is not represented as independent or qualified review.
- [ ] Approval does not establish market acceptance or profitability.
- [ ] Approval does not authorize external execution.

## 36. Backup and Recovery Validation

Verify:

- [ ] Backup method is approved.
- [ ] Backup scope includes the model and required dependencies.
- [ ] Backup owner is identified.
- [ ] Backup trigger or frequency is defined.
- [ ] Secondary encrypted copy or equivalent recovery capability exists.
- [ ] Backup access is restricted.
- [ ] Integrity evidence exists.
- [ ] Correct version can be identified.
- [ ] Representative recovery has been performed.
- [ ] Restored model is readable.
- [ ] Restored model is complete.
- [ ] Formulas are preserved.
- [ ] Relationships are preserved.
- [ ] External dependencies are preserved or documented.
- [ ] Restored inputs reconcile.
- [ ] Restored outputs reconcile.
- [ ] Access remains restricted.
- [ ] Recovery limitations are documented.
- [ ] Failed recovery tests are remediated and retested.
- [ ] Recovery evidence is preserved.
- [ ] Residual risk is approved.

Backup existence alone does not prove recoverability.

## 37. Preservation and Supersession Review

Verify:

- [ ] Preservation state is documented.
- [ ] No-disposition boundary is applied.
- [ ] Open obligation, dispute, audit, investigation, incident, or review status is assessed.
- [ ] Approved model version is preserved.
- [ ] Validation evidence is preserved.
- [ ] Source evidence is preserved.
- [ ] Approval evidence is preserved.
- [ ] Qualified-review evidence is preserved.
- [ ] Exception evidence is preserved.
- [ ] Backup and recovery evidence is preserved.
- [ ] Superseded versions are preserved.
- [ ] Active-use links point to the current approved version.
- [ ] Stale versions are restricted.
- [ ] Closure does not imply disposition.
- [ ] Disposition is not performed without authority.

## 38. Finding and Corrective-Action Record

Each finding shall identify:

1. Finding identifier.
2. Validation identifier.
3. Model evidence identifier.
4. Model version.
5. Requirement.
6. Finding description.
7. Severity.
8. Affected input, formula, output, scenario, KPI, or control.
9. Financial effect.
10. Commercial effect.
11. Confidentiality effect.
12. Recovery effect.
13. Root cause.
14. Immediate containment.
15. Corrective action.
16. Owner.
17. Due date.
18. Retest requirement.
19. Retest result.
20. Approver.
21. Closure date.
22. Preservation state.
23. Residual risk.

A finding shall not be closed without evidence.

## 39. Stop Conditions

Stop approval, reliance, or affected use when:

1. G2 has not passed.
2. Applicable G3 requirements are incomplete.
3. The private authoritative source is not identified.
4. The tested version is unclear.
5. A material source is missing.
6. An assumption is represented as evidence.
7. A material formula is undocumented.
8. A formula cannot be independently recomputed.
9. A model cannot reconcile.
10. A hidden or unauthorized override exists.
11. A circular reference is uncontrolled.
12. An external link is broken, unauthorized, or unsupported.
13. Units, periods, signs, or currencies are materially inconsistent.
14. A price boundary is breached without approval.
15. A required qualified review is missing.
16. An exception lacks authority or evidence.
17. A stale version may be used.
18. Backup is missing.
19. Recovery fails.
20. A private value is proposed for public Git.
21. A material finding remains open without an approved restriction.
22. External activity is proposed without authority.
23. Release 2.7 or later work begins.
24. A stricter requirement conflicts with this checklist.

## 40. Fallbacks

| Condition | Required Fallback |
| --- | --- |
| G2 fails | Stop private population and reliance; repair or replace the private source and retest |
| G3 remains incomplete | Restrict affected population, approval, conclusion, and live use |
| Source evidence is weak | Use a labeled assumption or range and conservative scenario |
| Material input is missing | Stop approval, obtain evidence, or remove the affected output |
| Formula fails | Correct the formula and rerun all affected tests |
| Model does not reconcile | Freeze approval, correct, and retest |
| Independent recomputation differs | Investigate, correct, reconcile, and retest |
| Qualified review is pending | Restrict the affected conclusion or use |
| Rate card is stale | Revalidate or replace the rate card before reliance |
| Scenario fails | Correct the scenario logic and retest all dependent outputs |
| KPI fails | Correct the formula, source, or data-quality control and retest |
| Backup fails | Repair backup and revalidate |
| Recovery fails | Repair recovery and repeat representative recovery |
| Public summary is unsafe | Aggregate, redact, restrict, delay, or keep private |
| Record state is unclear | Apply the more restrictive state |
| Material finding remains open | Defer approval or approve only a documented restricted use |
| Disposition authority is unclear | Preserve the record |
| Confidential exposure occurs | Contain, preserve evidence, remediate, and revalidate |

## 41. Public Repository Confidentiality Review

Before committing a public checklist or sanitized conclusion, verify that it contains no:

- [ ] Actual rates.
- [ ] Actual prices.
- [ ] Actual margins.
- [ ] Actual cost inputs.
- [ ] Actual thresholds.
- [ ] Actual reserves.
- [ ] Actual capacity values.
- [ ] Actual scenario outputs.
- [ ] Actual KPI values.
- [ ] Client, prospect, vendor, or referral-source identities.
- [ ] Invoice or collection details.
- [ ] Banking information.
- [ ] Tax records.
- [ ] Signatures.
- [ ] Executed agreements.
- [ ] Privileged advice.
- [ ] Credentials.
- [ ] Recovery keys.
- [ ] Sensitive configuration.
- [ ] Sensitive private file names or paths.
- [ ] Unnecessary personal information.
- [ ] Raw private validation, backup, recovery, or incident evidence.

The review shall include file names, paths, branch names, commit messages, issue text, screenshots, comments, embedded content, metadata, and validation output.

## 42. Validation Evidence Package

The private validation evidence package shall include, as applicable:

1. Completed checklist.
2. Validation record.
3. Model version.
4. Input inventory.
5. Source classification.
6. Assumption register.
7. Formula inventory.
8. Rate-card linkage.
9. Scenario validation.
10. KPI validation.
11. Independent recomputation.
12. Reconciliation record.
13. Version comparison.
14. Findings.
15. Corrective actions.
16. Retest evidence.
17. Approval.
18. Qualified-review evidence.
19. Backup evidence.
20. Recovery evidence.
21. Preservation evidence.
22. Residual-risk decision.

The public repository may contain only an unpopulated checklist and sanitized validation conclusion.

## 43. Final Validation Decision

Use one decision:

1. Pass.
2. Pass with conditions.
3. Fail.
4. Revalidation required.
5. Suspended.

The decision shall identify:

1. Validation identifier.
2. Model evidence identifier.
3. Model version.
4. Scope.
5. Result.
6. G2 status.
7. G3 status.
8. Qualified-review status.
9. Findings.
10. Open conditions.
11. Restricted uses.
12. Required remediation.
13. Retest status.
14. Approver.
15. Date.
16. Backup status.
17. Recovery status.
18. Preservation state.
19. Residual risk.
20. Public-summary authorization.

A pass with conditions shall define the exact permitted use and all prohibited uses.

## 44. Acceptance Criteria

A private model may receive a final Pass only when:

1. G2 has passed.
2. Applicable G3 requirements have been satisfied.
3. The authoritative private source is approved.
4. The exact model version is identified.
5. All material inputs are inventoried.
6. Sources and assumptions are correctly classified.
7. All material formulas are inventoried.
8. Units, dates, periods, currencies, signs, and rounding are controlled.
9. Scope and effort traceability is complete.
10. Rate-card linkage is valid.
11. Cost and expense inputs are supported.
12. Complexity, risk, contingency, capacity, and opportunity-cost treatment is supported.
13. Price-boundary and management-margin treatment is supported.
14. Payment, collection, travel, and remobilization treatment is supported.
15. Exceptions reconcile.
16. Scenarios pass.
17. KPIs pass.
18. Boundary and adverse-case tests pass.
19. Hidden logic, external links, circular references, and overrides are controlled.
20. Recalculation and independent recomputation pass.
21. All required reconciliations pass.
22. Unexplained material differences are absent.
23. Version comparison is complete.
24. Required qualified review is complete or the model is restricted consistently with an approved limited-purpose decision.
25. Approval is complete.
26. Backup is complete.
27. Representative recovery passes.
28. Preservation and supersession controls are complete.
29. Critical and high findings are closed.
30. Moderate findings are closed or subject to an approved restriction and remediation plan.
31. Public-repository confidentiality review passes.
32. Residual risk is approved.

## 45. Validation Requirements for This Checklist

This checklist shall be validated for:

1. Alignment with the Release 2.6 plan.
2. Alignment with the Pricing and Commercial Approval Standard, Version 2.0.
3. Alignment with the Private Commercial Operations and Confidential Records Standard.
4. Alignment with the Private Commercial Artifact Inventory and Control Matrix.
5. Coverage of model validation and reconciliation requirements.
6. G2 and G3 treatment.
7. Stable evidence identifiers.
8. Source and assumption controls.
9. Formula controls.
10. Range and boundary tests.
11. Scenario controls.
12. KPI controls.
13. Recalculation and independent recomputation.
14. Reconciliation.
15. Rounding and tolerance.
16. Version comparison.
17. Qualified-review controls.
18. Backup and recovery.
19. Preservation and supersession.
20. Findings and corrective action.
21. Stop conditions.
22. Fallbacks.
23. Public confidentiality review.
24. No confidential values.
25. No live-party information.
26. No credentials or recovery material.
27. No private paths or sensitive configuration.
28. No unsupported qualified conclusion.
29. No Release 2.7 work.
30. No records-disposition authority.
31. ASCII.
32. Final newline.
33. Trailing whitespace.
34. Tab characters.
35. Unresolved markers.
36. Markdown headings and tables.
37. Exact changed path.
38. Checksum.
39. `git diff --check`.
40. Synchronization and clean working tree.

## 46. Approval Boundary

Approval of this checklist approves:

1. The public unpopulated commercial model validation method.
2. The validation result and finding vocabularies.
3. The private validation record fields.
4. The source, formula, scenario, KPI, reconciliation, approval, backup, recovery, and evidence controls.
5. The stop conditions and fallbacks.
6. The final validation decision method.

Approval does not:

1. Approve a private repository.
2. Establish G2 completion.
3. Establish G3 completion.
4. Create, populate, approve, or validate an actual private model.
5. Approve actual rates, prices, margins, costs, thresholds, scenarios, or KPI values.
6. Approve a client, vendor, contract, invoice, collection action, delivery, or pilot.
7. Authorize Release 2.7 work.
8. Authorize records disposition.
9. Authorize production framework publication.
10. Establish legal, tax, accounting, insurance, regulatory, technical, market, effectiveness, scalability, security, or compliance conclusions.

This approved checklist becomes active only after controlled validation, commit, synchronization, and confirmation against a clean repository baseline.
