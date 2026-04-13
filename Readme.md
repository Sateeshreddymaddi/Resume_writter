# 🚀 ResumeIQ — AI Resume Tailor

## 📌 Overview

**ResumeIQ** is an AI-powered resume tailoring system that transforms a candidate’s resume into a highly optimized, job-specific version designed to pass Applicant Tracking Systems (ATS).

The system automates the entire process — from resume analysis to PDF generation — and delivers a professional, tailored resume directly to the user’s email.

---

## ⚡ Key Features

* ✨ AI-powered resume rewriting
* 🎯 Job-description-based optimization
* 📄 Automatic LaTeX resume generation
* 📧 Email delivery with premium template
* ⚡ Fully automated pipeline using n8n
* 📊 ATS-friendly structured formatting

---

## 🧠 System Workflow

```text
User Uploads Resume + Job Description
            ↓
Webhook Trigger (n8n)
            ↓
Resume Text Extraction (PDF)
            ↓
AI Processing (Groq LLM)
            ↓
Generate ATS-Optimized LaTeX Resume
            ↓
Convert LaTeX → PDF
            ↓
Send Email with Resume Attachment
```

---

## 🖥️ Frontend

The frontend provides a clean and minimal interface for users to:

* Enter personal details (Name, Email)
* Upload resume (PDF/DOC)
* Paste job description
* Submit request for AI processing

### Highlights

* Modern UI with smooth animations
* File upload with validation
* Real-time feedback and loading states

---

## 🔗 Backend Automation (n8n)

The backend is fully automated using n8n workflows:

### Core Components

* **Webhook Node** → Receives user input
* **File Extractor** → Extracts text from resume
* **AI Agent** → Rewrites resume using Groq LLM
* **Code Node** → Cleans and prepares LaTeX
* **HTTP Node** → Converts LaTeX into PDF
* **Gmail Node** → Sends final resume to user

---

## 🧩 Tech Stack

### Frontend

* HTML5
* CSS3 (Custom UI Design)
* JavaScript (Vanilla)

### Backend & Automation

* n8n
* Groq API (LLM)
* LaTeX Compiler API
* Gmail API

---

## 🎯 Use Cases

* Students and freshers applying for jobs
* Developers targeting specific roles
* Resume optimization for ATS systems
* Internship applications

---

## 🚀 Future Enhancements

* Resume scoring dashboard
* Multi-role resume versions
* LinkedIn auto-apply integration
* Analytics for ATS performance
* Multi-language support

---

## 👨‍💻 Author

**Sateesh Reddy Maddi**
Full-Stack Developer & Automation Engineer

* 🌐 Portfolio: [https://sateeshreddy-portfolio.vercel.app](https://sateeshreddy-portfolio.vercel.app)
* 💼 LinkedIn: [https://linkedin.com/in/sateeshreddymaddi](https://linkedin.com/in/sateeshreddymaddi)
* 🐙 GitHub: [https://github.com/Sateeshreddymaddi](https://github.com/Sateeshreddymaddi)

---

## 🏁 Conclusion

ResumeIQ simplifies and automates resume optimization by combining AI and workflow automation — helping users create job-ready, ATS-optimized resumes in seconds.
