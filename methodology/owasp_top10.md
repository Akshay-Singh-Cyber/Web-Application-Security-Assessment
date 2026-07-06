# OWASP Top 10 (2021)

## Overview

The **OWASP Top 10** is a widely recognized awareness document published by the Open Worldwide Application Security Project (OWASP). It identifies the most critical security risks affecting modern web applications and serves as a foundation for secure software development and security assessments.

This assessment followed the OWASP Top 10 (2021) methodology to evaluate common web application security risks.

---

# OWASP Top 10 Categories

## A01:2021 – Broken Access Control

Broken access control occurs when users can access resources or perform actions beyond their intended permissions.

### Examples

- Insecure Direct Object Reference (IDOR)
- Forced Browsing
- Privilege Escalation

### Typical Tests

- Role-based access verification
- URL manipulation
- Resource authorization testing

---

## A02:2021 – Cryptographic Failures

Cryptographic failures occur when sensitive information is not adequately protected during storage or transmission.

### Examples

- Weak TLS configuration
- Weak cipher suites
- Sensitive data exposure
- Insecure certificate configuration

### Typical Tests

- TLS protocol analysis
- Cipher suite evaluation
- Certificate validation

---

## A03:2021 – Injection

Injection vulnerabilities occur when untrusted user input is interpreted as commands or queries.

### Examples

- SQL Injection
- Command Injection
- LDAP Injection

### Typical Tests

- Input validation testing
- Parameter manipulation
- Automated and manual verification

---

## A04:2021 – Insecure Design

Security weaknesses resulting from poor application design rather than implementation mistakes.

### Examples

- Missing rate limiting
- Poor business logic
- Weak security architecture

### Typical Tests

- Business logic review
- Workflow analysis
- Authentication flow evaluation

---

## A05:2021 – Security Misconfiguration

Improper configuration of servers, frameworks, or security controls.

### Examples

- Missing security headers
- Directory listing enabled
- Default configurations
- Verbose error messages

### Typical Tests

- HTTP header inspection
- Configuration review
- Automated scanning

---

## A06:2021 – Vulnerable and Outdated Components

Applications using outdated software or libraries with known security issues.

### Examples

- Legacy JavaScript libraries
- Outdated frameworks
- Unsupported software

### Typical Tests

- Version identification
- Component analysis
- CVE verification

---

## A07:2021 – Identification and Authentication Failures

Weak authentication mechanisms allowing unauthorized access.

### Examples

- Weak password policies
- Session fixation
- Broken authentication

### Typical Tests

- Session management review
- Authentication workflow testing

---

## A08:2021 – Software and Data Integrity Failures

Failures involving software updates, code integrity, or insecure deserialization.

### Examples

- Insecure update mechanisms
- Unsigned software packages
- Unsafe deserialization

### Typical Tests

- Update process review
- Dependency validation

---

## A09:2021 – Security Logging and Monitoring Failures

Insufficient logging or monitoring that delays detection of security incidents.

### Examples

- Missing audit logs
- Lack of intrusion monitoring
- Poor alerting mechanisms

### Typical Tests

- Logging verification
- Audit trail review

---

## A10:2021 – Server-Side Request Forgery (SSRF)

Occurs when a server fetches remote resources based on user-controlled input.

### Examples

- Internal resource access
- Cloud metadata exposure

### Typical Tests

- URL parameter testing
- Internal network access validation

---

# Why OWASP Top 10?

The OWASP Top 10 provides a structured approach for identifying and mitigating common web application security risks. It is widely used by security professionals, penetration testers, developers, and organizations to improve application security throughout the software development lifecycle.

---

# References

- OWASP Top 10 (2021)
- OWASP Web Security Testing Guide (WSTG)
- OWASP Application Security Verification Standard (ASVS)
