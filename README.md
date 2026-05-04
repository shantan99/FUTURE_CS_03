# FUTURE_CS_03
API Security Risk Analysis Report — tested JSONPlaceholder REST API using Postman, identifying 4 high-risk vulnerabilities including broken authentication, unauthorized data access, and missing security headers. Completed as part of the Future Interns Cyber Security Internship (FUTURE_CS_03).
# FUTURE_CS_03 — API Security Risk Analysis

## Internship Details
- **Name:** Shantan Narayndas
- **CIN:** FIT/APR26/CS8031
- **Track:** FUTURE_CS_03
- **Task:** API Security Risk Analysis

## Task Overview
Performed a manual API security assessment on the JSONPlaceholder REST API using Postman API Client to identify common security vulnerabilities based on the OWASP API Security Top 10.

## Tool Used
- **Postman** — API testing and security analysis

## API Tested
- **JSONPlaceholder REST API** — https://jsonplaceholder.typicode.com

## Tests Performed
| # | Test | Method | Result |
|---|------|--------|--------|
| 1 | Unauthenticated Data Access | GET /users | VULNERABLE |
| 2 | Missing Security Headers | GET /users | VULNERABLE |
| 3 | Unauthorized Data Creation | POST /posts | VULNERABLE |
| 4 | Unauthorized Data Deletion | DELETE /posts/1 | VULNERABLE |
| 5 | Error Handling Check | GET /users/9999 | WEAK |
| 6 | HTTP vs HTTPS Enforcement | GET /users (HTTP) | VULNERABLE |

## Risk Summary
- 🔴 High Risk: 4
- 🟠 Medium Risk: 1
- 🟡 Low Risk: 1
- Total Tests: 6

## Deliverable
- `FUTURE_CS_03_API_Security_Report.pdf` — Full security assessment report

## Disclaimer
This assessment was performed on a public test API designed for educational purposes. No real user data was accessed or harmed.
