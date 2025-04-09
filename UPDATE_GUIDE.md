# 📘 UPDATE_GUIDE.md – How to Update the AWS Quiz App

This guide explains how to update your AWS Solutions Architect Associate quiz app using your Word file of questions and answers.

---

## 🛠 Prerequisites

- A `.docx` file with AWS exam-style questions  
- Each option marked with “Correct” (for the right answers)  
- Your GitHub repository with the quiz already hosted via GitHub Pages  

---

## 🔁 Update Process (Start to Finish)

### Step 1: Prepare Your Word File

Ensure your file is formatted like this:

Question #1. What is Amazon S3?
A. Object storage Correct
B. Relational database
C. Monitoring service
D. CDN

Question #2. Which AWS services can host containers?
A. Amazon ECS Correct
B. AWS Lambda
C. Amazon EKS Correct
D. Amazon RDS

---

### Step 2: Convert Word File to `questions.json`

1. Open the **Word to JSON Converter** (HTML tool you downloaded)
2. Drag and drop your `.docx` file into the window
3. It will extract all questions and show them in JSON format
4. Click **Download JSON**

✅ This file is now ready for your quiz app.

---

### Step 3: Update Your GitHub Repository

1. Go to your GitHub repo (e.g., `aws-quiz-app-sa-associate`)
2. Click **“Add file” → “Upload files”**
3. Upload the new `questions.json` and overwrite the old one
4. Click **Commit changes**

---

### Step 4: Verify It Works

1. Open your GitHub Pages link (e.g., `https://yourusername.github.io/aws-quiz-app-sa-associate`)
2. Refresh the page (Ctrl + Shift + R or open in Incognito)
3. Confirm your updated questions appear in the quiz

---

## 🧼 Tips

- Always keep a backup of your original Word file
- Use a consistent option format (A. / B. / C. / D.)
- You can re-use the converter tool as many times as needed

---

**Maintainer:** You  
**Last Updated:** April 2025
