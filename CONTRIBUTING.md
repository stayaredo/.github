# Contributing

- Work on a short-lived branch and open a pull request against `main`. Squash merge only.
- The PR title follows Conventional Commits (`feat:`, `fix:`, `docs:`, `chore:`, ...); it becomes the squash commit message.
- Every PR cites the architecture decision it relies on when relevant (`ADR: NNNN`) and the requirement it implements (`Req:`).
- Commits produced with Claude Code carry the trailer `Assisted-by: Claude Code:<model-id>`. The human opening the PR is the sole author.
- CI must be green before merge. Do not disable or skip tests to get there.
