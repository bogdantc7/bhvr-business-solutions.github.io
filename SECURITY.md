# Security Policy

## Reporting Security Issues

The security of this application is a top priority. If you discover or suspect a security vulnerability, please report it responsibly.

### How to Report a Vulnerability

- **Do NOT create a public GitHub issue** for security vulnerabilities.
- Report security issues by contacting the repository maintainers directly or submitting a draft security advisory via GitHub Security Advisories.
- Include detailed information to assist in reproducing and addressing the issue:
  - Type of vulnerability
  - Step-by-step instructions to reproduce
  - Potential impact if exploited
  - Any proof-of-concept code or screenshots (if applicable)

### Response Timeline

- **Acknowledgment:** Within 48 hours of receiving a report.
- **Assessment & Fix:** We aim to evaluate and provide an initial patch or mitigation strategy within 5–7 business days.
- **Disclosure:** Public details will be released only after a patch is made available.

## Supported Versions

Only the latest release / primary branch (`main` / default branch) receives security updates.

## Preferred Security Practices

- **Principle of Least Privilege:** Do not commit secrets, API keys, credentials, or private certificates.
- **Input Validation:** Sanitize and validate all external input.
- **Dependency Management:** Maintain dependencies up to date and audit regularly for known CVEs.
