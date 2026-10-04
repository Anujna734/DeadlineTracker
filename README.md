# DeadlineTracker
# 📅 DueSnap — Smart Deadline & Schedule Tracker

DueSnap is an AI-powered Streamlit web application that extracts deadlines, schedules, and deliverables directly from photos of syllabi, timetables, or assignment sheets. Powered by **Google Gemini (gemini-3.5-flash)**, it processes messy visual data into structured task lists and delivers a chronological digest directly to your email inbox via **Gmail SMTP**.

---

## ✨ Features

- 📸 **Visual Date Extraction:** Snap a picture of a syllabus, assignment sheet, or timetable—Gemini extracts all key dates, tasks, and deadlines automatically.
- 💬 **Interactive Task Assistant:** Ask questions about your schedule or manually type in additional tasks.
- 📧 **Direct Email Digests:** Send a clean, organized deadline summary straight to your email inbox using free Gmail SMTP integration.
- 🛡️ **Graceful Handling:** Built-in error management for blurry, incomplete, or non-schedule images.

---

## 🚀 Tech Stack

- **Frontend/UI:** Streamlit
- **LLM Engine:** Google Gemini API (`gemini-3.5-flash`)
- **Email Delivery:** Python `smtplib` + MIME (Gmail SMTP)
- **Environment Management:** Python `venv`

---


```bash
git clone [https://github.com/Anujna734/DeadlineTracker.git](https://github.com/Anujna734/DeadlineTracker.git)
cd DeadlineTracker
