# Personal AI OS (ChatGPT version)

A ChatGPT-compatible version of the [execassistant-template](https://github.com/alexsidhu1/execassistant-template). Same idea (a folder of files that turns ChatGPT into an assistant that knows you), rebuilt for how ChatGPT actually reads files, since it doesn't read `.claude/` or `CLAUDE.md` the way Claude Code does.

## What's here

```
personal-ai-os/
  GETTING-STARTED.md       <- step by step setup
  INSTRUCTIONS.md          <- paste this into ChatGPT's Project instructions
  context/
    me.md
    work.md
    team.md
    current-priorities.md
    goals.md
  decisions/
    log.md
  references/
    README.md
  skills/
    README.md
    weekly-review.md
  templates/
    session-summary.md
```

## What's different from the Claude Code version

| | Claude Code (`execassistant-template`) | ChatGPT (this template) |
|---|---|---|
| Bootstrap file | `CLAUDE.md`, auto-read on start | `INSTRUCTIONS.md`, pasted once into Project instructions |
| Context files | `.claude/`-aware, read on demand | Uploaded as Project files, ChatGPT searches them when relevant |
| Skills | `.claude/skills/`, auto-discovered, works on any plan | ChatGPT's own **Skills** tab (Plugins → Skills), launched July 2026. Same idea — a reusable, named workflow — but **only on Business, Enterprise, Healthcare, or Edu plans.** Not available on Free, Plus, or Pro. See `skills/README.md`. |
| Agents / subagents | `.claude/agents/`, orchestrated automatically | Not supported. ChatGPT has no equivalent to routing a task to a specialist subagent. |
| Decision log | Assistant edits `decisions/log.md` directly | You ask it to draft the entry, then paste it into the file and re-upload |
| Memory | Claude Code's built-in persistent memory | ChatGPT's separate "Memory" feature (Settings → Personalization) is a complement, not a replacement — it's not file-based and doesn't travel with this folder |

If you're on ChatGPT Plus or Pro, skip `skills/` — it won't do anything for you yet. If you outgrow what's left (agent orchestration, memory that isn't tied to one workspace), that's the signal to move to Claude Code.

## Get it

Live at [github.com/alexsidhu1/personal-ai-os](https://github.com/alexsidhu1/personal-ai-os) — download the ZIP, no GitHub account needed.

## Source

Adapted from [github.com/alexsidhu1/execassistant-template](https://github.com/alexsidhu1/execassistant-template) (Whitehorse AI).
