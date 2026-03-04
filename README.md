# Cursor Skills

A collection of [Cursor Agent Skills](https://cursor.com/docs/context/skills) you can reuse across projects or share with your team.

## Skills

| Skill | Description |
|-------|-------------|
| [abacus-ai](abacus-ai/) | Abacus.AI API & platform: RouteLLM (chat, tools, image gen), datasets, document retrievers, knowledge bases |

## How to use

### In a project

Copy the skill folder into your project’s Cursor skills directory:

```bash
# From this repo root
cp -r abacus-ai /path/to/your-project/.cursor/skills/
```

Or clone this repo and symlink/copy the skills you need into `.cursor/skills/`.

### Personal (all projects)

Copy into your user skills directory:

```bash
mkdir -p ~/.cursor/skills
cp -r abacus-ai ~/.cursor/skills/
```

Restart Cursor (or reload the window) so it picks up the skill.

## Adding skills

Each skill is a folder containing at least `SKILL.md` (YAML frontmatter + instructions). Optional: `reference.md`, `examples.md`, or `scripts/`. See [Cursor’s skill docs](https://cursor.com/docs/context/skills) for the format.

## License

Use and adapt these skills as you like. API-specific content (e.g. Abacus.AI) follows the respective service’s terms and documentation.
