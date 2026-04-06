# /project:write-tests

Write tests for a module or function.

## Instructions

1. Load the following convention files **in this order** (reading guide for "Write tests"):
   - `Coding_conventions/07-Testing_convention.md`
   - `Coding_conventions/10-Code_design_principles.md`
   - `Coding_conventions/03-Naming_style_conventions.md`

2. Write tests for the module or function described below:

   **Target:** $ARGUMENTS

3. Your tests MUST comply with the following requirements from file 07:
   - **Naming conventions**: test file names, test function names, and class names must follow the patterns defined in `07-Testing_convention.md §8`
   - **Fixtures and mocks**: use fixtures and mocks correctly as specified in file 07; do not over-mock internal logic
   - **Coverage requirements**: meet the minimum coverage thresholds defined in file 07
   - **Test types**: include unit tests at minimum; add integration tests if the target interacts with external systems or boundaries
   - **Arrange-Act-Assert**: structure every test with clear AAA sections
   - **No test interdependence**: each test must be independently runnable and not rely on execution order

4. If the target involves ML/data code, also load `Coding_conventions/13-data_ml_conventions.md` and apply its testing rules.
