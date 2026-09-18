<!--
  MiLLy template repository
  =========================
  This is a blank task repository pre-rigged with MiLLy, the Mastery Learning
  Loop tutor. To create a new task from it:

  1. Replace the placeholder sections below with your task content. MiLLy is
     topic-agnostic — the task can be a programming exercise, a proof, a data
     analysis, an essay, a poem to deconstruct, or anything with clear criteria.
  2. Put any supporting material where it suits the task (e.g. `src/`, `docs/`,
     `data/`). MiLLy reads the README first and follows links from it.
  3. State the learning goals explicitly — MiLLy anchors its skill analysis on
     them, so concrete goals produce better questions.
  4. Do NOT ship reference solutions — MiLLy builds its own internal reference.
  5. Edit POLICY.md to match your course's AI policy. It ships with the strict
     default (hints and explanations only); assistants follow whatever it
     says, and fall back to the strict default where it is silent.
  6. Keep the "Test yourself with MiLLy" section and the rigging files:
     MILLY.md, POLICY.md, AGENTS.md, CLAUDE.md, .claude/commands/milly.md,
     .github/agents/milly.md.

  Delete this comment block when the task is ready.
-->

# Task title 📝

*Introduce the task here: context, what the student will produce, and why it matters.*

### 💀 Deadline

*When the work should be completed.*

### ✅ Learning Goals

*List the concrete skills this task develops — MiLLy uses these to shape its quiz.*

1. …
2. …
3. …

### 🏛 Assignment

*The task itself: exercises, criteria, deliverables. Split into numbered exercises if helpful.*

### ❎ Checklist

- [ ] Completed all exercises to the best of your ability
- [ ] Tested your understanding with MiLLy (see below)
- [ ] Submitted your work

### 🤖 Test yourself with MiLLy

Once you have completed the task, you can quiz yourself with **MiLLy**, our Mastery Learning Loop tutor. MiLLy analyses the skills in this task and then asks you questions about them — one at a time, with feedback — ending with a summary of which skills look solid and which could use more practice. It's a great rehearsal for explaining your own work.

MiLLy works with whatever AI assistant you already use:

- **VS Code / Codespaces with Copilot:** select the **MiLLy** agent in the Copilot Chat agent picker, or just ask: *"Run MiLLy on this task"*.
- **CLI agents (Claude Code, Codex, Gemini CLI, …):** open the agent in this repository and say *"Run MiLLy"* (in Claude Code you can also type `/milly`).
- **Web chat (ChatGPT, Claude, …):** paste the contents of [`MILLY.md`](MILLY.md) and [`POLICY.md`](POLICY.md) into the chat along with the task description and your work, then say *"Run MiLLy"*.

You can scope the quiz (*"Run MiLLy on exercise 2"*) or run it again for more practice (*"quiz me again"*) — the questions will vary each time. MiLLy is there to test your understanding, not to do the work for you. What help AI assistants may give with the task itself is set out in [`POLICY.md`](POLICY.md) — and whatever it allows, remember that you must be able to explain the work you submit.
