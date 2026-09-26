# Claude Skills

Custom Agent Skills for Claude Code / Claude.ai.

No unlimited API magic. Just real workflows.

## Skills

- `error-explainer/` — Turns cryptic stack traces and API errors into plain English + fixes.

## Install (Claude Code)

```bash
# personal
cp -r error-explainer ~/.claude/skills/

# or project
cp -r error-explainer .claude/skills/
```

Then in Claude Code: `/error-explainer` or just paste an error.

## Structure

Every skill is a folder with `SKILL.md` (YAML frontmatter + instructions). Optional `scripts/`, `references/`, `assets/`.
