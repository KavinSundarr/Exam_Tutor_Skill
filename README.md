# 🎓 Claude Exam Tutor Skill

> A structured, self-contained AI tutoring skill file for university exam preparation — powered by Claude. Paste it. Study. Update it. Repeat.

---

## 📌 What Is This?

This repository contains **`EXAM_TUTOR_SKILL.md`** — a single Markdown file that transforms Claude (Anthropic's AI assistant) into a fully structured, personalised university exam tutor with built-in progress tracking, MCQ practice, session continuity, and automatic end-of-session updates.

No plugins. No complex setup. Just one file, pasted into Claude, and you are ready to study.

---

## 🎯 Purpose

Built specifically for postgraduate university exam preparation across 4 modules:

| Module Code | Module Name | Duration |
|---|---|---|
| COMP63502 | Data Engineering Technologies | 12 Weeks |
| COMP64602 | Advanced Topics in Knowledge Representation and Reasoning | 12 Weeks |
| COMP64702 | Transforming Text Into Meaning | 10 Weeks |
| COMP64802 | Advanced Topics in Machine Learning | 10 Weeks |

**Exam Format:** MCQ (Multiple Choice Questions)

---

## ✨ Features

### 🧠 Intelligent Tutoring
- Teaches every concept using a structured **4-step framework**: Simple Explanation → Deep Explanation → Real-World Example → Exam Angle
- Always grounds explanations in your **uploaded lecture material** (PPTs and PDFs)
- Flags the **top 5 most exam-relevant concepts** every time new material is uploaded

### 🧪 MCQ Practice & Testing
- Generates MCQ questions directly from your lecture slides
- Each question includes 4 options with 1 correct answer and 3 realistic distractors
- After every answer, Claude explains why the correct answer is right and why each wrong option is incorrect
- Re-tests you on any concept you got wrong before moving on

### 🔄 Session Continuity
- Works across multiple sessions even though Claude has no built-in memory between conversations
- At the start of every session, Claude reads the tracker and resumes exactly where you left off
- Handles mid-session subject switching seamlessly — always recaps before transitioning

### 📊 Progress Tracking
- Tracks progress week by week across all 4 subjects
- Maintains a live log of: weeks uploaded, weeks studied, weak areas, key exam concepts, and MCQ scores
- Provides a periodic progress snapshot every 3–4 topics

### 🔚 Automatic End-of-Session Updates
- Type **"Update today's progress"** at the end of any session
- Claude automatically generates the complete updated skill file with all session data filled in
- Also produces a **Session Report Card** summarising what was covered, scores, weak areas, and what to do next
- Download the updated file, replace your saved copy, and the next session picks up seamlessly

### 🏁 Exam Readiness Mode
- When all weeks of a subject are complete, Claude automatically generates:
  - A condensed master summary of all key concepts
  - A priority list of the top 10 topics for final revision
  - A full 15–20 question mock MCQ test
  - A performance report with recommended focus areas

---

## 🚀 How to Use

### Step 1 — First Time Setup
1. Download `EXAM_TUTOR_SKILL.md` from this repository
2. Save it to your device (Desktop, Notion, Obsidian, or any text editor works)
3. Open [claude.ai](https://claude.ai) and start a new conversation
4. Type the following one-liner, then paste the full contents of the file below it:

```
Please read and activate the skill file below — I will upload my lecture material once you confirm it is loaded.

[PASTE FULL FILE CONTENTS HERE]
```

5. Upload your lecture file (PPT or PDF) and tell Claude the subject and week number:

```
This is Week 3 of COMP63502 Data Engineering Technologies.
```

6. Start studying!

---

### Step 2 — Every Session After That
1. Open a **new** Claude conversation
2. Type the one-liner activation message
3. Paste the **most recently saved** version of `EXAM_TUTOR_SKILL.md` below it
4. Upload your lecture material and state the subject and week
5. Claude will recap your progress and resume from where you left off

---

### Step 3 — Ending a Session
At the end of any session, simply type:

```
Update today's progress
```

Claude will automatically:
- Summarise everything covered in the session
- Update all tracker sections in the file
- Output the complete updated `EXAM_TUTOR_SKILL.md` file for download
- Display a Session Report Card

Download the updated file and replace your saved copy. You are ready for next time.

---

## 📁 Repository Structure

```
claude-exam-tutor-skill/
│
├── EXAM_TUTOR_SKILL.md        ← The main skill file (paste this into Claude)
└── README.md                  ← This file
```

---

## 🔁 Session Workflow Summary

```
START SESSION
     │
     ▼
Paste EXAM_TUTOR_SKILL.md into Claude
     │
     ▼
Upload lecture file → state subject + week
     │
     ▼
Study → get explanations → answer MCQs → get feedback
     │
     ▼
Type "Update today's progress"
     │
     ▼
Download updated EXAM_TUTOR_SKILL.md
     │
     ▼
Replace saved file → ready for next session
```

---

## 💡 Tips for Best Results

- Upload **one subject's material at a time** to keep sessions focused
- Always state the **subject code and week number** when uploading (e.g. "Week 5 of COMP64802")
- If you want to switch subjects mid-session, just say so — Claude will handle the transition
- After every topic, ask for MCQs: *"Give me 5 MCQs on what we just covered"*
- Use the **Session Report Card** at the end of each session to track improvement over time
- Keep your most recent `EXAM_TUTOR_SKILL.md` saved and backed up — it is your single source of truth

---

## 🛠️ Requirements

- A [Claude.ai](https://claude.ai) account (Free, Pro, or Team)
- Your university lecture slides in PPT or PDF format
- A text editor to store and update the `.md` file between sessions (Notepad, VS Code, Notion, Obsidian — anything works)

---

## 📄 Licence

This project is open for personal and educational use. Feel free to adapt the skill file to your own subjects, modules, or exam formats.

---

*Built with Claude · Designed for postgraduate MCQ exam preparation · Version 2.0*
