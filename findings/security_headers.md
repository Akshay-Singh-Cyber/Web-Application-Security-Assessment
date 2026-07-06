# Security Headers

## Overview

HTTP Security Headers provide an additional layer of protection for web applications by instructing browsers how to handle website content securely. Properly configured security headers help mitigate several common attacks, including Cross-Site Scripting (XSS), Clickjacking, MIME-type confusion, and information leakage.

---

# Common Security Headers

## 1. Content-Security-Policy (CSP)

### Purpose

Restricts the sources from which a browser can load scripts, styles, images, fonts, and other resources.

### Why it is Important

A properly configured CSP significantly reduces the risk of:

- Cross-Site Scripting (XSS)
- Malicious JavaScript injection
- Unauthorized third-party resource loading

### Example

```http
Content-Security-Policy:
default-src 'self';
script-src 'self';
object-src 'none';
frame-ancestors 'none';
```

---

## 2. X-Frame-Options

### Purpose

Protects web applications against Clickjacking attacks.

### Recommended Value

```http
X-Frame-Options: SAMEORIGIN
```

or

```http
X-Frame-Options: DENY
```

---

## 3. X-Content-Type-Options

### Purpose

Prevents browsers from MIME-sniffing files and executing them as different content types.

### Recommended Value

```http
X-Content-Type-Options: nosniff
```

---

## 4. Referrer-Policy

### Purpose

Controls how much referrer information is shared when navigating between websites.

### Recommended Value

```http
Referrer-Policy: strict-origin-when-cross-origin
```

---

## 5. Permissions-Policy

### Purpose

Restricts access to sensitive browser features.

Examples include:

- Camera
- Microphone
- Geolocation
- USB
- Fullscreen

### Example

```http
Permissions-Policy:
camera=(),
microphone=(),
geolocation=()
```

---

# Why Security Headers Matter

Properly configured security headers:

- Reduce client-side attack surface
- Improve browser security
- Protect user privacy
- Reduce XSS risks
- Prevent Clickjacking
- Improve compliance with security best practices

---

# Best Practices

- Implement all recommended security headers.
- Regularly verify headers using automated security scanners.
- Review header policies after application updates.
- Validate browser compatibility before deployment.
