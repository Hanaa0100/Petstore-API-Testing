# Petstore API Testing

## Overview

This repository contains the deliverables for a hands-on API testing training assignment based on the Swagger Petstore API. The objective was to practice sending API requests, writing Postman assertions, validating responses, and documenting test results.

## Scope

- **Smoke Testing:** Store inventory, Pet search by status, and User login.
- **Pet Lifecycle:** Create, retrieve, update, search, and delete Pets.
- **Store Lifecycle:** Create, retrieve, and delete Store orders.
- **User Lifecycle:** Create, retrieve, update, login, logout, and delete Users.
- **Negative Testing:** Invalid or missing input and malformed request body scenarios.
- **End-to-End Testing:** Execute the Pet workflow twice.
- **Additional Improvement:** Data integrity checks between Pet and Store Order resources.

*Store and User lifecycle scenarios were optional assignment areas. The CSV-based data-driven challenge was not completed as an execution.*

## Tools

- **Postman** -- API request execution and collection management.
- **Newman** -- Command-line collection execution and HTML reporting.
- **JavaScript** -- Tests and response assertions in Postman.
- **GitHub** -- Assignment deliverables and documentation.
- **Microsoft Excel** -- Test cases, results, findings, and evidence tracking.

## Execution Highlights

- Pet lifecycle: all seven recorded test cases passed (PET-01 to PET-07).
- End-to-end workflow: **29/29 passed in each of two runs**.
- Additional data integrity checks: **29/29 passed**.
- Some API observations and unexpected responses were documented as findings in the Excel workbook.
- Newman was used to execute the full collection and generate an HTML execution report.

## Repository Contents

| File | Description |
|---|---|
| `Petstore_API_Testing_Submission_Final(HANAA).xlsx` | Test cases, results, findings, and evidence. |
| `Petstore Test Suite Hanaa.postman_collection.json` | Postman requests and test scripts. |
| `Petstore Environment.postman_environment.json` | Environment variables. |
| `Newman-Full-Report.html` | Full collection execution report. |

## How to Run

1. Open Postman and select **Import**.
2. Import the Collection JSON and Environment JSON.
3. Select the imported Petstore environment.
4. Run the required collection folders or individual requests.
5. Alternatively, use Newman to execute the full collection and generate an HTML report.

> Use only dummy credentials and non-sensitive environment values. Some requests create, update, or delete test data.

## Detailed Results

Refer to the Excel workbook for case-level expected and actual results, pass/fail status, findings, cleanup notes, and supporting screenshot references.

---

*Prepared for API Testing training and practice.*
