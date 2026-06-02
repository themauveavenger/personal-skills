# AGENTS.md

## Scope

This repository contains reusable skills for any agent harness or model. Each skill is self-contained in its own directory under `skills/`.

## Skill structure

- Each skill lives in its own directory under `skills/` (e.g., `skills/oracle-reviewer/`)
- Each skill contains a `SKILL.md` file with frontmatter (name, description) and instructions
- Skills are minimalist—avoid bundling unrelated logic or instructions into one skill
- Skills may include supporting files (templates, examples, bundled resources) alongside `SKILL.md`

## Adding new skills

1. Create a new directory: `skills/{skill-name}/`
2. Add `SKILL.md` with frontmatter and content
3. Update `README.md` with a brief description if useful
4. Keep each skill focused on a single, well-defined use case

## No hidden conventions

- No required boilerplate headers or CI/CD
- No complex tooling setup required
- Assume minimal dependencies; keep skills portable
