# A small pull request workflow

A pull request (PR) proposes a set of commits for discussion and merging into a base branch. This workflow keeps changes easy to understand and maintain.

## Before opening a PR

1. Start from an up-to-date `main` branch and create a focused feature branch.
2. Make one coherent change, then review the diff for accidental edits or generated files.
3. Write commit messages that describe the change, and push the branch to GitHub.

## Describe the proposal

A useful PR description explains the problem or goal, summarizes the change, and gives a way to verify it. Link related issues with closing keywords such as `Fixes #12` when the PR should close that issue after merging. Keep the PR focused; split unrelated work into separate proposals.

## Review and merge

Respond to review comments with context and follow-up commits as needed. Resolve conversations when the requested change is complete. Merge only after the repository's required checks and review rules are satisfied. After merging, confirm the PR's final state and remove the feature branch if it is no longer needed.
