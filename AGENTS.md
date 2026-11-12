# My First — agent instructions

<!-- workspace-control:pre-write:start -->
## Mandatory workspace pre-write gate

Before any repository write, consult the current `main` versions in [prvfritz/workspace-control](https://github.com/prvfritz/workspace-control): [AGENTS.md](https://github.com/prvfritz/workspace-control/blob/main/AGENTS.md), [PROJECTS.md](https://github.com/prvfritz/workspace-control/blob/main/PROJECTS.md), [GLOBAL-RULES.md](https://github.com/prvfritz/workspace-control/blob/main/GLOBAL-RULES.md), and [WORKFLOW.md](https://github.com/prvfritz/workspace-control/blob/main/WORKFLOW.md). Refresh and inspect the local clone against `origin/main`, or read current remote files through the available connector; stale chat context is not a substitute.

Confirm in the task's pre-write explanation which Workspace Control revision was read, the target repository/branch, and the intended scope. Then follow this project's instructions; stricter project-specific restrictions still apply. If required governance cannot be accessed, stop before writing and report the blocker. A prior check remains valid within the same coherent task unless the scope changes or remote governance advances; do not recurse between the two AGENTS files indefinitely.

This gate covers creating, editing, deleting or generating repository files, and Git operations that change the working tree or history. Read-only discovery, remote reads and `git fetch` needed to perform this preflight are allowed. It does not authorise runtime, security, spending or unrelated project changes.
<!-- workspace-control:pre-write:end -->

Experimental public test repository; do not use for production project state. Do not add secrets or private project material.
