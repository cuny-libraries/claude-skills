# Claude Skills — CUNY Libraries

Shared [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skills for CUNY Libraries projects.

## Available Skills

- **[Alma API](.claude/skills/alma-api.md)** — Ex Libris Alma REST API patterns, endpoints, and CUNY-specific conventions

## What Are Skills?

Skills are reference documents that give Claude Code domain-specific knowledge. When a skill is loaded into a project, Claude can use it to write better code — calling the right endpoints, following established conventions, and avoiding known pitfalls.

## Usage

Clone this repo alongside your CUNY Libraries projects:

```
cuny-libraries/
├── claude-skills/       ← this repo
├── alma-letters/
├── access-models/
├── alma-partner-sync/
└── ...
```

Then reference a skill in your project's `CLAUDE.md`:

```markdown
See ../claude-skills/.claude/skills/alma-api.md for Alma API conventions.
```

Or copy the `.claude/skills/` directory into your own project if you prefer a self-contained setup.

## Contributing

Edit the skill files, commit, and push. If you're adding a new skill, place it in `.claude/skills/` and update this README.
