# Guide 03: Project Planning and Preparation

> Before you write a single line of code, take a step back and plan. The best AI agents start with a clear purpose.

In this guide, you'll install one more tool (Playwright for browser automation) and define exactly what you're going to build. By the end, you'll have a project brief that serves as the blueprint for your AI agent.

---

## Step 1: Install Playwright

### What is Playwright?

Playwright is a browser automation tool. It lets your AI agent open web pages, click buttons, fill out forms, and extract information — just like a person would, but automatically.

Many AI agent projects need to interact with websites. Playwright makes that possible.

### Install Playwright

Make sure you're inside your project folder, then run:

```bash
npm install -D playwright
```

This adds Playwright to your project as a development dependency.

<!-- Screenshot: Terminal running npm install playwright -->

Next, install the Chromium browser that Playwright uses:

```bash
npx playwright install chromium
```

This downloads a version of Chromium that Playwright controls. It won't affect your regular browser.

<!-- Screenshot: Terminal running playwright install chromium -->

### Verify the Installation

Let's confirm everything works. Run:

```bash
npx playwright --version
```

You should see a version number like `1.x.x`. If you see it, Playwright is ready.

<!-- Screenshot: Terminal showing playwright version -->

---

## Step 2: Define Your Project

Before building, answer four questions. These aren't technical — they're about purpose.

Grab a piece of paper, open a notes app, or just think carefully. The clearer your answers, the better your AI agent will be.

### Question 1: What problem does it solve?

Every useful project solves a problem or provides value. Be specific.

- Bad: "I want to make a cool website."
- Good: "I want a tool that checks competitor prices daily and alerts me when they drop."

Ask yourself: If this project worked perfectly, what would it do for someone?

### Question 2: Who is it for?

Define your target audience. This shapes every decision you'll make.

- Is it for you personally?
- For a specific group of people (freelancers, students, small business owners)?
- For a broad audience?

The more specific you are, the more focused your project will be.

### Question 3: How will people find and use it?

Think about distribution. A great tool nobody can find is a tool nobody uses.

- Will you share it on social media?
- Is it a web app people access through a browser?
- Will you list it on a marketplace or directory?
- Is it a personal tool just for you?

### Question 4: What happens after someone uses it?

Think beyond the first interaction. What's the next step?

- Do they come back daily? Weekly?
- Is there a premium version or upgrade path?
- Do they share it with others?
- Does it lead them to another product or service?

---

## Step 3: Write Your Project Brief

Now turn those answers into a simple one-page document. This becomes the instruction set for your AI agent.

### Create Your Brief

Create a file called `PROJECT.md` in your project folder. Here's a template:

```markdown
# Project Brief

## What It Does
[One or two sentences describing what the project does and what problem it solves.]

## Who It's For
[Describe the target audience.]

## How People Find It
[List the main channels or distribution strategy.]

## What Happens Next
[Describe what happens after someone uses it — retention, next steps, etc.]

## Key Features
- [Feature 1]
- [Feature 2]
- [Feature 3]

## Success Looks Like
[Describe what a successful version of this project looks like.]
```

### Example

Here's a filled-in example:

```markdown
# Project Brief

## What It Does
A web app that monitors competitor product prices and sends a daily email
summary highlighting any price drops.

## Who It's For
Small e-commerce business owners who want to stay competitive on pricing.

## How People Find It
Direct outreach in e-commerce communities and a landing page with SEO.

## What Happens Next
Free tier tracks 5 products. Paid plan ($9/month) tracks unlimited products
with instant alerts.

## Key Features
- Add competitor product URLs to track
- Daily email digest with price changes
- Dashboard showing price history over time

## Success Looks Like
100 users tracking prices within the first month, with 10% converting to paid.
```

### Save It

Save your `PROJECT.md` in your project's root folder. When you're ready to build, you can give this file directly to Claude Code as context:

```
> Read PROJECT.md and help me build this project step by step
```

The more thought you put into your brief, the better the AI agent can help you build it.

---

## What's Next?

You now have:
- **Playwright** installed for browser automation
- **A clear project plan** written down as a brief
- **A workflow** for going from idea to instruction

You're ready to start building. Check back for future guides where we'll take your project brief and turn it into a working application.
