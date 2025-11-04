# Obsidian + Claude Code Template

A complete Obsidian vault template optimized for networked thinking and knowledge management with Claude Code integration.

## What is This?

This template provides:
- **Pre-configured slash commands** for Claude Code (`/day`, `/new`, `/research`, `/brainstorm`, etc.)
- **Obsidian vault structure** optimized for networked thinking and graph connectivity
- **Ready-to-use templates** for daily notes and topic notes
- **CLAUDE.md instructions** that teach Claude Code how to work with your vault

## Features

### Slash Commands (`.claude/commands/`)
- `/day` - Create or open today's daily note with automated capture
- `/new` - Create new topic notes with proper structure and linking
- `/research` - Research topics and create interconnected notes
- `/brainstorm` - Generate and organize ideas into topic notes
- `/task` - Manage tasks across your vault
- `/log` - Quick logging to daily notes
- `/answer` - Answer questions using your vault knowledge
- `/save` - Save content to your vault with proper organization
- `/resource` - Add resources and references to topics

## Command Usage Guide

### `/day` - Interactive Daily Journaling
Conversational daily note creation with smart linking.
```
/day
```
Claude will ask about your day, capture key insights, and create/update today's daily note with proper `[[wiki links]]` to relevant topics.

### `/new` - Create Topic Notes
Create new atomic topic notes with proper structure.
```
/new "Machine Learning"
/new "Product Strategy"
```
Claude searches for existing related topics first, creates the new topic with the template, and adds relevant `[[links]]`.

### `/research` - Deep Research
Research any topic using web search and create linked notes.
```
/research "vector databases"
/research "startup fundraising strategies"
```
Claude performs web searches, synthesizes findings into concise topic notes with sources and related `[[links]]`.

### `/brainstorm` - Generate Ideas
Creative brainstorming using your existing vault knowledge.
```
/brainstorm "new features for my app"
/brainstorm "content ideas for next week"
```
Claude scans your vault, finds connections, and generates ideas by combining existing topics in novel ways.

### `/log` - Quick Logging
Fast logging to daily notes without conversation.
```
/log "Met with Sarah about Q4 planning"
/log "Idea: gamification for onboarding flow"
```
Claude searches for existing topics, adds entry to today's daily note with proper `[[links]]`, and creates missing topic notes if needed.

### `/answer` - Query Your Vault
Answer questions using only your vault knowledge.
```
/answer "What did I learn about React hooks?"
/answer "What are my thoughts on remote work?"
```
Claude searches your vault and provides concise answers with `[[links]]` to relevant notes. If knowledge gap exists, suggests using `/research`.

### `/task` - Task Management
Manage tasks in your `todo.md` checklist.
```
/task add "Review contract with legal team"
/task list
/task complete "Finish project proposal"
```
Claude searches vault for context, adds tasks with `[[wiki links]]` to related topics, and manages your minimal task list.

### `/save` - Git Sync
Quick git commit and push for your vault.
```
/save
```
Claude automatically fetches, pulls, commits with a smart message based on your changes, and pushes to remote.

### `/resource` - Capture Resources
Save articles, videos, or resources as linked notes.
```
/resource https://example.com/article
/resource "YouTube video about AI agents" https://youtube.com/watch?v=...
```
Claude extracts content, creates summarized resource note with key insights and `[[links]]` to related vault topics.

### Vault Structure
```
Daily Notes/   → One note per day (YYYY-MM-DD format)
Topics/        → Atomic idea notes (flat structure for max connectivity)
MOCs/          → Maps of Content - hub notes connecting topics
Templates/     → Consistent note templates
```

### Key Philosophy
- **Flat Topics folder** - No subfolders, only `[[wiki links]]` for organization
- **Aggressive linking** - Everything connects via links, not folders
- **Atomic notes** - One main idea per topic
- **Graph-first thinking** - Structure designed for Obsidian's graph view

## Getting Started

### 1. Use This Template
Click "Use this template" or clone this repository:
```bash
git clone https://github.com/ashish141199/obsidian-claude-code.git my-vault
cd my-vault
```

### 2. Customize CLAUDE.md
Open `CLAUDE.md` and replace:
- `[Your full name]` → Your actual name
- `[Your Designation]` → Your role/title (e.g., "CEO", "Product Manager", "Software Engineer")

**Find and replace:**
```
Find: [Your full name]
Replace: John Doe

Find: [Your Designation]
Replace: Product Manager
```

### 3. Open in Obsidian
1. Open Obsidian
2. "Open folder as vault"
3. Select this directory
4. Start creating notes!

### 4. Start Using Claude Code
Open your vault directory in Claude Code and try:
```
/day - Create today's daily note
/new "Product Market Fit" - Create a new topic
/research "neural networks" - Research and create interconnected notes
```

## Folder Structure

```
📁 .claude/
  📁 commands/       → Slash commands for Claude Code
📁 Daily Notes/      → Daily journals (auto-created)
📁 Topics/           → All your ideas, concepts, learnings (flat)
📁 MOCs/             → Maps of Content - hub notes
📁 Templates/        → Note templates
📄 CLAUDE.md         → Instructions for Claude Code
📄 todo.md           → Task tracking
```

## Core Principles

### 1. Link Everything
Use `[[wiki links]]` to connect notes. Don't organize by folders - organize by connections.

### 2. Keep Topics Atomic
One main idea per topic note. Break down complex ideas into smaller, linkable concepts.

### 3. Build Your Graph
As you link topics, patterns emerge in Obsidian's graph view revealing unexpected connections.

### 4. Ultra-Concise Writing
- Bullets over paragraphs
- Fragments over complete sentences
- Dense information, minimal words
- Exception: Long-form only for external deliverables

## Templates Included

**Daily Note Template**
- Today's Focus
- Notes & Thoughts
- Ideas & Insights
- Connections (links to topics)
- Quick Capture

**Topic Template**
- Core Idea
- Details & Context
- Related Topics (links)
- Insights & Questions
- Sources & References

## Claude Code Integration

The included CLAUDE.md teaches Claude Code to:
- Maintain flat Topics structure (no subfolders)
- Create atomic, well-linked notes
- Follow your personal writing style preferences
- Respect the networked thinking model
- Use proper frontmatter and metadata

## Tips for Success

✅ **Link liberally** - Any noun becomes a `[[topic]]`
✅ **Review graph weekly** - Discover new patterns
✅ **Update MOCs as needed** - They evolve with your thinking
✅ **Keep notes short** - Brevity over completeness
✅ **Create topics daily** - Build your knowledge network consistently

## Customization

Feel free to:
- Modify slash commands in `.claude/commands/`
- Adjust templates in `Templates/`
- Update CLAUDE.md with your preferences
- Add your own MOCs in `MOCs/`

## Requirements

- [Obsidian](https://obsidian.md/) (free)
- [Claude Code](https://claude.ai/code) (for slash commands)

## About the Creator

Created by **Ashish Kulkarni**, Founder & CEO of [Platoona](https://platoona.com).

**Platoona** is an AI-powered workspace where you can assemble teams of specialized AI agents, collaborate with them in real-time, automate workflows, and manage everything on an intelligent Kanban board. Think of it as your AI workforce management platform - bringing together multiple AI agents with different capabilities to tackle complex projects and streamline your work.

This template emerged from building personal knowledge management workflows integrated with AI tools like Claude Code to maximize productivity and networked thinking.

## License

MIT - Use freely for your personal knowledge management system.

---

**Questions or improvements?** Open an issue or PR!
