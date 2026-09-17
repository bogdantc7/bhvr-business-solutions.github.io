# Sentinel's Journal

Critical learnings and security guidelines for this project.

## 2026-09-17 - Repository Security Baseline
**Vulnerability:** Unprotected workspace without `.gitignore` risking credential and sensitive artifact leaks.
**Learning:** Empty or newly initialized repositories lack default git ignore rules, making accidental commits of `.env` files or certificates a primary risk.
**Prevention:** Establish a strict `.gitignore` baseline blocking secrets, environment variables, keys, and credentials early in the project lifecycle.
