# /project:create-pr

Prepare a PR description for a set of changes.

## Instructions

1. Load the following convention files **in this order** (reading guide for "Create a PR"):
   - `Coding_conventions/09-Git_pr_release_convention.md`
   - `Coding_conventions/11-Definition_of_done.md`
   - `Coding_conventions/15-Documentation_conventions.md`

2. Prepare a PR description for the changes described below:

   **Changes:** $ARGUMENTS

3. Output a complete PR description with the following sections:

   ### PR Title
   - Follow the commit message convention from file 09 (e.g., `feat:`, `fix:`, `refactor:`, `chore:`)
   - Keep it concise and descriptive (max 72 characters)

   ### Summary of Changes
   - Bullet-point list of what was changed and why
   - Reference any related issues or tickets if applicable

   ### Definition of Done Checklist
   - Reproduce the full DoD checklist from `11-Definition_of_done.md`
   - Mark each item as checked `[x]` or unchecked `[ ]` based on the described changes

   ### Documentation Notes
   - List any documentation that was added, updated, or still needs to be written
   - Follow the documentation standards from `15-Documentation_conventions.md`
   - Flag any missing docstrings, type hints, README updates, or CHANGELOG entries
