# 🏛️ Nation of One

![Nation of One](assets/cover.jpg)

> [中文版](README_CN.md)

---

Most people who use productivity tools are doing execution work. Tasks, timers, streaks. It works — until it doesn't.

The quiet problem: execution tools assume you already know what you're executing toward. And they assume the person doing the executing is a stable, optimizable unit. Neither is true.

This shows up everywhere in vibe coding culture too. Someone gets excited about building. First project: a todo app. Second: a habit tracker. Third: a pomodoro timer. Not because those are the right things to build — but because that's the shape of the mental model they're running on. *Life as a queue of tasks to clear.*

But a person isn't a queue. A person is something that unfolds. The goal was never to complete more — it was to become more yourself.

**Nation of One is built on that premise.**

You're not a pipeline to be optimized. You're a country to be governed — with a foreign ministry for your relationships, a defense ministry for your emotional resilience, an intelligence agency for what you're paying attention to. Eight ministries. One life. The whole thing at once.

---

## What it looks like in practice

A designer with three products in progress. One is gaining traction, two are stalled. She's been logging daily for six weeks.

Her NDRC (goals) keeps getting B ratings even though she feels busy. Her MOF (time and energy) reveals she's spending 60% of her hours on the stalled projects. Her MOD advisor — someone known for not letting you avoid what's uncomfortable — surfaces a pattern she hadn't named: she gravitates toward the projects where she's in control of the output, not the ones that require her to be visible.

She didn't need another task manager. She needed to see the pattern.

That's what Nation of One is for.

---

## The 8 Ministries

| Code | Ministry | What It Governs |
|------|----------|-----------------|
| NDRC | 发改委 National Development & Reform | Goals, OKR, major decisions |
| MOF | 财政部 Ministry of Finance | Money, time, energy allocation |
| MOE | 教育部 Ministry of Education | Learning, skills, depth of input |
| NHC | 卫健委 National Health Commission | Sleep, exercise, diet, body signals |
| MFA | 外交部 Ministry of Foreign Affairs | Relationships, networking, social energy |
| MCT | 文旅部 Ministry of Culture & Tourism | Rest, leisure — no justification required |
| MOD | 国防部 Ministry of Defense | Emotional resilience, risk, boundaries |
| NIA | 情报部 National Intelligence Agency | Industry intel + personal interest tracking |

---

## Key Features

**Nation Founding**
Answer a few questions. Get your nation type, development stage, and baseline ministry ratings. Start governing the same day.

**Deep Founding**
Three ways in:
- *You have years of rawdata* — journals, notes, chat logs. Feed them in. The system builds a persistent knowledge base organized through 8 ministry lenses (inspired by [Andrej Karpathy's LLM wiki framework](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)), then produces a 6-dimension self-portrait: strengths, blind spots, core tensions, energy map, opportunity windows, risk tracks.
- *You have some materials* — whatever you have. Partial is fine. The portrait will be partial too, and honest about it.
- *You have nothing* — start with standard founding. Build from here.

**Daily Check-in**
Quick status across ministries. Only log what's abnormal. Normal = silence.

**Proactive Briefing**
Every session opens with an automatic scan — overdue logs, ministry warnings, advisor intel. Surfaced before you ask.

**Cabinet Meetings**
Weekly and monthly reviews with S/A/B/C/D ratings and trend arrows.

**Advisor Cabinet**
Distill real people — thinkers, builders, historical figures — into advisor personas. Appoint them to ministries. Summon them when you need a perspective you can't reach alone.
[nuwa-skill](https://github.com/alchaincyf/nuwa-skill) by [@alchaincyf](https://github.com/alchaincyf) · [X](https://x.com/alchainhust) breathes them into existence. Nation of One puts them to work.

**Intelligence Briefings**
Web search-powered updates on your professional domains and personal interests. Your NIA, doing its actual job.

---

## How to Talk to It

| You say | What happens |
|---------|-------------|
| `"建国"` / `"found my nation"` | Standard onboarding |
| `"深度建国"` / `"deep founding"` | rawdata → self-portrait → advisor recommendations |
| `"汇报"` / `"daily check-in"` | Ministry status report |
| `"开内阁会议"` / `"cabinet meeting"` | Weekly review with ratings |
| `"月报"` / `"monthly report"` | Monthly macro analysis |
| `"情报简报"` / `"intel briefing"` | Web search update on your fields |
| `"定目标"` / `"set OKR"` | Strategic planning |
| `"财政部怎么样"` / `"how's MOF"` | Single ministry deep dive |
| `"蒸馏 [人名]"` | Distill a person into an advisor persona |
| `"任命 [人名] 为 [部委]"` | Appoint advisor to a ministry |
| `"召见 [人名]"` | Summon an advisor to your current situation |
| `"顾问团状态"` | List all advisors and appointments |

Works in Chinese, English, or mixed.

---

## Installation

```bash
npx skills add hengyaoooo/nation-of-one
```

Requires [Claude Code](https://claude.ai/code).

> OpenClaw support coming soon.

---

## Data Storage

Everything in `~/Documents/nation/` as plain Markdown. No cloud. No accounts. Yours.

```
~/Documents/nation/
├── founding.md        # Nation founding declaration
├── config.md          # Ministry config + advisor assignments
├── goals.md           # OKR (when you're ready)
├── logs/              # Daily check-ins
├── weekly/            # Cabinet meeting reports
├── monthly/           # Monthly macro reports
├── wiki/              # Knowledge base built from your rawdata
└── advisors/          # Distilled advisor personas
```

---

## Design Principles

1. **Diagnose before prescribe** — Know your nation before setting goals
2. **Rest is rest** — MCT ≠ MOE. Leisure doesn't need to earn its place
3. **Data-minimal** — Only log what's abnormal. Normal = no entry
4. **Sovereignty** — All suggestions are advisory. You decide
5. **No blind spots** — The system reflects what's actually in your data, including what you might not want to see

---

## File Structure

```
nation-of-one/
├── SKILL.md
├── VERSION
├── README.md
├── README_CN.md
├── assets/
│   └── cover.jpg
├── examples/
│   └── advisor-cabinet-example.md
└── references/
    ├── onboarding.md
    ├── deep-onboarding.md
    ├── ministry-audit.md
    ├── advisors.md
    ├── checkin.md
    ├── report-format.md
    └── grading.md
```

---

## Credits

- Advisor distillation — [nuwa-skill](https://github.com/alchaincyf/nuwa-skill) by [@alchaincyf](https://github.com/alchaincyf) · [X](https://x.com/alchainhust)
- Knowledge base architecture — [Andrej Karpathy's LLM wiki framework](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)

---

MIT-0 — do whatever you want with it.

Issues and PRs welcome.
