# GitHuman Skills

Claude Code skills for [GitHuman](https://github.com/mcollina/githuman) - review AI-generated code changes before committing.

## Usage

This repository provides skills that can be used with Claude Code. See the [GitHuman documentation](https://github.com/mcollina/githuman) for usage instructions.

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
