
# Vulnerability Assessment Report (Read-Only)

## Project Overview
This repository contains a **Vulnerability Assessment Report** conducted on a publicly accessible website as part of **Cyber Security Task 1 (2026)** by **Future Interns**.  
The assessment was performed using **passive, non-intrusive techniques** to evaluate the security posture of the target website and provide business-friendly security recommendations.

This project focuses on **security consulting and risk assessment**, not exploitation or hacking.

---

## Target Website
- **URL:** http://testphp.vulnweb.com
- **Assessment Type:** Read-Only / Passive Vulnerability Assessment

---

## Scope of Assessment
**In Scope:**
- Public-facing web pages
- HTTP response headers
- Basic service exposure analysis
- Client-side behavior (passive)

**Out of Scope:**
- Authentication or authorization testing
- Exploitation of vulnerabilities
- Brute-force or denial-of-service attacks
- Access to restricted or administrative areas

---

## Tools Used
- **OWASP ZAP (Passive Scan)** – Identification of web security misconfigurations
- **Nmap** – Basic port and service version detection
- **Browser Developer Tools** – Manual inspection of headers and cookies
- **Canva** – Professional report design

---

## Key Findings Summary
- Missing HTTP security headers (CSP, X-Frame-Options, X-Content-Type-Options)
- Absence of Anti-CSRF protection
- Server and technology information disclosure
- Charset mismatch configuration issue

**Risk Levels Identified:**
- Medium Risk: Configuration weaknesses increasing attack surface
- Low Risk: Information disclosure and best-practice gaps

No critical or high-risk vulnerabilities were identified during this assessment.

---

## Report Deliverables
- 📄 **Vulnerability Assessment Report (PDF)**
- 🖼️ Supporting evidence (screenshots and tool outputs)
- 📘 This README explaining scope, tools, and methodology

---

## Methodology
1. Defined scope and ethical boundaries
2. Performed passive analysis using approved tools
3. Identified and classified security findings
4. Assessed business impact of each issue
5. Provided clear, actionable remediation recommendations
6. Compiled findings into a professional audit report

---

## Disclaimer
This assessment was conducted strictly for **educational purposes** under an ethical, read-only scope.  
No exploitation or harmful actions were performed.  
Findings reflect the security posture of the target website **at the time of testing only**.

---

## Author
**Harry**  
Cybersecurity Intern  
Future Interns

---

## Acknowledgement
Special thanks to **Future Interns** for providing structured, ethical cybersecurity learning opportunities.
