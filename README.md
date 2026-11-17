# Advanced ITT Exam Portal

**Live Exam Portal for ICAI Advanced ITT (AICITSS - Advanced Information Technology)**

🔗 **[Open Exam Portal](https://YOUR-USERNAME.github.io/advanced-itt-exam/)**

---

## 📖 About

An interactive digital examination portal for ICAI CA students preparing for the **Advanced Integrated Course on Information Technology and Soft Skills (AICITSS) – Advanced IT** examination.

### Features
- ✅ 700+ MCQ questions from official ICAI materials
- 🏆 Chapter-wise practice (9 chapters)
- ⏱ Countdown timer with auto-submit
- 🗂 Question palette with status indicators
- 💾 Auto-save progress (localStorage)
- 📊 Detailed results with model answers
- 📱 Mobile responsive

### Chapters Covered
- Forensic Accounting and Fraud Detection
- Digital Forensics and Cyber Security
- Robotic Process Automation (RPA)
- ERP - Oracle Fusion
- ERP - Microsoft Dynamics 365
- Data Analytics - Power BI
- Data Analytics - Python
- Data Analytics - KNIME
- Database Applications - MS Access

---

## 🚀 Usage

### Open Locally
Just open `index.html` (or `exam_portal.html`) in any modern browser — no server needed.

### Import Questions
1. Open the portal
2. Click **"Import Questions JSON"** on the home screen
3. Select `questions_bank.json`

### Add More Questions
1. Prepare a JSON file in the same format as `questions_bank.json`
2. Use the **"Add Questions"** screen in the portal
3. Questions are deduplicated automatically

---

## 💾 Backup & Restore

Your exam progress is saved in **browser localStorage** — it is device and browser specific.

**Export backup:** Home screen → "Export Progress" → saves `exam_history.json`  
**Restore backup:** Home screen → "Import Progress" → select your `exam_history.json`

> ⚠️ Clearing browser data or switching browsers will erase local progress. Export regularly.

---

## 📂 Files

| File | Description |
|------|-------------|
| `index.html` | Main exam portal (single-file app) |
| `questions_bank.json` | Question bank (700+ questions) |
| `README.md` | This file |

---

## ⚠️ Disclaimer

AI-generated evaluations for descriptive questions are **indicative only** and do not represent official ICAI marking. For official evaluation, refer to ICAI answer keys.

---

*Built for ICAI CA students. Not affiliated with ICAI.*
