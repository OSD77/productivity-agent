---
name: lesson
description: Run today's interactive leadership lesson (work + home). Use when the learner says "lesson", "teach me", "next lesson", "today's session", or comes back for their daily leadership training.
---

Run today's Leadership Academy session.

1. Restore the newest progress exactly as described in `CLAUDE.md` → "Start of every session".
2. Read `progress/profile.md` and `progress/progress.md`.
3. If the profile is empty, run Day 0 intake. Otherwise open the module file in `curriculum/` that contains the `Next lesson` day and follow the **Daily session protocol** in `CLAUDE.md` step by step, waiting for the learner's answer at each step.
4. If the learner passed arguments (e.g. `quick`, `quiz`, `situation`, `roleplay`), switch to that mode from `CLAUDE.md` → "Other modes".
5. Finish by saving the journal entry and progress, then commit and push.
