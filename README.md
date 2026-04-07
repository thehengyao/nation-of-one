# 🏛️ Nation of One

![Nation of One](assets/cover.jpg)

> [中文版 README](README_CN.md)

---

Productivity tools treat you like a pipeline. Input tasks, output results, repeat.

But a person isn't a pipeline. A person is something you become.

The goal was never to do more. It was always to be more — more yourself, more coherent, more alive to what actually matters to you. No app built around tasks and deadlines can get you there.

**Nation of One is built around a different premise: you are a country.**

Countries don't optimize. They govern — across defense and diplomacy, culture and economy, health and intelligence, all at once. A country's measure isn't how much it produces. It's whether it's becoming what it's capable of being.

You're the head of state. Your AI is your Chief of Staff. Eight ministries. One life. Fully yours.

---

## The 8 Ministries

| Code | Ministry | What It Governs |
|------|----------|-----------------|
| NDRC | 发改委 National Development & Reform | Goals, OKR, major decisions |
| MOF | 财政部 Ministry of Finance | Money, time, energy allocation |
| MOE | 教育部 Ministry of Education | Learning, skills, deep input |
| NHC | 卫健委 National Health Commission | Sleep, exercise, diet, body signals |
| MFA | 外交部 Ministry of Foreign Affairs | Relationships, networking, social energy |
| MCT | 文旅部 Ministry of Culture & Tourism | Pure leisure — rest is rest, not productivity |
| MOD | 国防部 Ministry of Defense | Emotional resilience, risk, boundaries |
| NIA | 情报部 National Intelligence Agency | Industry intel + personal interest tracking |

---

## Key Features

**Standard Founding**
Answer a few questions. Get your nation type, development stage, and baseline ratings. Start governing the same day.

**Deep Founding**
Feed it years of your journals, notes, and chat logs. The system reads them through 8 ministry lenses and produces a 6-dimension self-portrait — strengths, blind spots, core tensions, energy map, opportunity windows, risk tracks. Then it recommends which advisors to hire based on your actual patterns, not generic advice.

**Daily Check-in**
Quick status across ministries. Only log what's abnormal. Normal = silence.

**Proactive Briefing**
Every session opens with an automatic scan. Overdue logs, ministry warnings, advisor updates — surfaced before you ask.

**Cabinet Meetings**
Weekly and monthly reviews with S/A/B/C/D ratings and trend arrows. One session to see your whole nation's health.

**Advisor Cabinet**
Distill real people — thinkers, builders, historical figures — into advisor personas. Appoint them to ministries. Summon them anytime to weigh in on your decisions.
[nuwa-skill](https://github.com/alchaincyf/nuwa-skill) by [@alchaincyf](https://github.com/alchaincyf) breathes them into existence. Nation of One puts them to work.

**Intelligence Briefings**
Web search-powered updates on your professional domains and personal interests. Your NIA, actually doing its job.

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

Works in Chinese, English, or mixed — the system adapts.

---

## Installation

```bash
npx skills add hengyaoooo/nation-of-one
```

Requires [Claude Code](https://claude.ai/code).

> OpenClaw support coming soon.

---

## Data Storage

Everything lives in `~/Documents/nation/` as plain Markdown. No cloud. No accounts. Yours.

```
~/Documents/nation/
├── founding.md        # Your nation's founding declaration
├── config.md          # Ministry config + advisor assignments
├── goals.md           # OKR (when you're ready)
├── logs/              # Daily check-ins
├── weekly/            # Cabinet meeting reports
├── monthly/           # Monthly macro reports
├── wiki/              # Ministry wikis built from your rawdata
└── advisors/          # Distilled advisor personas
```

---

## Design Principles

1. **Diagnose before prescribe** — Know your nation before setting goals
2. **Rest is rest** — MCT ≠ MOE. Leisure doesn't need justification
3. **Data-minimal** — Only log what's abnormal. Normal = no entry
4. **Sovereignty** — All suggestions are advisory. You decide
5. **No blind spots** — The system reflects what's in your data, including what you might not want to see

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

## License

MIT-0 — do whatever you want with it.

## Contributing

Issues and PRs welcome. If you've built a custom advisor configuration or extended the ministry system, open a PR.
