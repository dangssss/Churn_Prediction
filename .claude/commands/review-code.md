# /project:review-code

Review code or a file for convention compliance.

## Instructions

1. Load the following convention files **in this order** (reading guide for "Review code"):
   - `Coding_conventions/10-Code_design_principles.md`
   - `Coding_conventions/03-Naming_style_conventions.md`
   - `Coding_conventions/05-Error_handling_convention.md`
   - `Coding_conventions/07-Testing_convention.md`
   - `Coding_conventions/11-Definition_of_done.md`

2. Review the code or file path provided below against all loaded conventions:

   **Target:** $ARGUMENTS

3. Output a **structured compliance report** with the following format for each finding:

   | # | Location | Violation | Severity | Recommended Fix |
   |---|----------|-----------|----------|-----------------|
   | 1 | `file.py:line` | Description of the violation | `critical` / `warning` / `suggestion` | How to fix it |

   **Severity definitions:**
   - `critical` — breaks a hard rule (e.g., secret in log, missing error handling at boundary, DoD item not met)
   - `warning` — violates a convention that degrades quality or maintainability
   - `suggestion` — improvement that is optional but recommended

4. End the report with a **DoD summary**: list which Definition of Done items pass and which fail for the reviewed code.
