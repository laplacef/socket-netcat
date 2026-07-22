# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| latest  | Yes       |

Only the latest release receives security patches.

## Reporting a Vulnerability

**Do not open a public GitHub issue for security vulnerabilities.**

To report a vulnerability, use [GitHub's private vulnerability reporting](https://github.com/laplacef/socket-netcat/security/advisories/new). You can expect an initial response within 72 hours.

Please include:
- A description of the vulnerability
- Steps to reproduce the issue
- Potential impact assessment

## Scope

The following are considered security issues:
- Unintended command execution or shell access beyond the documented interface
- Binding to interfaces broader than the caller requested
- Dependency vulnerabilities in direct dependencies

## Out of Scope

The following are **not** security issues:
- The tool performing its documented networking functions, which mirror netcat
- Use of the tool against hosts the operator is not authorized to access
- Vulnerabilities in the services being connected to
