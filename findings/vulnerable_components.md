# Vulnerable and Outdated Components

## Overview

Modern web applications rely heavily on third-party libraries, frameworks, plugins, and software packages. While these components accelerate development, they can also introduce security risks if they are outdated or contain publicly disclosed vulnerabilities.

The OWASP Top 10 (2021) identifies the use of vulnerable and outdated components as **A06:2021** because attackers frequently exploit known vulnerabilities in software that has not been updated.

---

# Common Vulnerable Components

Examples include:

- JavaScript Libraries
- Web Frameworks
- Content Management Systems (CMS)
- Database Servers
- Web Servers
- Programming Language Runtime
- Open Source Dependencies

---

# Why Outdated Components are Dangerous

Using outdated software can lead to:

- Remote Code Execution (RCE)
- Cross-Site Scripting (XSS)
- SQL Injection
- Privilege Escalation
- Information Disclosure
- Authentication Bypass
- Denial of Service (DoS)

Attackers actively search for publicly known vulnerabilities (CVEs) affecting outdated software versions.

---

# Common Examples

Examples of software that require regular updates include:

- Bootstrap
- jQuery
- Angular
- React
- Apache HTTP Server
- Nginx
- PHP
- Node.js
- Apache Tomcat

Keeping these components updated reduces exposure to publicly known security issues.

---

# CVE (Common Vulnerabilities and Exposures)

A **CVE** is a publicly disclosed security vulnerability assigned a unique identifier.

Example format:

```text
CVE-2025-12345
```

CVE identifiers help organizations:

- Track vulnerabilities
- Prioritize patching
- Monitor security advisories
- Improve vulnerability management

---

# CVSS (Common Vulnerability Scoring System)

CVSS is an industry-standard framework used to measure the severity of security vulnerabilities.

Typical severity ratings:

| Score | Severity |
|--------|----------|
| 0.0 | None |
| 0.1 – 3.9 | Low |
| 4.0 – 6.9 | Medium |
| 7.0 – 8.9 | High |
| 9.0 – 10.0 | Critical |

---

# Best Practices

To reduce the risk of vulnerable components:

- Maintain an inventory of software components.
- Regularly update third-party libraries.
- Remove unused dependencies.
- Subscribe to vendor security advisories.
- Monitor newly published CVEs.
- Verify software integrity before deployment.

---

# Useful Tools

Examples of tools used to identify vulnerable components include:

- OWASP Dependency-Check
- Trivy
- Snyk
- npm audit
- GitHub Dependabot
- Maven Dependency Check

---

# References

- OWASP Top 10 (2021)
- National Vulnerability Database (NVD)
- Common Vulnerabilities and Exposures (CVE)
- Common Vulnerability Scoring System (CVSS)
