# Contributing to the Velvet Ecosystem

Thank you for contributing to Velvet.

> Handmaidens propose. Mister approves. Repositories remember.

## Open contribution, controlled adoption

The Velvet ecosystem welcomes outside ideas, research, fixes, documentation, experiments, and code contributions. A contribution may be reviewed, tested, or accepted for further work without becoming an official ecosystem component immediately.

New reusable modules and substantial module rewrites must pass through the Velvet Module Lab before official promotion.

The public pathway and request form are maintained in `Velvet-ecosystem/velvet-docs`:

- `docs/contributing/module_lab_pathway.md`
- **Module Lab Request** issue form

The Module Lab provides:

- source and authorship tracking
- scope and authority review
- deterministic fixtures
- compatibility and failure testing
- hardware-boundary review
- promotion records

This protects ecosystem safety and quality while giving contributors a clear path toward official adoption.

A merge into the lab means accepted for assessment and testing. It does not mean production-ready, officially promoted, or authorized for active control.

The qualification workspace remains private in `Velvet-ecosystem/Modules` while the system is being established. Contributors begin through the public request pathway rather than by requesting access to the private lab.

## Repository-specific changes

Small documentation fixes, focused bug fixes, and changes that stay within an existing repository contract may follow that repository's normal contribution process.

Changes that introduce reusable cross-ecosystem behavior, expand authority, add hardware control, or substantially rewrite a module should be routed through the Module Lab.

## Default branch and pre-review workflow

Routine work should not be committed directly to `main`.

Use this flow unless a repository documents a stricter one:

1. Start from the current `main` branch.
2. Create a clearly named working branch such as `feature/...`, `fix/...`, `docs/...`, `agent/...`, or `governance/...`.
3. Make the smallest coherent change that solves the intended problem.
4. Push the branch and open a **draft pull request** before treating the change as complete.
5. Pre-review the diff, scope, tests, documentation, authority implications, privacy boundary, and failure behavior.
6. Resolve review findings and verify required checks.
7. Mark the pull request ready only when it is actually ready to merge.
8. Merge after owner/founder approval when the change is architectural, authority-bearing, safety-relevant, privacy-relevant, security-relevant, or otherwise consequential.
9. Prefer squash merge for a clean history unless preserving multiple commits is itself meaningful lineage.

Branches are proposals. Pull requests are the review table. `main` is the remembered state of the ecosystem.

## Pre-review checklist

Before merge, reviewers should ask:

- Does the diff match the stated scope?
- Did unrelated files change?
- Does this alter authority, permissions, hardware access, CAN behavior, shell/file access, package loading, networking, identity, privacy, safety, emergency behavior, continuity, receipts, or Runtime/Court boundaries?
- Are new dependencies necessary, bounded, and documented?
- Are failure modes and degraded behavior truthful?
- Are tests or validation evidence present where practical?
- Are docs and examples updated when contracts or behavior changed?
- Does the change preserve local-first and owner-controlled operation?
- Is anything private, credentialed, personally identifying, or unsuitable for the public repository?

## Authority-bearing changes

Changes that can affect physical authority, emergency behavior, authentication, module trust, secrets, remote access, privileged execution, or safety boundaries require explicit human review before merge. Passing automated checks is evidence, not approval.

## Documentation and doctrine changes

Documentation-only changes still use branches and pull requests when they modify doctrine, architecture, safety boundaries, public commitments, or canonical project history. Tiny typo fixes may use a lighter review, but direct-to-main should remain exceptional rather than habitual.

## Hotfix exception

An urgent hotfix may use an accelerated review when delay creates greater risk than immediate correction. The change should still be isolated, documented, and followed by a retrospective pull request or receipt describing what changed, why normal review was bypassed, and what verification was performed.

## Public/private boundary

Before opening a pull request, confirm that no private keys, tokens, passwords, personal records, private research, unpublished security details, or owner-only material have entered the public diff.

## Review and merge authority

Contributors do not need direct merge access to active ecosystem paths to participate meaningfully. Maintainers retain final review and promotion authority.

Contributions should state clearly:

- what is complete
- what is simulated
- what depends on hardware
- what remains untested
- what permissions or authority the change requests

The governing principle is simple: open contribution, controlled adoption.
