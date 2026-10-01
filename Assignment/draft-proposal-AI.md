# The Sustainable Island 2027
## AI Use Policy Addendum
*Erasmus+ Collaboration – I.E.S. El Rincon / Tækniskolinn / TECHCOLLEGE*

*Version 2: proposed changes for the teachers' meeting on 2 October 2026.*

---

## 1. Purpose

This document defines how AI tools may be used in The Sustainable Island 2027 project. Students are encouraged to use AI — but must maintain genuine understanding of every line of code they submit.

> **AI is a learning tool, not a replacement for understanding.**

---

## 2. Permitted AI Use

Students may use AI tools (ChatGPT, GitHub Copilot, Claude, etc.) to:

- Generate boilerplate code or starter templates
- Understand concepts, syntax, or error messages
- Explore approaches to a technical problem
- Review and improve code they have already written
- Help write documentation and comments
- Build features with an AI agent that you direct, run and review
- Generate reports, explanations of complex topics, and visual comparisons of different solutions

These are examples. Any use of AI is allowed as long as you meet the core requirement in section 3, with one exception: the interviews in the design sprint must be with real people. AI may help you prepare questions and sort your notes, but it must never invent interviews, answers or users.

---

## 3. The Core Requirement

It does not matter whether code was written by the student, a teammate, or an AI. Every student must be able to explain any code within their area of contribution.

> ### The Golden Rule
> If you cannot explain a line of code to your teacher or a teammate, it does not belong in your project.

Understanding will be checked through code reviews, the final presentation, and unannounced spot-checks.

---

## 4. What Is Required When Using AI

### 4.1 Inline Comments
All code must include comments that you understand and could explain in your own words. AI may help write them (see section 2). Comments should show that the author understands what the code does.

### 4.2 AI Usage Log
Each student keeps a brief log of their AI use as part of the project documentation. At the end of every project day, note:

- What you asked
- What the AI returned
- What you changed and why
- What you learned

A few bullet points per day is enough. Write them in your own words.

Then ask your AI agent to turn the day into an HTML page: your notes word for word, followed by the AI's own account of how it was used. Ask it to make the page as easy to understand as possible, with interactivity and animations wherever they help to explain something complex (a before-and-after of a fix, how data flows through the app, a step-by-step walkthrough). Save it as `report/notes/<date>-<your-name>.html` and commit it the same day. You can use this prompt:

> *Go through our sessions from today and the git log. Make one HTML page with today's notes. First my notes below, word for word. Then your own short, factual account: what you built or changed (with commit hashes), what I asked you to explain, where you were wrong and how it was caught, and what I changed in your code. Do not flatter me. Make the page as easy to understand as possible: use interactivity and animations to explain anything complex. My notes: …*

If you used a tool without a history (for example a chat in the browser), add a line about it to your notes. Do not commit raw chat transcripts, as they can contain personal data or secret keys; keep them until grades are given.

### 4.3 Commit Ownership
You must be able to explain every commit you have made. Read, understand, and if needed modify AI-generated code before you commit it. If your tool adds a line such as `Co-Authored-By` to a commit, leave it there.

### 4.4 Team Review Before Merge
Before merging AI-generated code, explain it to at least one teammate. If you cannot explain it, it is not ready to merge. This is a habit we recommend; it is not graded.

### 4.5 The AI Report
Each team publishes an AI report as a web page, `report/index.html`, and submits its link with the other project links. Use your AI to build it from the daily notes pages, and make it interactive and easy to understand. It has these sections:

1. **Try it** – a link to the live app
2. **The problem** – what you learned from the interviews in the design sprint
3. **Decision log** – the main choices, what the AI suggested and what you chose and why, with visual comparisons
4. **What the AI got wrong** – the mistakes you found and how you fixed them, with links to the commits
5. **Tutorials** – one short, interactive explanation per student of a complex part of the code that student owns
6. **How we used AI** – which tools and what for, with links to every daily notes page

---

## 5. How Understanding Is Assessed

| Method | Description | When |
|---|---|---|
| Code Review Sessions | 10–15 min walkthrough with a teacher | During the project |
| Spot Checks | A teacher may ask about any snippet at any time | At any point |
| Group Visits | Two teachers from different countries visit each group and ask every group the same questions: one asks, one marks | January 21 |
| Final Presentation | Students explain their technical decisions | January 29 |
| AI Usage Log Review | The daily notes pages and the AI report, including their git history | Post assessment, with the review of the front end and back end |

Two items in the project rubric cover AI use, on the same 10-point and 7-point scale as the other items:

- **Understanding your code** (each student): explaining your own code to a teacher, during the group visits on January 21 or at the final presentation on January 29 (to be decided). Code review sessions and spot checks also count.
- **The AI report** (each team): the report and the daily notes pages, in the post assessment.

We grade how critically you used AI, not how much you used it. We do not use AI detectors: they are unreliable, and they wrongly flag people who write in a second language, which is all of us.

---

## 6. If You Cannot Explain Your Code

Using AI that you have declared in your notes is never penalised. What matters is whether you understand the result.

The following may apply:

- The section may be marked incomplete
- You may be asked to rewrite it independently
- A one-on-one technical interview may be requested

This is not a punishment — it is a way to make sure the project is a real learning experience.

---

## 7. A Note on Integrity

Using AI is fine. Submitting AI output you do not understand — and presenting it as your own — is not.

AI can make you a better developer, but only if you engage with it critically and take responsibility for what ends up in your code.

> **Before you commit, ask yourself:**
> - ✓ Can I explain every line?
> - ✓ Could I explain my comments in my own words?
> - ✓ Have I logged today's AI use, and is today's notes page committed?
> - ✓ Would I be comfortable walking a teacher through this right now?

---

