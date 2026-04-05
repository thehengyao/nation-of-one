# 🏛️ Nation of One

**Run your life like a country.** A personal management skill for [OpenClaw](https://openclaw.ai) that frames your life as a nation with 8 ministries, each tracking a dimension of your wellbeing and growth.

## What It Does

Instead of yet another habit tracker or todo list, Nation of One gives you a **governance framework** — you're the head of state, your OpenClaw agent is your Chief of Staff, and your life is organized into 8 ministries:

| Ministry | Code | What It Manages |
|----------|------|-----------------|
| 发改委 National Development & Reform | NDRC | Goals, OKR, major decisions |
| 财政部 Ministry of Finance | MOF | Money + time + energy allocation |
| 教育部 Ministry of Education | MOE | Learning, skills, deep input |
| 卫健委 National Health Commission | NHC | Sleep, exercise, diet, checkups |
| 外交部 Ministry of Foreign Affairs | MFA | Relationships, networking, social |
| 文旅部 Ministry of Culture & Tourism | MCT | Pure leisure — games, travel, rest |
| 国防部 Ministry of Defense | MOD | Emotional resilience, risk, boundaries |
| 情报部 National Intelligence Agency | NIA | Industry intel (Dept 1) + hobby intel (Dept 2) |

## Key Features

- **Nation Founding** — First-time onboarding that diagnoses your "nation type" (tech-driven, resource-based, creative, etc.) and development stage before setting any goals
- **Daily Check-in** — Quick status report across ministries, only logging what's abnormal
- **Cabinet Meetings** — Weekly/monthly reviews with S/A/B/C/D ratings and trend arrows
- **Intelligence Briefings** — Web search-powered updates on your professional and hobby domains
- **Strategic Planning** — OKR framework when you're ready (not forced on day one)
- **Cross-ministry Analysis** — Detects when one department's decline affects another

## Token Efficiency

Designed to be lean on tokens:

- **SKILL.md**: ~70 lines, ~700 tokens when triggered
- **Reference files**: Loaded on-demand only (check-in guide, report templates, grading standards)
- **Daily logs**: YAML frontmatter + minimal text, skip normal departments
- **Weekly summaries**: ≤150 words, replace daily details
- **Monthly summaries**: ≤200 words, replace weekly details

Your context window stays clean. Old data is summarized and archived, never accumulated.

## Installation

### From ClawHub
```bash
clawhub install nation-of-one
```

### Manual
```bash
# Clone to your OpenClaw skills directory
git clone https://github.com/hengyaoooo/nation-of-one.git ~/.openclaw/skills/nation-of-one
```

### Workspace-level
```bash
git clone https://github.com/hengyaoooo/nation-of-one.git ./skills/nation-of-one
```

## Usage

Just talk to your agent naturally:

| You say | What happens |
|---------|-------------|
| "汇报" / "log today" | Daily check-in across ministries |
| "开内阁会议" / "weekly review" | Cabinet meeting with ratings |
| "月报" / "monthly report" | Monthly macro analysis |
| "仪表盘" / "dashboard" | Visual dashboard (if canvas available) |
| "情报简报" / "what's new in my field" | Web search-powered intel briefing |
| "定目标" / "set OKR" | Strategic planning session |
| "财政部怎么样" / "how's my health" | Single department deep dive |

Works in Chinese, English, or mixed — the agent adapts.

## File Structure

```
nation-of-one/
├── SKILL.md                      # Core instructions (loaded when triggered)
├── VERSION                       # Semver
├── README.md                     # You're reading it
└── references/
    ├── onboarding.md             # Nation founding flow (first use only)
    ├── checkin.md                # Daily check-in guide
    ├── report-format.md          # Weekly/monthly report templates
    └── grading.md                # S-D rating standards per ministry
```

## Data Storage

All data lives in `~/Documents/nation/` as plain Markdown:

```
~/Documents/nation/
├── founding.md                   # Nation founding declaration
├── config.md                     # Intel department config (your interests)
├── goals.md                      # Current OKR (when you're ready)
├── logs/                         # Daily status reports
│   ├── 2026-03-16.md
│   └── archive/                  # Archived old logs
├── weekly/                       # Weekly State of the Union
└── monthly/                      # Monthly macro reports
```

## Design Philosophy

1. **Diagnose before prescribe** — Understand your nation before setting goals
2. **Rest is rest** — Ministry of Culture ≠ Ministry of Education. Fun doesn't need to be "productive"
3. **Data-minimal** — Only log what's abnormal. Normal = no entry needed
4. **Sovereignty** — All suggestions are advisory. The head of state decides

## Requirements

- OpenClaw with any LLM (Claude recommended for best bilingual support)
- Web search tool (for Intelligence Briefings)
- No API keys or external services needed

## Security

```
# SECURITY MANIFEST:
# Environment variables accessed: none
# External endpoints called: none (web search via OpenClaw built-in)
# Local files read: ~/Documents/nation/**
# Local files written: ~/Documents/nation/**
```

## License

MIT-0 (ClawHub default)

## Contributing

Issues and PRs welcome. If you've extended the ministry system or added new report formats, I'd love to see them.
