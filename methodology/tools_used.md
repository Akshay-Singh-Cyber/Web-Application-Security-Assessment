# Tools Used

This document provides an overview of the tools used during the web application security assessment and their role in the testing process.

---

# 1. Burp Suite

**Purpose**

Burp Suite was the primary tool used for manual web application security testing.

**Typical Usage**

- Intercepting HTTP/HTTPS requests
- Inspecting request and response headers
- Modifying parameters
- Testing input validation
- Manual vulnerability verification

---

# 2. Nmap

**Purpose**

Nmap was used for network reconnaissance and service discovery.

**Typical Usage**

- Host discovery
- Port scanning
- Service version detection
- NSE script execution
- Basic vulnerability checks

---

# 3. Nikto

**Purpose**

Nikto is a web server scanner used to identify common security issues.

**Typical Usage**

- Detecting missing security headers
- Identifying outdated software
- Finding default files
- Detecting server misconfigurations

---

# 4. Gobuster

**Purpose**

Gobuster was used for content discovery.

**Typical Usage**

- Directory enumeration
- File discovery
- Hidden endpoint identification

---

# 5. SQLMap

**Purpose**

SQLMap is an automated SQL Injection testing tool.

**Typical Usage**

- Safe validation of potential SQL injection points
- Database fingerprinting (when authorized)
- Verification of manually identified injection vectors

> Note: SQLMap should only be used against systems where explicit authorization has been granted.

---

# 6. Qualys SSL Labs

**Purpose**

Qualys SSL Labs was used to evaluate HTTPS configuration.

**Typical Usage**

- TLS protocol analysis
- Cipher suite evaluation
- Certificate validation
- HTTPS security grading

---

# 7. Browser Developer Tools

**Purpose**

Modern browser developer tools were used to inspect client-side behavior.

**Typical Usage**

- HTTP header inspection
- Cookie analysis
- JavaScript debugging
- DOM inspection
- Network traffic analysis

---

# Summary

| Tool | Primary Purpose |
|------|------------------|
| Burp Suite | Manual Web Application Testing |
| Nmap | Network Reconnaissance |
| Nikto | Web Server Security Analysis |
| Gobuster | Directory Enumeration |
| SQLMap | SQL Injection Validation |
| Qualys SSL Labs | SSL/TLS Configuration Analysis |
| Browser Developer Tools | Client-side Inspection |
