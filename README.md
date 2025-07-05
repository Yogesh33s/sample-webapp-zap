# 🔒 Secure DevOps Task – OWASP ZAP Integration  
**Internship Task 4 – CodTech**

This project demonstrates how to integrate **OWASP ZAP**, an open-source security scanner, into a GitHub Actions-based **CI/CD pipeline** to identify vulnerabilities in a deployed web application.

---

## 🚀 Project Overview

- **Deployed App:**  
  [Live on Vercel](https://sample-webapp-acixn1pzb-yogeshs-projects-58fc2360.vercel.app)

- **Security Tool Used:**  
  [OWASP ZAP](https://www.zaproxy.org/)

- **CI/CD Platform:**  
  [GitHub Actions](https://docs.github.com/en/actions)

- **Scan Target:**  
  The deployed website hosted on Vercel.

---

## 📂 Repo Structure

.github/
└── workflows/
└── owasp-zap-scan.yml # GitHub Actions workflow for ZAP scan

index.html # Sample frontend file
vercel.json # Configuration for Vercel hosting
README.md # This file


---

## ⚙️ Workflow Summary

This GitHub Actions pipeline:
- Triggers manually or on push to `main`
- Launches OWASP ZAP in a Docker container
- Scans the deployed Vercel app
- Uploads a detailed vulnerability report

---

## 📄 Vulnerability Report

- The report is auto-generated as:
  - `report_html.html` (viewable in browser)
  - `report_md.md` (Markdown summary)
  - `report_json.json` (machine-readable)

- Downloadable under GitHub Actions → Artifacts → `zap-report`

- ✅ **Result Summary:**
  - ⚠️ Warnings: 7
  - ❌ Critical Issues: 0
  - ✅ Passed Checks: 64

---

## 👤 Submitted By

**Name:** Yogesh  
**Internship Company:** CodTech  
**Task:** Secure DevOps – CI/CD Security Scanning with OWASP ZAP  
**Repo:** [GitHub - sample-webapp-zap](https://github.com/Yogesh33s/sample-webapp-zap)

---



