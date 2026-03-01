# LinkedIn Post Writing Skill for Claude AI

A complete system for writing LinkedIn posts that sound like a real person, not AI. Built for Claude Projects but adaptable to any AI writing workflow.

## What This Is

4 files that turn Claude (or any LLM) into a LinkedIn ghostwriter that actually sounds human. The system includes voice calibration, anti-AI detection, content strategy, algorithm optimization, and a weekly publishing workflow.

I use this system to write 3 LinkedIn posts per week for my engineering leadership coaching practice. Every post goes through an AI detection checklist before publishing.

## The Files

### Skill Files (upload these to your AI project)

| File | What It Does |
|---|---|
| `files/LinkedIn_SKILL.md` | Core writing guidelines. Voice profile, banned words (40+), post types, 2026 algorithm strategy, pre-publish checklist. This is the main instruction file. |
| `files/anti-ai-writing-guide.md` | How to NOT sound like AI. 8-part guide covering vocabulary, structure, tone, formatting, openings/closings, and content patterns. Includes side-by-side rewrites. |
| `files/LinkedIn_POST_EXAMPLES.md` | Real post examples for voice calibration. Annotated with what makes each one work. |
| `files/linkedin-weekly-system.md` | Weekly content workflow. Sunday planning, Tue/Wed/Thu writing sessions, Notion backlog integration, content mix rules. |

### Setup Files (for configuring Claude Projects)

| File | What It Does |
|---|---|
| `LinkedIn PROJECT_INSTRUCTIONS to paste.md` | Project instructions to paste into your Claude Project's system prompt. Defines triggers, formatting rules, and behavior. |
| `LinkedIn MEMORY_SEEDS to paste.md` | Suggested memory entries for tracking story numbers, high-performing formats, seasonal context, and voice corrections. |

## How to Use It

### With Claude Projects
1. Create a new Claude Project
2. Upload the 4 files from `files/` to the project's knowledge base
3. Copy the contents of `LinkedIn PROJECT_INSTRUCTIONS to paste.md` into the project's custom instructions
4. Optionally seed your memory with entries from `LinkedIn MEMORY_SEEDS to paste.md`
5. Start writing posts

### With Other LLMs
The files are plain markdown. You can paste them into any LLM's system prompt or context window. Start with `LinkedIn_SKILL.md` and `anti-ai-writing-guide.md` as the minimum setup.

### Adapting to Your Voice
These files are calibrated to my voice (direct, confrontational, coaching-oriented). To make them yours:

1. **Replace the voice profile** in `LinkedIn_SKILL.md` with your own phrases, tone, and style
2. **Replace the examples** in `LinkedIn_POST_EXAMPLES.md` with your actual best-performing posts
3. **Keep the anti-AI guide as-is.** The banned words, structure rules, and detection checklist are universal
4. **Adjust the content pillars** to match your expertise areas
5. **Update the proof points** with your own numbers and credentials

## What Makes This Different

Most AI writing prompts focus on what to write. This system focuses on what NOT to write.

The anti-AI detection layer catches 40+ vocabulary tells, 10+ structural patterns, and 6 tone problems that make AI-generated content obvious to readers. Every post runs through a 6-step quality gate before delivery.

The system also includes 2026 LinkedIn algorithm signals (360 Brew), content funnel strategy, and framework branding guidelines.

## The Anti-AI Philosophy

Your readers have developed an internal AI detector. They can't always name what feels off, but they feel it. The text is too smooth. Too balanced. Too careful.

This system eliminates that "AI smell" by:
- Banning 40+ words that AI overuses (leverage, navigate, unlock, empower, delve...)
- Breaking AI's default structure (intro → balanced body → summary → optimistic close)
- Forcing specific details over vague generalizations
- Requiring a clear stance instead of "on the other hand" hedging
- Checking every post against a read-aloud test

Full breakdown in `anti-ai-writing-guide.md`.

## About

I'm [Marian Kamenistak](https://www.kamenistak.com), an Engineering Leadership Coach based in Prague. I run the [Engineering Leaders Community](https://www.engineeringleaders.io/) (1,700+ members), mentor 300+ engineering leaders per year, and organize the annual ELC Conference.

These files are the actual system I use to write my LinkedIn content. Open-sourced because I think more people should know how to make AI-assisted writing sound human.

## License

MIT. Use it, adapt it, share it. If you build something cool with it, I'd love to hear about it.

## Connect

- LinkedIn: [mariankamenistak](https://www.linkedin.com/in/mariankamenistak/)
- Website: [kamenistak.com](https://www.kamenistak.com)
- Community: [engineeringleaders.io](https://www.engineeringleaders.io/)
