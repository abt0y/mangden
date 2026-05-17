---
name: add-or-migrate-data-files
description: Workflow command scaffold for add-or-migrate-data-files in mangden.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /add-or-migrate-data-files

Use this workflow when working on **add-or-migrate-data-files** in `mangden`.

## Goal

Adds new data files or migrates existing ones into the project structure, often updating .gitignore to reflect new files.

## Common Files

- `data/*`
- `references/*`
- `.gitignore`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Add or move data files into appropriate data/ or references/ subfolders.
- Update .gitignore if necessary to exclude/include new files.

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.