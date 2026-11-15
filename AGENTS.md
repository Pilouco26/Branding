# Merge policy (AI agents)

This repository follows a non-negotiable review rule:

- **Never merge a pull request.** Do not run `gh pr merge`, do not enable
  auto-merge, and do not merge locally and push `main`/`master`.
- Opening a pull request is fine. After opening it, stop and wait.
- Only merge when the owner explicitly asks for that specific PR in the current
  conversation (for example: "merge PR #12 now"). Approval of the changes is
  not approval to merge.
- Never push directly to the default branch; always use a branch and a PR.
- Never approve your own work to satisfy a review requirement.
- Cutting a release or deploying is a separate explicit decision; do not do it
  just because a PR was merged.
