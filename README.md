# HUMN8031 Hacky Hours

Class repository for hacky-hour support in HUMN8031 (Digital
Humanities Research Project, ANU, Session 1, 2026).

This repo supports two things:

1. A **learning prompt** you can adapt with your LLM of choice to
   get a project-aware tutorial on any topic.
2. An **issue tracker** where you submit specific blockers before
   hacky-hour sessions, so class time is focused on your questions.

## Who this is for

Students enrolled in HUMN8031 who are preparing for a hacky-hour
session (Weeks 9–11) or the Week 11 discussion + PICO drop-in clinic.

## What's in here

| Path | Purpose |
|------|---------|
| `prompts/learning-prompt.md` | Adapt to your project and topic; run with your LLM before the session. |
| `.github/ISSUE_TEMPLATE/` | The issue template for submitting a blocker. |
| Issues tab | Where your blockers go. Submit at least 24 hours before the session. |

## How the workflow runs

### Before a hacky hour

1. Open `prompts/learning-prompt.md`.
2. Fork this repo (top-right on GitHub).
3. Edit your fork's copy of the prompt — paste in your project
   description, your skill level, and the topic for the next
   hacky hour.
4. Commit the edit to your fork (practice with git — this counts).
5. Run the adapted prompt with your favourite LLM. Work through at
   least the clarifying questions and the first step of the tutorial.
6. Try something concrete on your own project data — even a failed
   attempt teaches you something.
7. If you're still stuck on a specific question, open an issue on
   **this** repo (not your fork) using the template.

### During the hacky hour

- The instructor will pick 3–4 submitted issues that represent common
  problems and work through each one as a group discussion.
- Expect to be asked how you'd approach someone else's problem. Even
  a first-instinct answer is useful — there's no right answer.
- After the group discussion, there's an open floor for questions
  that weren't selected and for silent work on your own project.

### After the session

- If your issue was handled, reply with what worked (or didn't) and
  close the issue. Others reading the archive benefit from knowing
  how it resolved.
- If you still need help, leave the issue open and book 1:1 time.

## The pre-submission norm

**Submit at least 24 hours before the session.** Issues submitted
closer to class may not be chosen for the group discussion — the
instructor needs time to triage and sequence questions. Late
submissions still get picked up in the open-floor segment.

**Submit something concrete.** The template asks what you've already
tried. If you haven't tried anything, the answer to your question is
probably "try it and see" — not the kind of blocker hacky hours
address. Use your LLM first.

## Sessions covered

- **Week 9 Hour 2** — Python for humanities (foundation)
- **Week 10 Hour 1** — Python NLP + APIs
- **Week 10 Hour 2** — Zotero deep dive + Voyant Tools
- **Week 11 Hour 1** — Multimodal / video analysis + qualitative
  coding
- **Week 11 Hour 2** — Drop-in clinic for discussion section + PICO
  *(submit on Canvas for this one, not here)*

## Questions about this repo itself

Email shawn@faims.edu.au or raise it in class. If GitHub is the
blocker (rather than your research topic), use Canvas instead —
never let the tool get in the way of the question.
