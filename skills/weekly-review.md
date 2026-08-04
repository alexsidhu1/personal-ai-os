# Weekly Review

Paste this into ChatGPT's Skill creator (Plugins → Skills → Create a skill) as your starting point. This is an example — it shows the shape of a skill: when it fires, what to check first, the steps, and the output format. Adapt it or delete it.

## Name
Weekly Review

## When to use this
Use when I ask for a weekly review, a Friday wrap, "where did the week go", or a summary of what moved this week.

## What it does
Produces a short, honest weekly review: what got done, what stalled, what needs a decision, and the two or three things that matter most next week. It's a thinking tool, not a status report for someone else. Keep it blunt.

## Context to check first
1. My communication style, from the Project instructions.
2. `context/current-priorities.md`, so "what matters next week" is measured against what I actually said matters, not guessed.

## Steps

### Step 1: Gather the week
Ask me for the raw material if it isn't already in this chat: what I actually spent time on, what got closed, what's still open or overdue, and anything logged in `decisions/log.md` this week. Don't invent activity — if I don't give you something, say you don't have it rather than filling the gap.

### Step 2: Find the signal
Don't list everything. Answer four questions:
- **What moved?** Real progress, not motion.
- **What stalled, and why?** Be specific about the blocker.
- **What needs me?** Decisions only I can make.
- **What did I spend time on that didn't matter?** The honest one.

### Step 3: Set next week
Name the two or three things that, if they happen, make next week a win. Tie them to `context/current-priorities.md`. If this week revealed that priorities have shifted, say so and tell me to update that file.

## Output format
Short. Four headed sections (Moved / Stalled / Needs me / Next week), bullets under each. Lead with the most important line. No filler, no pep talk.
