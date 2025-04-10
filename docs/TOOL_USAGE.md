# 🧰 TOOL_USAGE.md – Word to JSON Converter

This guide explains how to use the Word to JSON converter tool that helps you update the AWS Quiz App with questions from a Word document.

---

## 📄 What the Tool Does

This is a browser-based drag-and-drop tool that converts `.docx` Word files into a `questions.json` file, which is used by the quiz app.

It:
- Detects questions and answer options
- Identifies correct answers marked as **Correct**
- Removes “Question #1” and similar labels
- Provides a live preview
- Lets you download the output instantly

---

## 🧭 How to Use the Tool

1. Open `word_to_json_converter.html` in any browser
2. Drag and drop your `.docx` file with AWS questions
3. Wait for the preview to appear
4. Click **Download JSON**
5. Save the downloaded file as `questions.json`

---

## 🔁 How to Update the Quiz

Once you have the `questions.json` file:

1. Go to your GitHub repo
2. Click “Add file → Upload files”
3. Upload the new `questions.json`
4. Commit the change
5. Refresh your quiz page (Ctrl+Shift+R)

---

## 📁 Where the Tool Lives

The HTML converter file is located in:

tools/word_to_json_converter.html


You can reuse this tool as many times as you like!

---

## 🛠️ Coming Soon

- Excel to JSON converter
- Tag/category support
