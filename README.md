# FUTURE_CS_01 — Vulnerability Assessment Report for a Live Website

**Internship:** Future Interns — Cyber Security Track
**Task:** 1 of 3

## 📌 Objective
Perform a vulnerability assessment of a web application, classify identified risks, explain them in
business-friendly language, and provide clear remediation guidance.

## 🎯 Target
[OWASP Juice Shop](https://owasp-juice.shop/) — an intentionally vulnerable demo application built by
OWASP specifically for security training. Using a designated training target keeps this task safe and
legal (never scan a live production site without written authorization).

## 🛠️ Tools Used
- **Nmap** — service/port reconnaissance
- **OWASP ZAP** (passive scan) — automated header & information-disclosure checks
- **Browser DevTools** — manual request/response inspection
- **Microsoft Word / Canva** — report design

## ✅ Key Features Delivered
- Identification of common web vulnerabilities
- Risk classification (Low / Medium / High)
- Plain-language business impact explanation for each finding
- Clear, actionable remediation steps

## 📊 Summary of Findings

| ID | Finding | Risk |
|----|---------|------|
| V-01 | Broken Object Level Authorization (IDOR) on basket/order endpoints | 🔴 High |
| V-02 | Missing critical HTTP security headers (CSP, X-Frame-Options, HSTS) | 🟠 Medium |
| V-03 | No rate limiting / account lockout on login | 🟠 Medium |
| V-04 | Outdated component version disclosed in response headers | 🟠 Medium |
| V-05 | Verbose error messages reveal stack traces | 🟢 Low |
| V-06 | Weak password policy | 🟢 Low |

Full details, business-impact write-ups, and remediation guidance are in the report.

## 📄 Deliverable
[`Vulnerability_Assessment_Report.docx`](./Vulnerability_Assessment_Report.docx)

## 📁 Repository Structure
```
FUTURE_CS_01/
├── README.md
└── Vulnerability_Assessment_Report.docx
```

## 👤 Author
Cyber Security Intern — Future Interns
[LinkedIn](https://www.linkedin.com/company/future-interns/) | contact@futureinterns.com
