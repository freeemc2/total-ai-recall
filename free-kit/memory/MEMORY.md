# Memory Index

This is the map of everything your AI knows about you and your work. Every memory file gets one line here, grouped by temperature. Your AI reads this index on startup to decide what to load.

Keep the HOT list short. If everything is hot, nothing is.

---

## 🔥 HOT — loads every session

*The handful of things needed every single time. Who you are, what you're working on now.*

- [about-me](memory/about_me.md) — who I am, how I work
- *(add your current-project file here once you make one)*

---

## 🟠 WARM — loads when the task touches this project

*Project details, loaded on demand — not every session.*

- *(example: [game-tilt](memory/project_tilt.md) — the puzzle game, mechanics and goals)*

---

## 🔵 COOL — searched when relevant

*Occasionally useful. Your AI searches these when the topic comes up.*

- *(example: [feedback-code-style](memory/feedback_code_style.md) — how I like code formatted)*

---

## ⚪ COLD — archived, never auto-loaded

*Old stuff kept for the record. Only opened if you go looking.*

- *(example: [old-project-v1](memory/archive_v1.md) — the first version, shelved)*

---

**How to use this file:** every time you create a memory in the `memory/` folder, add one line here under the right temperature. When a memory cools off, move its line down. This index is how your AI — and you — see the whole picture at a glance.
