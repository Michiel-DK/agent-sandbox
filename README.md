# agent-sandbox → wilco

This project continues as **[wilco](https://github.com/Michiel-DK/agent-exam-suite)**
(`github.com/Michiel-DK/agent-exam-suite`, being renamed `Michiel-DK/wilco`; GitHub redirects either way).

**What it is.** An exam suite for small local language-model agents and the harness that grades them: eight
back-office tasks (email triage, expense fields, reply drafts, weekly recap, CRM follow-up over tool calls, call
summaries, CRM fields from a call, request intake), each with hand-authored train and held-out cases. Grading is
deterministic and judge-free: no model scores another model's work. A model's snapshot is three fresh loads at
temperature 0, and a case counts only when all three agree, so a runtime bump or a model swap re-sits the exam
case by case. Results are published as held-out fractions, failures left in.

**Where things live.**

- Public, curated cut: tasks, exams, runner, write-ups, results → [agent-exam-suite / wilco](https://github.com/Michiel-DK/agent-exam-suite)
- Results site → [roger3000.com/wilco](https://roger3000.com/wilco)
- The working repo with build ledger, sprint queue and lane briefs is private.

This repository is a signpost only. Its earlier contents were a September 2026 snapshot of the public cut, now
superseded.
