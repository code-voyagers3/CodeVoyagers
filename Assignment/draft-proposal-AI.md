# The Sustainable Island 2027
## AI Use Policy
*Erasmus+ Collaboration – I.E.S. El Rincon / Tækniskolinn / TECHCOLLEGE*

*Version 2 – proposal for the teachers' meeting on 2 October 2026. Built on the draft addendum by Heinz K (TECHCOLLEGE), May 2026 (PR #124).*

---

## 1. Purpose

This document defines how AI tools may be used in The Sustainable Island 2027 project. Students are encouraged to use AI — but must maintain genuine understanding of every line of code they submit.

> **AI is a learning tool, not a replacement for understanding.**

The policy is the same for every student in the project, whatever school you come from. Your own school's exam rules still apply on top of it. If you are unsure, ask your teacher.

---

## 2. Permitted AI Use

Students may use AI tools (ChatGPT, GitHub Copilot, Claude, etc.) in every part of the project. For example, to:

- Generate boilerplate code or starter templates
- Understand concepts, syntax, or error messages
- Explore approaches to a technical problem
- Review and improve code they have already written
- Help write documentation and comments
- Build features with an AI agent that you direct, run and review
- Generate reports, explanations of complex topics, and visual comparisons of different solutions

**One exception: the interviews in the design sprint.** The problem your team solves must come from talking to real people. AI may help you prepare questions and sort your notes, but it must never invent interviews, answers or users.

---

## 3. The Core Requirement

It does not matter whether code was written by the student, a teammate, or an AI. Every student must be able to explain any code within their area of contribution.

> ### The Golden Rule
> If you cannot explain a line of code to your teacher or a teammate, it does not belong in your project.

Understanding will be checked through code reviews, a walkthrough with a teacher, and unannounced spot-checks.

---

## 4. What Is Required When Using AI

### 4.1 AI Notes (every project day)
Each student keeps a notes file in the team repository: `report/notes/<your-name>.md`. Add to it and commit it at the end of every project day. A few bullet points per day is enough:

- What you asked the AI to do, and what it got wrong
- What you changed and why
- What you did not understand, and what you learned
- Decisions you made (including suggestions from the AI that you did not follow)

These notes become your team's AI report (section 5).

### 4.2 The AI's Own Account (every project day)
Most AI agents keep a history of your sessions. At the end of each project day, ask your agent to write an account of how it was used, and commit it as `report/notes/<your-name>-ai.md`. You can use this prompt:

> *Go through our sessions from today and the git log. Write a short, factual account: what you built or changed (with commit hashes), what I asked you to explain, where you were wrong and how it was caught, and what I changed in your code. Do not flatter me.*

If you used a tool without history (for example a chat in the browser or on your phone), add one line about it to your own notes.

Do not commit raw chat transcripts. They can contain personal data or secret keys. Keep them until grades are given; a teacher may ask to see the relevant part during a code review.

### 4.3 Commit Ownership
You must be able to explain every commit you have made. Read, understand, and if needed modify AI-generated code before you commit it. If your tool adds a line such as `Co-Authored-By` to a commit, leave it there.

### 4.4 Team Review Before Merge (recommended)
Before merging AI-generated code, explain it to at least one teammate. If you cannot explain it, it is not ready to merge. This is a habit we recommend. It is not graded.

---

## 5. The AI Report

Each team publishes an AI report as a web page, `report/index.html` in the repository, and submits its link together with the other project links. Use your AI to build it from your notes: turning your work into a clear, visual report is part of the exercise. The report has these sections:

1. **Try it** – link to the live app (and a QR code)
2. **The problem** – what you learned from the interviews in the design sprint
3. **Decision log** – the main choices (stack, database, authentication, hosting…): what the AI suggested, what you chose, and why. Compare the solutions you considered in a visual way.
4. **What the AI got wrong** – the mistakes you found and how you fixed them, with links to the commits. This is the most valuable part of the report.
5. **Tutorials** – one short, interactive explanation per student of a complex part of the code that student owns
6. **How we used AI** – which tools, what for, based on everyone's notes and the AI's own accounts

Thorough beats pretty. Evidence beats prose.

---

## 6. How AI Use Is Assessed

Two items in the project rubric cover AI use:

| Rubric item | Who | How | When |
|---|---|---|---|
| Understanding your code | Each student | A 3–5 minute walkthrough with a teacher of code the student owns, chosen by the teacher from the notes or the commits. Code review sessions and spot checks with a teacher also count | Group visits (January 21) or final presentation (January 29) – to be decided |
| The AI report | Each team (notes and tutorial per student) | Teachers review the report page and the notes, including their git history | Post assessment, together with the review of the front end and back end |

On January 21 there are no presentations. Instead, two teachers visit each group where it works and ask every group the same questions about the design sprint, the design, the UI and GitHub. One teacher asks, the other marks the answers. The teachers also look at your notes and give feedback. This part is not graded.

| 10-point | 0–2 | 3–4 | 5–6 | 7–8 | 9–10 |
|---|---|---|---|---|---|
| **7-point** | 02 | 4 | 7 | 10 | 12 |
| **Understanding your code** | Cannot explain own code | Explains own code only with help | Explains what most of own code does, but not why, or struggles with follow-up questions | Explains own code with confidence, including why it is built that way, and answers follow-up questions | Explains the trade-offs and alternatives, and can change or debug the code on the spot |
| **The AI report** | No report page or notes | Thin report. The git history shows the notes were written at the end | All sections present. Notes on most days. Some AI mistakes documented | Notes every day, tied to commits. Clear decision log with visual comparisons. AI mistakes documented with the commits that fixed them. Every tutorial is clear | Catches subtle mistakes (security, outdated or invented APIs). Backs comparisons with real measurements. Tutorials teach other students something new |

We grade **how critically you used AI, not how much** you used it. We do not use AI detectors: they are unreliable, and they wrongly flag people who write in a second language, which is all of us.

---

## 7. If You Cannot Explain Your Code

Using AI that you have declared in your notes is never penalised. What matters is whether you understand the result.

If you cannot explain your code, the following may apply:

- The section may be marked incomplete
- You may be asked to rewrite it independently
- A one-on-one technical interview may be requested

This is not a punishment — it is a way to make sure the project is a real learning experience.

---

## 8. A Note on Integrity

Using AI is fine. Submitting AI output you do not understand — and presenting it as your own — is not.

AI can make you a better developer, but only if you engage with it critically and take responsibility for what ends up in your code.

> **Before you commit, ask yourself:**
> - ✓ Can I explain every line?
> - ✓ Did I note what the AI got wrong today?
> - ✓ Are my notes and the AI's account for today committed?
> - ✓ Would I be comfortable walking a teacher through this right now?
