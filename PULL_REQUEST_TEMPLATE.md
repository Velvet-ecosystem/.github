## Summary

What changed, and why?

## Scope

List the repositories, files, modules, surfaces, contracts, or docs intentionally affected.

## Pre-review

- [ ] Diff matches the stated scope.
- [ ] No unrelated files changed.
- [ ] Public/private boundary checked.
- [ ] New dependencies are necessary and documented.
- [ ] Repository CI workflow / baseline test command was inspected.
- [ ] New or changed tests use the framework and dependencies that CI actually installs.
- [ ] Tests, fixtures, screenshots, hardware evidence, or validation notes are included where practical.
- [ ] Failure and degraded behavior are described truthfully.
- [ ] Docs/examples are updated when contracts or behavior changed.

## Test-runner spot check

State the exact test command or workflow used by this repository, especially when tests changed.

- CI / baseline command:
- Test framework expected by CI:
- New test imports/dependencies checked for framework drift: yes / no / not applicable
- Any intentional runner/dependency change included in this PR: yes / no

Do not assume all Velvet repositories use the same test framework. The repository's active CI workflow is the source of truth unless this pull request intentionally and completely changes that contract.

## Authority and safety boundary

Check every area this change touches:

- [ ] No authority-bearing behavior changes.
- [ ] Runtime / Court / executor authority path.
- [ ] Physical control or hardware access.
- [ ] CAN or vehicle behavior.
- [ ] Emergency / medical behavior.
- [ ] Authentication, identity, presence, or permissions.
- [ ] Module trust or package loading.
- [ ] Shell, file, privileged, or remote execution.
- [ ] Networking, cloud, or internet permission.
- [ ] Privacy, secrets, or personal data.
- [ ] Receipts, continuity, lineage, or evidence semantics.

If any authority-bearing box applies, explain the boundary and required human approval below.

## Validation

What was actually tested or reviewed?

- Complete:
- Simulated:
- Hardware-dependent:
- Untested / deferred:

## Review notes

Call out anything a reviewer should examine closely, including compatibility risks, migration needs, or intentionally deferred work.

## Merge posture

- [ ] Draft pre-review completed.
- [ ] Required checks are green or explicitly accounted for.
- [ ] Review findings are resolved.
- [ ] Owner/founder approval obtained where required.
- [ ] Squash merge is appropriate, or commit lineage preservation is explained.

> Handmaidens propose. Mister approves. Repositories remember.
