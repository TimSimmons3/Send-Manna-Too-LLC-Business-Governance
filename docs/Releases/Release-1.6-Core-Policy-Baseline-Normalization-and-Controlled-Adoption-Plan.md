# Release 1.6 Core Policy Baseline Normalization and Controlled Adoption Plan

## Document Control

| Field | Value |
| --- | --- |
| Organization | Send Manna Too LLC |
| Framework | Business Governance Framework |
| Document Type | Release Plan |
| Release | Release 1.6 |
| Release Name | Core Policy Baseline Normalization and Controlled Adoption |
| Status | Proposed for approval |
| Owner | Send Manna Too LLC |
| Approving Authority | Send Manna Too LLC governance authority |
| Canonical Source | `docs/Releases/Release-1.6-Core-Policy-Baseline-Normalization-and-Controlled-Adoption-Plan.md` |
| Publication Formats | Markdown in Git is canonical; Word, PDF, and PowerPoint are publication formats only |
| Effective Date | Upon approval and synchronization |
| Review Cycle | Through Release 1.6 closeout |

## 1. Purpose

This plan governs Release 1.6 of the Send Manna Too LLC Business Governance Framework.

Release 1.6 will normalize the administrative document-control baseline and stable operating presentation of the seven approved core governance policies without changing substantive policy requirements.

The release will make the canonical policy files accurately reflect their approved status, original release, effective date, version, ownership, approval authority, source, publication treatment, and review-cycle basis before broader operationalization, controlled distribution, training, production publication, or final framework closeout.

## 2. Release Objective

Normalize the document-control metadata and release-development scaffolding of the seven approved core governance policies while preserving all substantive policy obligations, scope boundaries, authority relationships, exceptions, noncompliance requirements, and review requirements.

## 3. Authoritative Baseline

The authoritative baseline is the synchronized `main` branch at:

`26994f6 Document Release 1.5 closeout`

The following references were validated as aligned at `26994f6` before Release 1.6 planning:

- `HEAD`
- `main`
- `origin/main`
- `origin/HEAD`
- `release-1.5-core-governance-policy-set-completion-review-next-phase-planning-closeout`

The working tree was clean.

No Release 1.6 artifact existed at the start gate.

## 4. Canonical Policy Set

Release 1.6 applies only to these seven canonical Markdown policy files:

1. `docs/Foundation/Governance-and-Operating-Authority-Policy.md`
2. `docs/Foundation/Client-Engagement-Governance-Policy.md`
3. `docs/Foundation/Commercial-and-Contracting-Governance-Policy.md`
4. `docs/Foundation/Information-Handling-and-Confidentiality-Policy.md`
5. `docs/Foundation/Third-Party-and-Partner-Governance-Policy.md`
6. `docs/Foundation/Records-Evidence-and-Retention-Policy.md`
7. `docs/Foundation/External-Deliverable-Governance-Policy.md`

No additional policy is included.

## 5. Confirmed Problem Statement

The Release 1.6 read-only inventory confirmed the following administrative baseline defects:

- Six approved policies still identify themselves as drafts.
- Two approved policies retain `Upon approval` as the effective date.
- One approved policy lacks status, version, release, effective-date, owner, and consistently named approving-authority fields.
- Document-control structures vary among Markdown tables, plain-text metadata, and tables without a `Document Control` heading.
- Owner terminology varies among `Owner`, `Document Owner`, `Primary Owner`, `Owning Authority`, and `Approved By`.
- Version terminology varies between `1.0` and a release identifier.
- Canonical-source values vary between a general source statement and an exact repository-relative path.
- Review-cycle metadata is absent from several policies and differs in underlying obligation among policies.
- Four policies retain release approval criteria after their releases were completed.
- Three policies retain release notes after their releases were completed.
- Release-development scaffolding remains embedded inconsistently in stable policy documents.

These defects do not invalidate the original approval commits or release closeouts. They create ambiguity for controlled adoption, policy reliance, review, maintenance, publication, distribution, audit evidence, and future change control.

## 6. Evidence Basis

The seven policy implementation commits and seven release closeout commits were reviewed.

All seven release closeout records were committed on `2026-07-10`:

| Policy | Original Release | Closeout Commit |
| --- | --- | --- |
| Governance and Operating Authority Policy | Release 0.8 | `0a0ba40 Document Release 0.8 closeout` |
| Client Engagement Governance Policy | Release 0.9 | `7527168 Document Release 0.9 closeout` |
| Commercial and Contracting Governance Policy | Release 1.0 | `3359db4 Document Release 1.0 closeout` |
| Information Handling and Confidentiality Policy | Release 1.1 | `2121ab9 Document Release 1.1 closeout` |
| Third-Party and Partner Governance Policy | Release 1.2 | `b8ee074 Document Release 1.2 closeout` |
| Records Evidence and Retention Policy | Release 1.3 | `fa5141d Document Release 1.3 closeout` |
| External Deliverable Governance Policy | Release 1.4 | `cc6a27c Document Release 1.4 closeout` |

The Governance and Operating Authority Policy establishes that governance authority approves new policies and policy changes. The normalized approving-authority value will therefore be role-based rather than person-dependent.

## 7. Scope

Release 1.6 will:

- Approve one normalized policy document-control schema.
- Apply the schema consistently to all seven policies.
- Add a `Document Control` heading where missing.
- Convert plain-text metadata to the approved Markdown table format.
- Normalize field names and field order.
- Normalize approved and active status.
- Normalize version values.
- Preserve each policy's original release identifier.
- Normalize effective dates using the original release closeout date.
- Normalize policy owner values.
- Normalize approving-authority values.
- Normalize canonical-source values to exact repository-relative Markdown paths.
- Normalize publication-format statements.
- Add a review-cycle metadata field without expanding the underlying review obligation.
- Evaluate each release-specific final section.
- Remove release-development scaffolding only after no-loss verification.
- Preserve any unique enduring scope or exclusion language before scaffolding removal.
- Verify that substantive policy content remains unchanged.
- Perform cross-policy comparison after normalization.
- Update `CHANGELOG.md`.
- Update `DECISIONS-LOG.md` if the normalized baseline decision is approved.
- Create the Release 1.6 implementation record.
- Create the Release 1.6 closeout record.
- Commit, push, synchronize, tag, back up, checksum, copy to iCloud, and validate recovery.

## 8. Exclusions

Release 1.6 will not create or perform:

- New substantive policy requirements.
- A new policy.
- A new standard.
- A new procedure, playbook, template, or checklist.
- Production Word, PDF, or PowerPoint policy artifacts.
- Training materials.
- A policy acknowledgment process.
- A retention schedule.
- Commercial or contracting execution aids.
- Client engagement execution aids.
- External deliverable execution aids.
- Third-party onboarding or assessment procedures.
- Information classification technical controls.
- Cybersecurity governance.
- AI governance.
- Privacy governance.
- Business continuity governance.
- Procurement governance.
- Employment governance.
- Technical controls.
- Workflow automation.
- Release automation.
- Legal advice or regulatory conclusions.
- Changes to the frozen Release 0.1 governance architecture.
- Resolution of the `FC-0002` status-value inconsistency.
- Assignment of release numbers beyond Release 1.6.

## 9. Normalized Document-Control Schema

Subject to approval of this plan, each policy will use the following field order:

1. Document
2. Document Type
3. Policy Area
4. Owner
5. Approving Authority
6. Status
7. Version
8. Release
9. Effective Date
10. Review Cycle
11. Canonical Source
12. Publication Formats

The table format will be:

| Field | Value |
| --- | --- |
| Document | Policy-specific title |
| Document Type | Policy |
| Policy Area | Policy-specific governance area |
| Owner | Send Manna Too LLC |
| Approving Authority | Send Manna Too LLC governance authority |
| Status | Approved and Active |
| Version | 1.0 |
| Release | Original policy release |
| Effective Date | Original release closeout date |
| Review Cycle | Policy-specific value preserving the existing obligation |
| Canonical Source | Exact repository-relative Markdown path |
| Publication Formats | Word, PDF, and PowerPoint are publication formats only |

## 10. Approved Administrative Value Rules

Subject to approval of this plan, the following rules will govern normalization:

### 10.1 Document

Use the exact policy title shown in the level-one heading.

### 10.2 Document Type

Use:

`Policy`

### 10.3 Policy Area

Use the policy's established governance domain without changing scope.

### 10.4 Owner

Use:

`Send Manna Too LLC`

This replaces inconsistent labels such as `Document Owner`, `Primary Owner`, and `Owning Authority`.

### 10.5 Approving Authority

Use:

`Send Manna Too LLC governance authority`

This is a durable, role-based value grounded in the Governance and Operating Authority Policy. Historical named approval evidence remains preserved in Git history and release closeout records.

### 10.6 Status

Use:

`Approved and Active`

This reflects the completed and approved release closeouts. It does not create a new approval or change the original approval date.

### 10.7 Version

Use:

`1.0`

The original release identifier will remain separately recorded in the `Release` field.

### 10.8 Release

Use the policy's original release:

- Governance and Operating Authority Policy: `Release 0.8`
- Client Engagement Governance Policy: `Release 0.9`
- Commercial and Contracting Governance Policy: `Release 1.0`
- Information Handling and Confidentiality Policy: `Release 1.1`
- Third-Party and Partner Governance Policy: `Release 1.2`
- Records Evidence and Retention Policy: `Release 1.3`
- External Deliverable Governance Policy: `Release 1.4`

### 10.9 Effective Date

Use:

`2026-07-10`

The date is based on the original approved release closeout commit for each policy. Because all seven closeouts occurred on the same date, the normalized value is the same across the seven-policy set.

### 10.10 Review Cycle

Normalize the field name, but do not expand or reduce the policy's existing review obligation.

For policies whose current Review and Maintenance section requires review upon material change, the metadata value will reflect that requirement without adding an annual review duty.

For policies already requiring review at least annually or upon material change, that existing requirement will be preserved.

Any future decision to impose one common annual review frequency across all policies requires a separate approved substantive change.

### 10.11 Canonical Source

Use the exact repository-relative Markdown path for each policy.

### 10.12 Publication Formats

Use:

`Word, PDF, and PowerPoint are publication formats only`

This does not authorize production publication during Release 1.6.

## 11. Policy-Specific Target Values

| Policy | Policy Area | Release | Effective Date | Review-Cycle Basis |
| --- | --- | --- | --- | --- |
| Governance and Operating Authority Policy | Governance and Operating Authority | Release 0.8 | 2026-07-10 | Preserve current material-change review requirement |
| Client Engagement Governance Policy | Client Engagement Governance | Release 0.9 | 2026-07-10 | Preserve current material-change review requirement |
| Commercial and Contracting Governance Policy | Commercial and Contracting Governance | Release 1.0 | 2026-07-10 | Preserve current material-change review requirement |
| Information Handling and Confidentiality Policy | Information Handling and Confidentiality | Release 1.1 | 2026-07-10 | Preserve current material-change review requirement |
| Third-Party and Partner Governance Policy | Third-Party and Partner Governance | Release 1.2 | 2026-07-10 | Preserve current annual-or-material-change requirement |
| Records Evidence and Retention Policy | Records Evidence and Retention | Release 1.3 | 2026-07-10 | Preserve current annual-or-material-change requirement |
| External Deliverable Governance Policy | External Deliverable Governance | Release 1.4 | 2026-07-10 | Preserve current annual-or-material-change requirement |

## 12. Release-Specific Final Section Treatment

The following sections are release-development scaffolding rather than stable policy requirements:

- `Release 0.8 Approval Criteria`
- `Release 0.9 Approval Criteria`
- `Release 1.0 Approval Criteria`
- `Release 1.1 Approval Criteria`
- `Release 1.2 Notes`
- `Release 1.3 Notes`
- `Release 1.4 Notes`

The approval-criteria sections document gates that were satisfied and are preserved in release plans, closeouts, validation evidence, and Git history. They should not remain in stable policy text after controlled normalization.

The release-notes sections contain implementation context, scope exclusions, and canonical-source reminders. Before removal, each section must be compared against the policy's Purpose, Scope, Relationship to Other Governance Documents, Review and Maintenance, and normalized document-control metadata.

A release-specific final section may be removed only when:

- Its approval or historical purpose is preserved in the applicable release record and Git history.
- Its enduring scope boundaries already exist elsewhere in the policy.
- Its canonical-source and publication statements are preserved in normalized metadata.
- No unique substantive requirement would be lost.
- Any unique enduring language is relocated to the appropriate stable policy section before removal.
- The relocation does not expand, narrow, or otherwise change the policy obligation.

## 13. Proposed Decision Record

If this plan is approved, Release 1.6 should record the following material decision:

`DEC-0012: Adopt a Common Administrative Document-Control Baseline for Controlled Policies`

The decision should establish that:

- Controlled policies use the approved common metadata schema.
- Role-based governance authority is used instead of a person-dependent approving-authority value.
- Approved policy status is reflected as `Approved and Active`.
- Version and release are separate fields.
- Original release closeout dates provide the effective-date basis.
- Exact repository-relative Markdown paths identify canonical sources.
- Publication formats remain non-canonical.
- Review-cycle metadata preserves existing obligations and does not create a new common annual review duty.
- Release-development scaffolding is removed only after no-loss verification.
- Administrative normalization does not reopen or substantively amend approved policy requirements.

## 14. Implementation Method

Release 1.6 implementation will use controlled candidate files and small validation gates.

### Phase 1 - Plan Approval

- Validate this plan.
- Review the full diff.
- Commit the plan separately.
- Push through GitHub Desktop.
- Validate local and remote synchronization.
- Do not edit policy files before this phase is complete.

### Phase 2 - Baseline Evidence

- Confirm the seven policy files.
- Capture current SHA-256 hashes.
- Capture current document-control sections.
- Capture current release-specific final sections.
- Create a policy inventory in the Release 1.6 implementation record.
- Capture substantive-body fingerprints that exclude document-control metadata and release-specific final sections.

### Phase 3 - Candidate Normalization

- Create candidate copies outside the canonical paths.
- Apply only the approved metadata and scaffolding changes.
- Preserve all substantive policy text byte-for-byte where practical.
- Compare each candidate against its canonical source.
- Review every changed line.

### Phase 4 - No-Loss Review

- Compare release notes with stable policy scope and exclusion language.
- Confirm that removed approval criteria remain preserved in release evidence.
- Confirm that no authority, obligation, exception, noncompliance, scope, evidence, or review requirement is lost or changed.
- Recalculate substantive-body fingerprints.
- Resolve any mismatch before promotion.

### Phase 5 - Controlled Promotion

- Promote validated candidate files to the seven canonical paths.
- Review the combined cross-policy diff.
- Update `DECISIONS-LOG.md` if DEC-0012 is approved.
- Update `CHANGELOG.md`.
- Create the Release 1.6 implementation record.

### Phase 6 - Validation and Closeout

- Run Markdown quality checks.
- Run ASCII validation.
- Run trailing-whitespace validation.
- Run drafting-marker scans.
- Run `git diff --check`.
- Review staged diffs.
- Commit implementation.
- Push and validate synchronization.
- Create and validate the Release 1.6 closeout record.
- Commit and synchronize closeout.
- Create the local annotated tag.
- Create and validate the recovery package.
- Copy the package to iCloud.
- Validate local and iCloud checksums.

## 15. Substantive-Change Prevention Controls

The following controls are mandatory:

- No policy requirement may be added, removed, broadened, narrowed, or reinterpreted.
- No scope boundary may change except relocation of identical enduring language.
- No authority or decision right may change.
- No exception or noncompliance requirement may change.
- No evidence or records requirement may change.
- No review obligation may change.
- No cross-policy precedence statement may change.
- No production publication artifact may be created.
- Each changed line must be classified as metadata normalization, heading normalization, release-scaffolding removal, or exact relocation of enduring language.
- Any change that cannot be classified as administrative must be rejected or moved to a separately approved future release.
- Substantive-body fingerprints must match before and after normalization, except for an approved exact relocation documented in the implementation record.
- Candidate hashes must be recorded before promotion.
- Promoted-file hashes must match the approved candidate hashes.

## 16. Validation Requirements

Release 1.6 will not pass unless all of the following are true:

- The baseline commit is confirmed.
- The working tree is clean before implementation.
- Exactly seven canonical policy files are in scope.
- All seven policies use the approved document-control heading and table structure.
- All twelve approved metadata fields are present in the approved order.
- All statuses read `Approved and Active`.
- All versions read `1.0`.
- All releases match the original policy releases.
- All effective dates read `2026-07-10`.
- All owners read `Send Manna Too LLC`.
- All approving authorities read `Send Manna Too LLC governance authority`.
- All canonical-source values use exact repository-relative paths.
- All publication-format statements use the approved standard language.
- Review-cycle values preserve existing obligations.
- No policy retains a draft status.
- No policy retains `Upon approval`.
- No release approval-criteria section remains.
- No release-notes section remains unless the implementation record documents a specific no-loss exception.
- Substantive policy text remains unchanged except for approved exact relocation.
- Cross-policy comparison passes.
- ASCII validation passes.
- Trailing-whitespace validation passes.
- Drafting-marker scans pass.
- `git diff --check` passes.
- Staged-diff review passes.
- Candidate and promoted hashes match.
- `CHANGELOG.md` accurately records Release 1.6.
- Any approved material decision is recorded in `DECISIONS-LOG.md`.
- The Release 1.6 implementation record is complete.
- The Release 1.6 closeout record is complete.
- Local and remote references align after each push.
- The local tag resolves to the final closeout commit.
- ZIP integrity and checksum validation pass.
- Local and iCloud recovery copies match.

## 17. Required Deliverables

Release 1.6 will produce:

- `docs/Releases/Release-1.6-Core-Policy-Baseline-Normalization-and-Controlled-Adoption-Plan.md`
- `docs/Releases/Release-1.6-Core-Policy-Baseline-Normalization-and-Controlled-Adoption-Record.md`
- `docs/Releases/Release-1.6-Core-Policy-Baseline-Normalization-and-Controlled-Adoption-Closeout.md`
- Normalized versions of the seven canonical policy files
- Updated `CHANGELOG.md`
- Updated `DECISIONS-LOG.md` if DEC-0012 is approved
- Release 1.6 local annotated tag
- Release 1.6 ZIP recovery package
- Release 1.6 SHA-256 checksum file
- Validated iCloud recovery copy

No Word, PDF, or PowerPoint policy artifact is a Release 1.6 deliverable.

## 18. Commit Strategy

Use separate commits for controlled review and recovery:

1. Add the approved Release 1.6 plan.
2. Normalize the seven-policy administrative baseline and document the implementation.
3. Document Release 1.6 closeout.

Additional commits require a documented reason.

## 19. Push and Synchronization Strategy

Command-line Git push authentication remains deferred.

Use GitHub Desktop to push approved commits.

After every push, validate:

- `HEAD`
- `main`
- `origin/main`
- `origin/HEAD`
- Working-tree status

Do not proceed to the next phase while references are misaligned.

## 20. Tagging and Recovery

After the final closeout commit is synchronized, create a local annotated tag using the approved Release 1.6 closeout name.

Create a ZIP recovery package from the final synchronized repository state.

Create a SHA-256 checksum file.

Validate:

- ZIP integrity.
- Local checksum.
- Local-to-iCloud ZIP byte comparison.
- Local-to-iCloud checksum-file byte comparison.
- iCloud checksum.

The exact tag and backup filenames will be finalized in the closeout record.

## 21. Risks and Responses

| Risk | Response |
| --- | --- |
| Administrative edits unintentionally change policy obligations | Use candidate files, line-by-line diff review, substantive-body fingerprints, and no-loss validation |
| A common review-cycle value creates a new annual duty | Preserve each policy's existing review obligation |
| Named-person approval metadata becomes stale | Use role-based Send Manna Too LLC governance authority |
| Historical release evidence is lost | Preserve plans, closeouts, Git history, tags, and implementation evidence |
| Release notes contain unique enduring scope language | Compare before removal and relocate only identical enduring language |
| Version and release remain conflated | Use separate `Version` and `Release` fields |
| Canonical-source statements remain ambiguous | Use exact repository-relative Markdown paths |
| Publication normalization triggers premature artifact creation | Preserve DEC-0011 and exclude production publication |
| Scope expands into unrelated governance work | Enforce the Release 1.6 exclusions and one-primary-objective rule |

## 22. Approval Criteria

This plan is approved when:

- The Release 1.5 baseline remains clean and synchronized.
- The seven-policy inventory is accepted.
- The normalized schema is accepted.
- The administrative value rules are accepted.
- The role-based approving-authority value is accepted.
- The effective-date basis is accepted.
- The review-cycle preservation rule is accepted.
- The release-scaffolding no-loss rule is accepted.
- The exclusions are accepted.
- The substantive-change prevention controls are accepted.
- The plan passes ASCII, trailing-whitespace, and `git diff --check` validation.
- The plan is committed, pushed, and synchronized before policy editing begins.

## 23. First Implementation Action After Plan Approval

After this plan is approved, committed, pushed, and synchronized:

1. Create the Release 1.6 implementation record.
2. Record the complete seven-policy inventory.
3. Capture baseline hashes and substantive-body fingerprints.
4. Prepare candidate normalized policy files outside the canonical paths.
5. Do not promote any candidate until all seven candidates pass cross-policy and no-loss review.
