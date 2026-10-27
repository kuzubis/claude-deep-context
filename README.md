# claude-deep-context

**Let Claude interview you once — and stop explaining yourself in every chat.**
A skill that runs a structured interview (14 blocks, one question at a time) and turns your answers into two claude.ai skills: **my-profile** (how you work, who you are, family and dates, sport, devices) and **my-company** (company, people, contracts, finances, projects).

🇺🇦 [Українська версія](README.uk.md)

## Two ways to run it
| | claude.ai chat | Claude Code / Cowork |
|---|---|---|
| Needs | a plan with Skills | Claude Code (or Cowork) |
| Where answers go | kept in the conversation; progress card to resume in a new chat | written to `profile/docs/ABOUT-ME.md` and `<company>/docs/CONTEXT.md` after every block |
| At the end | `my-profile.zip`, `my-company.zip` (or the text to save) | the same, plus the reference files stay on disk |

## Quick start — claude.ai chat
1. Download this repository (green **Code** button → **Download ZIP**) and unpack it.
2. Make the skill zip: compress the folder `skills/deep-context-interview` into `deep-context-interview.zip` (Windows: right-click → Send to → Compressed folder), or run `python tools/build-skill-zips.py skills`.
3. claude.ai → your name (bottom left) → **Settings** → **Capabilities** → **Skills** → **Upload skill** → choose the zip → switch it on.
4. New chat: **"Interview me"**. Answer with text, voice or files (a CV saves a whole block). Say **"pause"** any time.
5. At the end upload the two skills it gives you the same way. Done — every new chat (and Cowork) now knows you.

## Quick start — Claude Code
Copy `skills/deep-context-interview/` into your working folder as `.claude/skills/deep-context-interview/`, open Claude Code there and say **"Interview me"**. Or, without the skill, paste the prompt from [interview/questions.md](interview/questions.md).

## What's inside
| Path | What |
|---|---|
| `skills/deep-context-interview/` | the interviewer skill (self-contained: all questions and rules inside) |
| `skills/my-profile/`, `skills/my-company/` | templates of the two result skills |
| `interview/questions.md`, `questions.uk.md` | the questions as a readable list (EN / UK) |
| `tools/build-skill-zips.py` | packs skill folders into zips claude.ai accepts; refuses unfilled templates |

## Privacy
The interview never asks for passwords, card or account numbers, passport data or e-signature codes — and the skill refuses to store them. Your profile skills live in your claude.ai account; reference files stay on your disk.

## Keep the memory fresh
The skills are a snapshot. To keep Claude Code, claude.ai chat and Cowork in sync after every task, see the companion kit **[claude-shared-memory](https://github.com/kuzubis/claude-shared-memory)**.

## Origin
Built by a non-programmer together with Claude Code after a two-day "deep context" interview that replaced dozens of repeated explanations. Improvements welcome.

License: [MIT](LICENSE).
