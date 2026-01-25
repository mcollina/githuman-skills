# GitHuman Skills

Claude Code skills for [GitHuman](https://github.com/mcollina/githuman) - review AI-generated code changes before committing.

## Installation

Add this skill to your Claude Code configuration:

```bash
# In your project directory
claude mcp add-skill mcollina/githuman-skills/skills/githuman
```

Or add it globally:

```bash
claude mcp add-skill --global mcollina/githuman-skills/skills/githuman
```

## What's Included

The GitHuman skill teaches Claude Code how to:

- Start and use the GitHuman review interface
- Stage files for review
- Manage inline comments and suggestions
- Track todos for follow-up work
- Export reviews for documentation

## Skill Structure

```
skills/githuman/
├── SKILL.md              # Main skill definition
└── rules/
    ├── installation.md   # Installing GitHuman
    ├── review-workflow.md # Complete review workflow
    ├── staging.md        # Staging files for review
    ├── cli-commands.md   # CLI command reference
    ├── todos.md          # Managing todos
    ├── comments.md       # Inline comments and suggestions
    ├── export.md         # Exporting reviews
    └── tips.md           # Best practices
```

## License

MIT
