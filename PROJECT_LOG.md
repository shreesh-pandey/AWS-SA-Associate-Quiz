# 📘 Project: AWS Quiz App – SA Associate  
**Status:** ✅ Live and functional — hosted on GitHub Pages

---

## 🏁 Project Start  
**Goal:** Build a quiz app to practice questions from the AWS Certified Solutions Architect – Associate exam using a Word file of Q&A.

---

## 🔹 Phase 1: Project Idea & Planning  
**✅ Key Actions:**
- User wanted to attempt AWS exam questions in test format, repeatedly.
- We discussed 3 options:
  - Chat-based testing
  - Spreadsheet grading
  - **Web-based quiz app** ✅ *(chosen)*
- Agreed to build a browser-based quiz that reads from a Q&A file.

---

## 🔹 Phase 2: Upload & Parsing Word File  
**✅ Key Actions:**
- User uploaded a `.docx` file with 20+ AWS practice questions.
- I parsed and extracted:
  - Question text
  - Answer options
  - Correct answer(s) marked as “Correct”

---

## 🔹 Phase 3: Web App Build (MVP)
**✅ Features Built:**
- One question at a time
- Instant feedback
- Supports multiple-answer questions
- Final score display
- Shuffling and retry options

**🎁 Delivered:**
- `index.html` file
- Fully self-contained and reusable

---

## 🔹 Phase 4: Deployment on GitHub Pages  
**✅ User Completed:**
- Created GitHub account
- Created repository
- Uploaded files
- Enabled GitHub Pages
- **✅ Quiz now live on the web!**

---

## 🔹 Phase 5: Dynamic Question Loading  
**Problem Solved:** User wanted to update questions without touching code  
**✅ Added:**
- `questions.json` file for question storage
- Quiz app modified to load from JSON
- Provided downloadable zip with both files:
  - `index.html`
  - `questions.json`

---

## 🔹 Phase 6: Word & Excel Integration (In Progress)
**User’s Workflow:**
- Keeps questions in a Word file
- Wants to convert to JSON easily

**Planned:**
- Word to JSON parser (automated)
- Excel to JSON converter (drag-and-drop tool)

**Issue:** Tools temporarily down — will resume when back up

---

## 🔹 Phase 7: Documentation
**✅ Created:**
- Polished project documentation (in ChatGPT canvas)
- README.md for GitHub (rewritten professionally)
- Project naming convention:
  - `Project: [Platform/Tool] [App Type] – [Goal]`
  - Current: `Project: AWS Quiz App – SA Associate`

---

## 📌 Current Status Summary

| Area              | Status  | Notes                                   |
|-------------------|---------|-----------------------------------------|
| Quiz app frontend | ✅ Done | Hosted on GitHub Pages                  |
| JSON integration  | ✅ Done | Easy question updates via JSON          |
| Word support      | 🕒 Pending | Will auto-convert to JSON soon        |
| Excel converter   | 🕒 Pending | HTML drag & drop tool in progress     |
| Documentation     | ✅ Done | Project doc + README created            |
| Hosting           | ✅ Done | Accessible online                       |

---

## ✅ Next Steps (Optional/Future)

- Finish and connect Excel + Word converters
- Add tag/category filters to quiz
- Introduce score saving (local or cloud)
- Polish UI for mobile view
- Add user-friendly editor for non-coders
