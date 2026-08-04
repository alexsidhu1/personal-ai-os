# Getting Started: build your second brain in ChatGPT

This is the ChatGPT version of the second brain. No coding. If you can create a folder and fill in a form, you can do this.

Set aside about 30 minutes. By the end you'll have a ChatGPT Project that knows who you are, what you're working on, and how you write, and that gets sharper every time you use it.

Five steps:

1. Download this template
2. Fill in your details
3. Create a ChatGPT Project
4. Paste the instructions and upload your files
5. Use it

You need a ChatGPT **Plus, Team, Business, or Enterprise** plan. Projects aren't available on the free plan.

---

## Step 1: Download this template

1. Go to **[github.com/alexsidhu1/chatgpt-second-brain](https://github.com/alexsidhu1/chatgpt-second-brain)**.
2. Click the green **Code** button near the top.
3. Click **Download ZIP**.
4. Find the downloaded ZIP file (usually in your Downloads folder) and double-click it to unzip.
5. You now have a folder called `chatgpt-second-brain`. Move it somewhere you'll remember, like your Desktop or Documents. You can rename it to anything you like.

No GitHub account needed. You're just downloading a folder.

---

## Step 2: Fill in your details

Open these files in any text editor (Notepad, TextEdit, Google Docs, whatever you've got) and replace the `[bracketed placeholders]` with your real information:

1. **`context/me.md`** — who you are, your role, how you work.
2. **`context/work.md`** — what your business does, your offers, your clients.
3. **`context/team.md`** — who's on your team and what to loop them in for.
4. **`context/current-priorities.md`** — what matters in the next 30 days.
5. **`context/goals.md`** — your targets for the quarter.

Be specific. "I run a business" is useless. "I manage a 40-property commercial portfolio out of the LNS office, mostly landlord-side leasing" is gold. The detail is the whole point.

**Don't have ChatGPT open yet to do this part.** Filling in files by hand works fine here since there's no assistant-led interview step like the Claude Code version. If you'd rather be interviewed, you can do that inside your Project once it exists (see Step 5).

---

## Step 3: Create a ChatGPT Project

1. In ChatGPT, go to the sidebar and click **Projects → New project**.
2. Name it something like "My Second Brain" or your name.
3. Open the project.

---

## Step 4: Paste the instructions and upload your files

1. Open **`INSTRUCTIONS.md`** from this template, copy the whole thing.
2. In your Project, click the settings/instructions area (the pencil or "Add instructions" prompt) and paste it in.
3. Click **Add files** (or the file/paperclip icon in the project) and upload every file from `context/`, plus `decisions/log.md` and `references/README.md`.

ChatGPT will search these files automatically whenever they're relevant to what you ask, inside this Project.

To check it's working, start a new chat inside the Project and type:

> Based on the files you have, tell me in one sentence what you understand about me so far.

---

## Step 5: Use it

Every chat inside this Project now has your context. Try:

- "Draft an email to a client who went quiet, in my voice."
- "What are my top priorities this week, and what should I ignore?"
- "I'm thinking about hiring a salesperson. Talk it through with me using what you know about my business."

**Want the interview instead of filling in files by hand?** Start a chat in the Project and say:

> Interview me one question at a time to fill in my context: who I am, what my business does, my team, my current priorities, and my goals. After each answer, write out the updated file content for me so I can paste it back in.

It'll write out the file text for you to copy into the actual file and re-upload (ChatGPT can't edit the files directly the way Claude Code can).

**Log decisions.** When you make a real call, ask it to draft a decision log entry in the format already in `decisions/log.md`. Paste the entry in and re-upload the file so it's there for next time.

**Keep files current.** Every so often (weekly is a good habit), re-upload updated versions of `context/current-priorities.md` and `decisions/log.md` so the Project isn't working off stale information.

---

## The honest limits, vs. the Claude Code version

This gets you 80% of the value with none of the setup. What it can't do:

- **It won't edit its own files.** You copy and re-upload. Claude Code writes directly to disk.
- **No skills or agents.** Repeatable workflows stay one-off prompts here, they can't be saved as a reusable recipe the way `.claude/skills/` works in Claude Code.
- **Memory is separate and thinner.** ChatGPT's own Memory feature (Settings → Personalization) picks up bits it decides are worth remembering, but it's not the same as this folder and doesn't export or travel with it.

If any of those start to matter, that's the point to move to Claude Code.

---

## Stuck?

Ask ChatGPT directly, inside the Project: "I followed the getting started guide and X isn't working, help me debug it." It can see your uploaded files and instructions, so it can usually tell you what's missing.

Built by Alex Sidhu (Whitehorse AI). More at [alexsidhu.com](https://alexsidhu.com).
