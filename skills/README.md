# Skills (Business, Enterprise, Healthcare, or Edu plans only)

ChatGPT's Skills feature (launched July 2026) is the closest thing to Claude Code's `.claude/skills/` folder: a named, reusable workflow that tells ChatGPT how to do a specific recurring task the same way every time, instead of you re-explaining it in every chat.

**Not on Plus or Pro.** The Skills tab only exists on Business, Enterprise, Healthcare, and Edu workspaces. If you don't see **Plugins → Skills** in your sidebar, that's why — nothing broken, just not your plan.

## How it's different from Claude Code's version

- Claude Code skills are a file (`SKILL.md`) sitting in a folder, auto-discovered from disk.
- ChatGPT skills live in the app itself, built through a UI (Plugins → Skills → Create a skill), not a file you drop somewhere.
- You can still draft the content here first and paste it in — that's what the files in this folder are for.
- Exactly how ChatGPT ingests an *externally authored* skill file (versus one built inside its own creator UI) isn't something we've nailed down yet — OpenAI hasn't published a stable file spec for it. So treat the `.md` files in this folder as **drafts to paste into the Skill creator**, not files to "import" and expect to work unmodified. Copy the content in, let ChatGPT refine it if it wants to reshape the format, and check the result actually saves and runs before relying on it.

## How to write your own

Same shape as the example (`weekly-review.md`):

1. **Name it.** Short, one recognizable trigger phrase.
2. **Say when it fires.** What you'd actually type to call it ("run my weekly review", "draft a lease submission").
3. **List the steps.** What it should check, in what order, before it produces anything.
4. **Specify the output.** Format, length, tone — don't leave it to guess.

Build it once, watch it run, then tighten it. The first version is never the last version.

## Sharing with a team

If you're an admin on a Business or Enterprise workspace, you can push a skill to everyone automatically once it's built, so nobody has to install it themselves — same effect as everyone's Claude Code project shipping with the same `.claude/skills/` folder already in it.
