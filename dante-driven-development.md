# Dante Driven Development (DDD)

> *"Nel mezzo del cammin di nostra codebase..."*

**Version 1.0 — The Lightweight AI Development Methodology**

---

## Philosophy

Not smarter coding. Not heavier documentation. Just: a little structure, every day a little further through purgatory.

DDD is not a framework you install. It is a habit you develop. Born organically from daily practice with Claude Code, it combines the best of Scrum, GTD, and spec-driven development — without the overhead of any of them.

> *"Don't code smarter. Don't document harder. Just show up, read the last report, and keep moving."*

---

## The Three Artifacts

### I. Session Report — *the sprint retrospective*

```
sessionreport240326.md
```

Written at the end of every session, by Claude, steered by you. A chronological archive of the project's evolution. Short, dense, useful. Not a diary — a handover note to your future self.

**Rule:** One per day. Date in the filename. Never overwrite.

---

### II. Rolling Todos — *the prioritized backlog*

```
rolling_todos.md
```

The top = urgent. Updated together with Claude at the end of every session. The most important tasks live at the top — Claude reads the file top-down, so priority is structural, not labelled.

**Rule:** Always end a session by asking Claude: *"What goes on top of rolling_todos for the next session?"*

---

### III. The Plan — *PRD + architecture*

```
projectname_plan.md
```

The living document. Goal, direction, technical decisions. Loaded at the start of every new session to give Claude the right context without rebuilding it from scratch.

**Rule:** Update it when decisions change. Never let it go stale.

---

## The Session Cycle

```
Start session
    → Read most recent sessionreport
    → Read rolling_todos
    → Build
    → Evaluate + prioritize together with Claude
    → Write new sessionreport
```

No ceremonies. No standups. No planning poker. Just the cycle.

---

## The Virgil Protocol

Claude is Virgil: he guides you through the purgatory of the codebase, but you set the direction. Without you, Virgil wanders aimlessly.

Start every session with:

```
"Read sessionreport[date].md and rolling_todos.md, then tell me where we left off."
```

Claude will orient itself immediately. No context lost. No re-explaining. Ready to build.

---

## Comparison

| Method | Verdict |
|---|---|
| Superpowers | Too rigid — deletes your code before you can blink |
| BMAD | Too heavy — 21 agents for a solo developer |
| GTD | For humans, not for AI pairs |
| Waterfall | Non, merci |
| Scrum | Good ideas, too many meetings |
| **DDD** | Just right |

---

## Core Principles

**Chronological memory** — Every day adds a layer. Together they tell the story of the project.

**Living backlog** — Priority at the top, always updated, never forgotten.

**Light but consistent** — No ceremonies. No frameworks. Just do what works.

**Human + AI as a duo** — You steer, Claude executes. Dante and Virgil.

---

## Compatibility

DDD works with any Claude Code setup. No plugins required. No marketplace needed. No `/plugin install dante`.

Compatible with:
- Claude Code CLI
- Claude Max subscription
- Friday afternoon deploys *(not recommended)*

---

## Anti-Patterns

**The Kitchen Sink Session** — Starting three unrelated tasks in one session. Fix: `/clear` between topics, or start a new session.

**The Stale Plan** — A `projectname_plan.md` that no longer reflects reality. Fix: update it whenever a major decision changes.

**The Forgotten Report** — Ending a session without writing the report. Fix: make it the last line of every session, non-negotiable.

**The Infinite Backlog** — A `rolling_todos.md` so long Claude can't hold it in context. Fix: split into `todos_active.md` and `todos_backlog.md` when it grows beyond ~50 lines.

---

## Origin

DDD was not designed. It emerged. Through months of daily Claude Code sessions, three files proved their worth above all others: the session report, the rolling todos, and the plan. Everything else was overhead.

The name came later — a joke about development methodologies and Dante's *Inferno*. But the practice came first.

> *"Lasciate ogni spaghetti code, voi ch'entrate."*
> — DDD Manifesto, 2026

---

*DDD is not affiliated with, endorsed by, or sponsored by Anthropic, Dante Alighieri, or the city of Florence.*
