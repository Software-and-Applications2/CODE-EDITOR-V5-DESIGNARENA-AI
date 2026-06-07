# Security Policy

## Supported Versions

| Version | Supported |
| ------- | --------- |
| 5.x     | Yes       |
| < 5.0   | No        |

## Reporting a Vulnerability

This is an experimental, open-source project. If you discover a security vulnerability, please report it responsibly:

1. **Do not open a public GitHub issue** for security vulnerabilities.
2. Use [GitHub Private Vulnerability Reporting](https://github.com/Software-and-Applications2/CODE-EDITOR-V5-DESIGNARENA-AI/security/advisories/new) to submit a report privately.
3. Include:
   - A clear description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if any)

## Response Timeline

- Acknowledgement within **72 hours**
- Assessment and triage within **7 days**
- Fix or mitigation within **30 days** for confirmed vulnerabilities

## Scope

This project is a **client-side only** React/Vite application. The primary attack surface includes:

- Third-party npm dependencies (see Dependabot alerts)
- The `react-router-dom` routing layer
- Browser storage (`localStorage`) usage in the code editor session history

## Known Issues

Please review [Dependabot alerts](https://github.com/Software-and-Applications2/CODE-EDITOR-V5-DESIGNARENA-AI/security/dependabot) for the current list of known dependency vulnerabilities.

## Disclosure Policy

We follow a coordinated disclosure model. Once a fix is confirmed and released, the vulnerability will be publicly disclosed via a GitHub Security Advisory.
