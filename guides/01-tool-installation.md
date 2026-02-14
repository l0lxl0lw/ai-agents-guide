# Guide 01: Tool Installation

In this guide, you'll install the two main tools for AI agent development:

1. **Cursor** - An AI-powered code editor
2. **Claude Code** - Anthropic's CLI for Claude

By the end, both tools will be installed and ready to use.

---

## Part 1: Install Cursor

### What is Cursor?

Cursor is a code editor built on top of VS Code with AI features built in. It lets you write, edit, and understand code with the help of AI — right inside the editor.

### Step 1: Download Cursor

Go to [cursor.com](https://www.cursor.com/) and click the download button for your operating system.

<!-- Screenshot: Cursor download page -->

### Step 2: Install Cursor

**Mac:**
1. Open the downloaded `.dmg` file.
2. Drag the Cursor icon into your Applications folder.
3. Open Cursor from Applications.

**Windows:**
1. Run the downloaded `.exe` installer.
2. Follow the installation wizard prompts.
3. Launch Cursor from the Start menu.

**Linux:**
1. Run the downloaded `.AppImage` file, or extract the `.tar.gz` archive.
2. Launch Cursor from the extracted folder.

<!-- Screenshot: Cursor installation on Mac -->

### Step 3: Initial Setup

When you first open Cursor, it will walk you through a quick setup:

1. Choose your theme (light or dark).
2. Select your preferred keybindings (VS Code defaults are fine).
3. Sign in or create a Cursor account.

<!-- Screenshot: Cursor initial setup screen -->

### Step 4: Connect GitHub

Connecting GitHub lets you save your work and collaborate:

1. Open Cursor's command palette (`Cmd+Shift+P` on Mac, `Ctrl+Shift+P` on Windows/Linux).
2. Type "GitHub: Sign In" and select it.
3. Follow the browser prompts to authorize Cursor.

<!-- Screenshot: GitHub sign-in from Cursor -->

Cursor is now ready. Let's move on to Claude Code.

---

## Part 2: Install Claude Code

### What is Claude Code?

Claude Code is Anthropic's command-line tool that lets you work with Claude directly in your terminal. You can use it to generate code, edit files, run commands, and build entire projects through conversation.

### Step 1: Install Node.js

Claude Code requires Node.js version 18 or higher.

1. Go to [nodejs.org](https://nodejs.org/) and download the LTS (Long Term Support) version.
2. Run the installer and follow the prompts.
3. Verify the installation by opening your terminal and running:

```bash
node --version
```

You should see a version number like `v20.x.x` or higher.

<!-- Screenshot: Node.js download page -->
<!-- Screenshot: Terminal showing node version -->

### Step 2: Install Claude Code

Open your terminal and run:

```bash
npm install -g @anthropic-ai/claude-code
```

Wait for the installation to complete.

<!-- Screenshot: Terminal running npm install -->

### Step 3: Authenticate

Claude Code requires a Claude Pro, Max, or Team subscription.

1. Run Claude Code for the first time:

```bash
claude
```

2. It will open your browser for authentication.
3. Sign in with your Anthropic account.
4. Authorize Claude Code when prompted.

<!-- Screenshot: Claude Code authentication in browser -->

### Step 4: Verify Installation

After authentication, Claude Code will start an interactive session. You should see a prompt where you can type messages to Claude.

Try a quick test:

```
> What can you help me with?
```

Claude should respond with a helpful summary of its capabilities.

<!-- Screenshot: Claude Code first run in terminal -->

Type `/exit` to close the session when you're done.

---

## What's Next?

Both tools are installed and ready. Head to [Guide 02: AI Agent Setup](02-ai-agent-setup.md) to create your first AI agent project.
