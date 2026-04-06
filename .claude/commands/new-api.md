# /project:new-api

Design and implement a new API endpoint.

## Instructions

1. Load the following convention files **in this order** (reading guide for "Write/review API"):
   - `Coding_conventions/12-Api_conventions.md`
   - `Coding_conventions/10-Code_design_principles.md`
   - `Coding_conventions/05-Error_handling_convention.md`
   - `Coding_conventions/06-Logging_observability_convention.md`
   - `Coding_conventions/03-Naming_style_conventions.md`
   - `Coding_conventions/08-Security_secrets_conventions.md`

2. Design and implement the API endpoint described below, applying all conventions from the loaded files:

   **API request:** $ARGUMENTS

3. Your implementation MUST cover:
   - **REST conventions**: correct HTTP methods, status codes, resource naming, versioning (from file 12)
   - **Error handling**: structured error responses by layer, no secrets in error messages (from files 05, 08)
   - **Logging**: request/response logging at boundary, correlation ID propagation (from file 06)
   - **Security**: input validation, no secrets in logs or responses, least-privilege access (from file 08)
   - **Code design**: single responsibility, clear naming, dependency direction (from files 10, 03)

4. Include the endpoint schema (request/response), route definition, handler, and any required service/repository calls.
