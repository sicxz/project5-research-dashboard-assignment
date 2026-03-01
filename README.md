# Project #5 // Build a Research Dashboard Site for Project 2

## Overview
Project 2 is large. Research links, prompts, notes, and experiments can get scattered fast.

In this assignment, you will build a single, living research dashboard site to run Project 2 from one place.

Workflow:
- **ChatGPT, Claude, or Gemini:** Converse + ideate
- **AntiGravity, Codex, or Claude Code:** Build + create + make
- **GitHub Pages:** Deploy live

## What You Are Building
A static research dashboard site (`HTML`, `CSS`, `JS` only) that supports:
- Tracking readings and sources
- Logging prompts and AI outputs
- Documenting experiments and iterations
- Keeping project goals, research question, and weekly plan visible
- Linking out to Milanote and related tools

## Hard Requirements
- Static only (`HTML`, `CSS`, `JS`)
- No server and no external database
- Data saved with `localStorage`
- Must be deployed on GitHub Pages
- Must look intentionally designed (not generic default AI output)

## Before You Start
Install or confirm:
- Modern browser (Chrome, Firefox, Edge)
- AntiGravity: <https://antigravity.google/>

## Step 1: Converse and Ideate (Prompt Design)
Use at least one of: ChatGPT, Claude, or Gemini.

Goal: design a prompt that generates a dashboard aligned to your Project 2 focus.

Paste this prompt into your model:

```text
My Project 2 Deep Dive focus is: [ write this in here ]

My research is about/my question is: [ write it in here ]

I need you to help me write a strong AntiGravity prompt to generate a static research dashboard website.

The dashboard must:

Be HTML, CSS, JS only

Use localStorage

Have an opinionated layout that feels like a research command center

Include sections for:

Project overview (focus, question, goals)

Reading library (sources with title, author, link, tags, status, notes)

Weekly plan (Week 5 to Week 11 milestones)

Prompt log (prompt, model used, output summary, what I changed next)

Experiment log (what I tried, screenshots or notes, outcome, next step)

Links (Milanote board, GitHub repo, tool links)

Ask me 5 sharp questions first to clarify what I want.

Then produce:

A single polished AntiGravity build prompt I can paste in

A checklist of features to verify after generation
```

Save this conversation. You will submit it as evidence.

## Step 2: Build the Dashboard with AntiGravity
1. Create folder: `research-dashboard`
2. Open AntiGravity
3. Paste the build prompt from Step 1
4. Generate files
5. Confirm `index.html` is in the root
6. Open `index.html` and test

### Minimum Functionality Checklist
- Add, edit, and delete Reading Library items
- Add Prompt Log entries
- Add Experiment Log entries
- Data persists after refresh (`localStorage` works)
- Links section works
- Layout is readable and structured

## Step 3: Make It Feel Like You (Required)
You must intentionally design this. No default AI visual style.

Use art direction detailed enough to design from.

### Required Art Direction Parts
- Theme name
- Typography direction (serif/sans, mono/proportional, scale)
- Layout system (grid, cards, columns, left nav)
- UI tone (sterile, warm, aggressive, calm, academic)
- Color direction (contrast, light/dark, accent usage)

Minimum: 5 clear bullets and at least one reference image.

Use this AntiGravity redesign prompt after core features work:

```text
Redesign the UI to match my art direction below. Keep all existing functionality working.

Art direction:

Theme: [NAME IT]

Layout: [describe structure: sidebar, panels, card grid, dense list, etc.]

Typography: [font types, scale, hierarchy expectations]

Color: [background, surface, text contrast, accent usage]

Components: [buttons, inputs, tabs, tags, cards, etc.]

Interaction: [hover, focus, active states, subtle motion yes/no]

Constraints:

Do not change the data structure or break the localStorage.

Improve spacing, alignment, and hierarchy.

Make section headers and navigation feel intentional.

Keep it fast: no heavy frameworks.
```

## Step 4: Add at Least 2 Feature Upgrades
Pick at least two from this list, and invent/develop one of your own.

1. Tags and filtering
2. Status tracking
3. Search
4. Theme switcher
5. Drag-and-drop ordering
6. Export/import JSON
7. Weekly checkpoint timeline (Week 5 to Week 11)

## Step 5: Push to GitHub and Deploy
Use GitHub Desktop (recommended).

### GitHub Desktop Flow
1. `File` -> `Add Local Repository...`
2. Choose `research-dashboard`
3. Create repository
4. Publish repository as **Public**
5. Commit and push updates

### Deploy to GitHub Pages
1. Repo `Settings` -> `Pages`
2. Source: `Deploy from a branch`
3. Branch: `main`, folder: `/ (root)`
4. Wait a few minutes
5. Confirm live URL works

## Submission (Canvas)
Submit these items to a Milanote board:
1. Live URL (GitHub Pages)
2. Repo URL (GitHub repository)
3. Screenshot of dashboard home view
4. Research materials (prompts, references, notes)
5. Reflection (6-10 sentences) answering:
   - What problem does your dashboard solve for your Project 2 workflow?
   - What did you use ChatGPT/Claude/Gemini for?
   - What did AntiGravity get wrong, and how did you fix it?
   - Which two upgrades did you implement, and why?

## Prompt Evidence
Include screenshots or exported text from your ideation chat and your AntiGravity prompt iterations.

## Checklist
- [ ] ✅ Ideation chat completed and saved
- [ ] ✅ Dashboard core features work
- [ ] ✅ Visual design is intentional and custom
- [ ] ✅ 2+ upgrades are implemented
- [ ] ✅ Repo is public and deployed
- [ ] ✅ Submission package is complete
