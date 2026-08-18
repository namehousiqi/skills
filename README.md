# Skills

Personal AI coding skills for repeatable development workflows.

## Included Skills

### hsq-develop

A single-entry Vibe Coding workflow that adapts to diagnosis, feature delivery,
bug fixing, performance analysis, code review, Git operations,
API/configuration design, frontend changes, and automated verification.

The workflow emphasizes first-principles reasoning, root-cause evidence,
impact analysis, backward compatibility, state correctness, focused
verification, safe delivery, and concise behavior-oriented summaries. It acts
as the personal process layer when specialized skills are also in use.

## Install with Skills CLI

Install from the public repository and choose the available skill interactively:

```bash
npx skills@latest add namehousiqi/skills
```

Install `hsq-develop` globally for personal use without prompts:

```bash
npx skills@latest add namehousiqi/skills@hsq-develop -g -y
```

Install it in the current project instead:

```bash
npx skills@latest add namehousiqi/skills@hsq-develop -y
```

The CLI requires Node.js `>=22.20.0`.

## Manual Install for Codex

```bash
git clone git@github.com:namehousiqi/skills.git
cp -R skills/hsq-develop ~/.codex/skills/
```

Start a new agent task and invoke the skill explicitly when needed:

```text
Use $hsq-develop to diagnose this issue without changing code yet.
```
