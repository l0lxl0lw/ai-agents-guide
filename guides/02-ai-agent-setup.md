# Guide 02: AI Agent Setup

> "A journey of a thousand miles begins with a single step." — Lao Tzu

In this guide, you'll set up your first AI agent project. By the end, you'll have a project folder, a GitHub repository, and a working development workflow.

---

## What is Vibe Coding?

Vibe coding is a new way to build software. Instead of writing every line of code yourself, you describe what you want in plain language and an AI agent writes the code for you.

You speak. The AI codes. You review. Together, you build.

This doesn't mean you need zero knowledge — understanding what you're asking for and reviewing what the AI produces is still important. But the barrier to entry has dropped dramatically. If you can describe what you want clearly, you can build software.

---

## Step 1: Create Your Project Folder

Your project needs a home. Let's create one.

### Using Terminal

Open your terminal and run:

```bash
mkdir ~/my-first-agent
cd ~/my-first-agent
```

This creates a folder called `my-first-agent` in your home directory and moves into it.

<!-- Screenshot: Terminal creating project folder -->

### Using Cursor

Alternatively, you can create the folder through Cursor:

1. Open Cursor.
2. Click **File > Open Folder**.
3. Navigate to where you want your project (your home folder or Desktop works fine).
4. Click **New Folder**, name it `my-first-agent`, and open it.

<!-- Screenshot: Cursor open folder dialog -->

---

## Step 2: Set Up GitHub

### What is GitHub?

GitHub is where developers store and share code. Think of it as Google Drive, but for code. It keeps a complete history of every change you make, so you can always go back to a previous version.

### Why Version Control Matters

When you're building with AI agents, things can change fast. Version control (git + GitHub) gives you a safety net:

- **Undo mistakes**: Go back to a working version if something breaks.
- **Track progress**: See exactly what changed and when.
- **Share your work**: Others can see, use, and contribute to your project.

### Create a GitHub Account

If you don't have one already:

1. Go to [github.com](https://github.com/) and click **Sign up**.
2. Follow the prompts to create your account.
3. Verify your email address.

<!-- Screenshot: GitHub signup page -->

### Initialize Your Repository

Back in your terminal (inside your project folder):

```bash
git init
```

This turns your folder into a git repository. Now git will track all changes you make.

<!-- Screenshot: Terminal running git init -->

---

## Step 3: Create Your First AI Agent Project

Now let's bring it all together.

### Open Your Project in Cursor

1. Open Cursor.
2. Go to **File > Open Folder** and select your `my-first-agent` folder.

<!-- Screenshot: Cursor with empty project folder open -->

### Start Claude Code

Open Cursor's integrated terminal (`Ctrl+`` ` or **View > Terminal**) and start Claude Code:

```bash
claude
```

<!-- Screenshot: Claude Code running inside Cursor's terminal -->

### Scaffold Your Project

Now you can talk to Claude Code to build your project. Try something like:

```
> Create a simple web page that says "Hello, I was built by an AI agent!" with some nice styling
```

Claude Code will:
1. Create the necessary files (HTML, CSS, maybe JavaScript).
2. Explain what it's doing along the way.
3. Ask for your approval before making changes.

<!-- Screenshot: Claude Code generating files -->

### Review and Accept Changes

Claude Code shows you exactly what it wants to create or modify. Review the proposed changes:

- **Accept** if it looks good.
- **Ask for changes** if you want something different.
- **Reject** if you want to start over.

This review loop is the core of vibe coding: you guide, the AI executes, you verify.

<!-- Screenshot: Claude Code showing proposed changes -->

---

## The Basic Workflow

Here's the workflow you'll use from now on:

1. **Describe** what you want to build or change in plain language.
2. **Review** what the AI agent proposes.
3. **Accept or adjust** until you're happy with the result.
4. **Save your progress** with git:

```bash
git add .
git commit -m "Add initial project files"
```

5. **Repeat** for the next feature or change.

<!-- Screenshot: Terminal showing git commit -->

---

## What's Next?

You now have a working setup:
- **Cursor** for editing and viewing your code
- **Claude Code** for AI-powered development
- **Git** for tracking your changes

From here, you can start building anything. Describe your ideas to Claude Code and watch them come to life.

Check back for future guides on building web apps, debugging, and deploying your projects.
