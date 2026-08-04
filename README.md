# Second Brain for ChatGPT

A ChatGPT-compatible version of the [execassistant-template](https://github.com/alexsidhu1/execassistant-template). Same idea (a folder of files that turns ChatGPT into an assistant that knows you), rebuilt for how ChatGPT actually reads files, since it doesn't read `.claude/` or `CLAUDE.md` the way Claude Code does.

## What's here

```
chatgpt-second-brain/
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
  templates/
    session-summary.md
```

## What's different from the Claude Code version

| | Claude Code (`execassistant-template`) | ChatGPT (this template) |
|---|---|---|
| Bootstrap file | `CLAUDE.md`, auto-read on start | `INSTRUCTIONS.md`, pasted once into Project instructions |
| Context files | `.claude/`-aware, read on demand | Uploaded as Project files, ChatGPT searches them when relevant |
| Skills / agents | `.claude/skills/`, `.claude/agents/`, auto-discovered | Not supported. There's no file-based skill or subagent system in ChatGPT. |
| Decision log | Assistant edits `decisions/log.md` directly | You ask it to draft the entry, then paste it into the file and re-upload |
| Memory | Claude Code's built-in persistent memory | ChatGPT's separate "Memory" feature (Settings → Personalization) is a complement, not a replacement — it's not file-based and doesn't travel with this folder |

If you outgrow these limits (you want it editing its own files, running skills, or holding memory that isn't tied to one browser), that's the signal to move to Claude Code, not a reason to avoid starting here.

## Source

Adapted from [github.com/alexsidhu1/execassistant-template](https://github.com/alexsidhu1/execassistant-template) (Whitehorse AI).
