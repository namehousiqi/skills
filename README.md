# Skills

Personal Codex skills for repeatable development workflows.

## Included Skills

### hsq-develop

A single-entry Vibe Coding workflow that adapts to diagnosis, implementation,
performance analysis, code review, Git operations, API/configuration design,
and Docker/Kubernetes troubleshooting.

The workflow emphasizes root-cause evidence, impact analysis, backward
compatibility, state correctness, focused verification, and safe delivery.

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

## Manual Install

```bash
git clone git@github.com:namehousiqi/skills.git
cp -R skills/hsq-develop ~/.codex/skills/
```

Start a new Codex task and invoke the skill explicitly when needed:

```text
Use $hsq-develop to diagnose this issue without changing code yet.
```
