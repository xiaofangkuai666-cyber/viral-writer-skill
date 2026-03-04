# 🔥 Viral Writer — OpenClaw Skill

Write viral, human-sounding long-form content for social platforms.

**Platforms supported:** X/Twitter threads, 公众号, LinkedIn, 小红书, Discord, Newsletter

**Languages:** Chinese & English

## What It Does

This is an [OpenClaw](https://github.com/openclaw/openclaw) skill that transforms any topic into high-engagement social content through a 7-step pipeline:

```
BRIEF → FRAMEWORK → HOOK → DRAFT → DE-AI → FORMAT → DELIVER
```

The critical differentiator: a rigorous **De-AI processing** pass that makes AI-generated content sound genuinely human — with specific personal details, raw emotion, intentional imperfections, and natural language patterns.

## Key Features

- **5 Proven Frameworks** — Narrative, Contrast, Listicle, Counter-Intuitive, Personal Journey
- **Hook Formulas** — 5 battle-tested formulas that stop the scroll
- **De-AI Checklist** — 5-pass system to eliminate "AI smell" from any draft
- **Depth Lenses** — Philosophy, sociology, data techniques, and cross-domain analogies
- **Platform Formatting** — Specific rules for X, 公众号, LinkedIn, 小红书, Discord, and newsletters

## Installation

### For OpenClaw users

Copy the skill into your OpenClaw skills directory:

```bash
git clone https://github.com/xiaofangkuai666-cyber/viral-writer-skill.git
cp -r viral-writer-skill ~/.openclaw/skills/viral-writer
```

### For everyone else

The reference files in `references/` are standalone and useful even without OpenClaw:

- [`references/frameworks.md`](references/frameworks.md) — 5 content frameworks with templates
- [`references/hooks.md`](references/hooks.md) — Hook formulas and quality tests
- [`references/de-ai-checklist.md`](references/de-ai-checklist.md) — Make AI writing sound human
- [`references/depth-lenses.md`](references/depth-lenses.md) — Add intellectual depth
- [`references/platforms.md`](references/platforms.md) — Platform-specific formatting rules

## File Structure

```
viral-writer/
├── SKILL.md                  # Main skill definition (OpenClaw entry point)
├── README.md                 # This file
└── references/
    ├── frameworks.md         # 5 writing frameworks
    ├── hooks.md              # Hook design formulas
    ├── de-ai-checklist.md    # De-AI processing passes
    ├── depth-lenses.md       # Intellectual depth lenses
    └── platforms.md          # Platform formatting guide
```

## De-AI: The Secret Sauce

Most AI writing fails because it *sounds* like AI. This skill includes a 5-pass de-AI system:

1. **Person Pass** — Replace "研究表明" with "我发现"
2. **Detail Pass** — Add specific times, places, numbers
3. **Emotion Pass** — Inject raw, authentic feelings
4. **Imperfection Pass** — Add self-doubt, admitted mistakes, asides
5. **Read-Aloud Pass** — If it sounds like an essay, rewrite it

Plus: 去结构化, 重构逻辑, 标点故障, 高频词去重, 比喻+玩梗 techniques.

## License

MIT

## Credits

Built by [AH Company](https://github.com/xiaofangkuai666-cyber) for [OpenClaw](https://github.com/openclaw/openclaw).
