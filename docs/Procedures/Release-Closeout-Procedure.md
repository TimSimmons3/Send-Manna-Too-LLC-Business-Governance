# Release Closeout Procedure

## Document Control

| Field | Value |
| --- | --- |
| Document | Release Closeout Procedure |
| Owner | Send Manna Too LLC |
| Status | Approved |
| Canonical Source | Markdown in Git |
| Release | 0.2 |

## Purpose

This procedure defines the controlled process for closing a Send Manna Too LLC Business Governance Framework release.

The purpose is to ensure that each release is validated, approved, committed, synchronized, tagged, backed up, checksum-validated, and recoverable.

## Authority

Markdown in Git remains the authoritative source of truth for controlled governance framework content.

Git remains the authoritative version history for controlled releases.

GitHub is used for remote backup, synchronization, and review support.

Word, PDF, and PowerPoint files are publication outputs unless a future approved decision changes the governance architecture.

## Scope

This procedure applies to controlled framework releases, including:

- Foundation releases.
- Publication template releases.
- Policy, standard, framework, procedure, and playbook releases.
- Template, checklist, and script releases.
- Other controlled releases approved under the governance framework.

## Release Closeout Trigger

Release closeout begins only after planned release deliverables have been created, reviewed, and validated.

Do not close a release while required deliverables, decision records, future consideration updates, or change log entries remain incomplete.

## Procedure Overview

The release closeout process follows these stages:

1. Confirm release scope completion.
2. Validate controlled files.
3. Update required records.
4. Review Git status and changes.
5. Create approval commit.
6. Push and validate synchronization.
7. Create release closeout commit when required.
8. Push and validate synchronization again.
9. Create release tag.
10. Create backup package.
11. Create checksum.
12. Copy backup to approved location.
13. Validate copied backup checksum.
14. Prepare handoff or closeout summary.

## Step 1 - Confirm Release Scope Completion

Confirm that all planned release deliverables are present and complete.

Validate that:

- Required release files exist.
- Required documents have the correct owner, status, canonical source, and release identifier.
- Each document has one primary purpose.
- Duplicate guidance is avoided.
- Deferred items are recorded in the Future Considerations Register.
- Required governance decisions are recorded in the Decision Register.

## Step 2 - Validate Controlled Files

Run release validation before approval.

At minimum, validate that:

- Markdown files contain only ASCII characters.
- Markdown files contain no trailing whitespace.
- Final release deliverables contain no unresolved placeholder status markers.
- Required files are present.
- Required headings and document control sections are present.
- Cross-references and paths are accurate.
- The change log is updated.
- The decision register is updated when required.
- The future considerations register is updated when required.

## Step 3 - Update Required Records

Before approval, update the required release records.

Required records may include:

- DECISIONS-LOG.md.
- FUTURE-CONSIDERATIONS.md.
- CHANGELOG.md.
- Release plan.
- Release notes or closeout summary when used.

Decision records must be used for material governance decisions.

Deferred work must be recorded in the Future Considerations Register.

## Step 4 - Review Git Status and Changes

Review the repository state before committing.

Use Terminal to confirm:

- Working tree changes are expected.
- No unrelated files are included.
- No generated backup packages are accidentally staged.
- No confidential or client-specific files are accidentally staged.
- Diffs are reasonable and aligned with the release scope.

## Step 5 - Create Approval Commit

Create an approval commit after release deliverables and required records pass validation.

The approval commit should represent the approved release content before closeout documentation.

Use a clear commit message that identifies the release and approval action.

## Step 6 - Push and Validate Synchronization

Push the approval commit using the approved Git workflow.

If command-line Git push authentication is not working, GitHub Desktop remains the approved temporary push workaround.

After pushing, validate from Terminal that local and remote branches are synchronized.

At minimum, confirm:

- Working tree is clean.
- Latest local commit is expected.
- Local main and origin/main are aligned.

## Step 7 - Create Release Closeout Commit When Required

If closeout documentation or the change log must be updated after approval, create a separate closeout commit.

The closeout commit should document the final release state, validation result, synchronization status, tag plan, and backup plan where applicable.

Use a clear commit message that identifies the release and closeout action.

## Step 8 - Push and Validate Synchronization Again

Push the closeout commit using the approved Git workflow.

After pushing, validate from Terminal that:

- Working tree is clean.
- HEAD, main, origin/main, and origin/HEAD are aligned where applicable.
- The latest commit is the expected closeout commit.

## Step 9 - Create Release Tag

Create a local release tag after the final closeout commit is synchronized.

The tag should point to the final closeout commit unless a documented decision states otherwise.

Use a stable tag naming pattern such as:

`release-[version]-[descriptor]`

Example:

`release-0.2-publication-templates-operating-closeout`

## Step 10 - Create Backup Package

Create a clean backup package from the repository after closeout.

The backup package should exclude Git internals and unnecessary temporary files.

At minimum, confirm that the backup package:

- Uses a clear release-based file name.
- Identifies the repository or framework.
- Identifies the release version.
- Identifies the final commit when practical.
- Excludes the .git directory.

## Step 11 - Create Checksum

Create a SHA-256 checksum for the backup package.

The checksum file should be stored next to the backup package.

## Step 12 - Copy Backup to Approved Location

Copy the backup package and checksum file to the approved backup location.

The approved location should be stable, recoverable, and appropriate for firm records.

## Step 13 - Validate Copied Backup Checksum

Validate the copied backup package against the checksum file after copying.

The copied backup is not considered validated until checksum verification passes.

## Step 14 - Prepare Handoff or Closeout Summary

Prepare a closeout summary or handoff when the release is complete.

The summary should include:

- Project name.
- Release version.
- Final status.
- Local repository path.
- GitHub repository path.
- Branch.
- Final commit.
- Release tag.
- Completed deliverables.
- Validation results.
- Backup package path.
- Checksum value.
- Known issues or deferred items.
- Recommended next release or next action.

## Restrictions

Release closeout must not:

- Include unvalidated deliverables.
- Include unrelated scope without a decision record.
- Treat publication outputs as authoritative source records.
- Skip synchronization validation after push.
- Skip checksum validation after backup copy.
- Hide deferred work or unresolved risks.

## Validation Checklist

Before declaring a release closed, confirm:

- Planned deliverables are complete.
- Required records are updated.
- Validation gates pass.
- Approval commit exists.
- Closeout commit exists when required.
- Remote synchronization is validated.
- Release tag exists and points to the intended commit.
- Backup package exists.
- Checksum file exists.
- Copied backup checksum validation passes.
- Handoff or closeout summary is complete.

## Future Implementation Note

This procedure defines the controlled release closeout process.

Release-specific automation, scripts, or checklists may be created later as controlled artifacts, but this Markdown procedure remains the controlled governance source.
