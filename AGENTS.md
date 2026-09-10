# Repository workflow

- `main` is the stable release branch and the GitHub Pages publishing source.
- Start changes on `feature/<name>`, `fix/<name>`, or `chore/<name>` from current `main`. Continue an existing feature branch when working on that feature.
- Develop Tape Rain on `feature/tape-rain` until its pull request is approved for merge.
- Do not commit, push, or write files through an API directly to `main` for ordinary development. Do not merge a pull request or publish feature changes without explicit user approval for that release. A request to continue development is not permission to publish.
- Open a draft pull request early. Describe the user-visible behavior, validation, and known limitations. Keep it unmerged until the user explicitly approves release.
- Preserve history: use revert commits for rollbacks. Never force-push or reset a shared branch to erase history.
- Before any API update, inspect the current remote branch and use a non-forced fast-forward update. Preserve unrelated changes.
- The Git checkout is the source of truth. `outputs/` packages outside this repository are deliverables, not a substitute for version control. Label stable and preview packages separately.
- Run checks relevant to the change. Visual effects require browser inspection, pause/resume, source switching, mobile layout, and affected export checks. Keep recordings muted unless audio support is intentionally added and tested.
- Follow `CONTRIBUTING.md` for branch, review, release, and local guard setup.

The one-time recovery on 2026-09-10 restores the stable ASCII application with an additive revert commit, preserves the Tape Rain work, and establishes this workflow. It is not a standing exception for future direct changes to `main`.
