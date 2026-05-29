# Vulnerability Assessment Report — demo.testfire.net

## Overview
This repository contains a passive, read-only vulnerability assessment 
conducted on demo.testfire.net as part of a cybersecurity internship 
project.

The goal was to identify common security weaknesses on a public-facing 
website and present findings in a professional, business-ready report.

---

## Target Website
- **URL:** https://demo.testfire.net
- **IP Address:** 65.61.137.117
- **Type:** Intentionally vulnerable demo site (IBM AltoroMutual)
- **Assessment Date:** 21 May 2026

---

## Scope

### What Was Tested
- HTTP response headers
- SSL/TLS certificate configuration
- Cookie security flags
- Server information disclosure
- Missing security headers

### What Was NOT Tested
- No login bypass
- No brute force attacks
- No exploitation of any kind
- No denial-of-service
- No automated attack tools

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Chrome DevTools | Response header and cookie inspection |
| securityheaders.com | Security header analysis |
| Qualys SSL Labs | SSL/TLS certificate strength |
| MDN HTTP Observatory | Overall security scoring |
| OWASP ZAP (Safe Mode) | Passive traffic observation |

-------------------------------------------------------------

## Author
**Anay Nayak**
