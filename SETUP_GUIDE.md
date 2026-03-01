# How to Build Your Own AI LinkedIn Writing Skill in Claude

A step-by-step guide. No coding needed. Takes about 3 hours.

---

## What You'll Get

An AI assistant that writes LinkedIn posts in YOUR voice. Not generic AI slop. Posts that sound like you actually wrote them.

## What You Need

- A Claude Pro account ($20/month at claude.ai). The free version won't work for this because you need Claude Projects.
- Your brain. You need to know what you sound like when you write.
- About 3 hours for the initial setup. After that, writing a post takes 10 minutes.

---

## Step 1: Get Claude Pro (5 minutes)

1. Go to [claude.ai](https://claude.ai)
2. Sign up or log in
3. Click your name (bottom left) → **Settings** → **Subscription**
4. Subscribe to Claude Pro ($20/month)
5. You now have access to **Projects**

---

## Step 2: Create a Project (2 minutes)

1. On the left sidebar, click **Projects**
2. Click **Create Project**
3. Name it something like "LinkedIn Posts"
4. You now have an empty project. This is where your skill lives.

---

## Step 3: Build Your Voice Profile (60-90 minutes)

This is the hard part. And the most important part. You need to tell Claude exactly how you sound.

Open a text file (or Google Doc, or Notion page) and write answers to these questions:

**Who are you?**
- What do you do? (job title, company, industry)
- How many years of experience?
- What's your audience on LinkedIn? (who reads your posts?)
- What topics do you post about?

**How do you sound?**
- Are you formal or casual?
- Do you use humor? What kind?
- Do you curse? How often?
- Do you use emojis? Which ones?
- Short sentences or long ones?
- Do you use bullet points? What style? (▷, -, ✅, numbers?)

**Grab 3-5 of your best LinkedIn posts.** The ones that got the most engagement. Paste them into the file. These are your voice examples.

**What do you NEVER say?** Think about phrases that would sound weird coming from you. Write them down.

**What do you ALWAYS say?** Catchphrases, repeated terms, signature expressions.

Now structure all of this into a file called something like `MY_SKILL.md`. Look at my `LinkedIn_SKILL.md` in this repo for the format. You don't need all the sections I have. Start with:

- Voice Profile (who you are, how you sound)
- Phrases you use / phrases you never use
- Post examples (paste your real posts)
- Basic writing rules (formatting preferences, length, structure)

---

## Step 4: Create the Anti-AI Layer (30-45 minutes)

This is what makes your posts not sound like AI wrote them. You can use my `anti-ai-writing-guide.md` directly. It's universal. The banned words and structure rules apply to everyone.

But also add your own rules:
- Words YOU would never use (even if they're not on my banned list)
- Formatting rules specific to your style
- Things that bug you about AI writing

Save this as a separate file or add it to your skill file.

---

## Step 5: Upload Files to Your Project (5 minutes)

1. Open your "LinkedIn Posts" project in Claude
2. Click the **Knowledge** section (or the paperclip/upload area in project settings)
3. Upload your files:
   - Your skill file (voice profile, writing rules, examples)
   - The anti-AI guide (you can use mine directly)
   - Any other reference files (post examples, content calendar, etc.)

---

## Step 6: Add Project Instructions (10 minutes)

In your project settings, there's a field called **Custom Instructions** (or **Project Instructions**).

This tells Claude HOW to behave. Not what your voice sounds like (that's in the uploaded files), but what to do when you talk to it.

Here's a starter template you can copy and adjust:

```
You are my LinkedIn post writing assistant. Follow the skill file exactly.

When I say "write a post about [topic]", write a full LinkedIn post. Don't ask questions. Just write it.

Output the post text ready to copy-paste. No code blocks. No markdown.

After every post, tell me:
- Character count
- Post type
- Whether it passes the anti-AI check

Rules:
- Use my voice from the skill file. Not generic AI voice.
- Never use words from the banned list.
- One thought per line. Posts must breathe.
- Include real numbers and specific details when possible.
- Take a clear stance. Don't hedge everything.
```

Customize this based on what you need. My full project instructions are in `LinkedIn PROJECT_INSTRUCTIONS to paste.md` in this repo.

---

## Step 7: Test It (15 minutes)

Start a conversation in your project and try:

1. "Write a post about [something you recently experienced at work]"
2. Read the output. Does it sound like you?
3. If not, tell Claude what's wrong: "That's too formal" or "I would never say 'crucial'" or "Make it shorter"
4. Each correction helps you figure out what to add to your skill file

Do this 5-10 times. Each time, update your skill file with new rules based on what Claude gets wrong.

---

## Step 8: Set Up a Weekly System (optional, 30 minutes)

If you post regularly, build a workflow:

1. **Pick your posting days.** (I do Tuesday, Wednesday, Thursday)
2. **Create a content backlog.** A simple list of post ideas in Notion, Google Sheets, or even a text file.
3. **Plan weekly.** Every Sunday, pick 3 topics from your backlog.
4. **Write daily.** Open Claude, say "write Tuesday's post about [topic]", review, post.

My full weekly system is in `linkedin-weekly-system.md`.

---

## How to Improve It Over Time

Your skill gets better the more you use it. After every post:

- Did Claude use a word you'd never say? Add it to the banned list.
- Did the structure feel off? Add a new rule.
- Did a post perform really well? Add it as an example.
- Did Claude miss your tone? Sharpen the voice profile.

Think of your skill file as a living document. It's never "done."

---

## Common Mistakes

**"I uploaded my files but Claude ignores them."**
Make sure you're starting conversations INSIDE the project, not in regular Claude chat. The project files only work inside the project.

**"The posts still sound like AI."**
Your voice profile probably isn't specific enough. Add more real examples. Add more banned words. Be more explicit about your tone. "Casual" isn't enough. "Like a voice memo I'd send to a friend about something that pissed me off at work" is better.

**"Claude keeps using the same structure."**
Add a rule like: "Never start with a generic intro. Never end with a summary. Start mid-story. End with the punchline." AI has strong default patterns. You need explicit rules to break them.

**"My posts are too long / too short."**
Add a character target to your rules. "Aim for 1,000-1,300 characters for story posts."

---

## Time Investment

| What | How Long |
|---|---|
| Initial setup (Steps 1-6) | ~3 hours |
| Testing and refining (Step 7) | ~30 minutes |
| Weekly planning | ~15 minutes on Sunday |
| Writing a single post | ~10 minutes |
| Ongoing skill improvements | ~5 minutes per week |

After the initial 3 hours, you're looking at roughly 45 minutes per week for 3 polished LinkedIn posts. Not bad.

---

## Questions?

Open an issue on this repo or connect with me on [LinkedIn](https://www.linkedin.com/in/mariankamenistak/).
