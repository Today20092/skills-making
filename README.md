> **Moved:** This skill is now maintained in [Today20092/skills](https://github.com/Today20092/skills). Install and update it from that repository. This repository is retained for existing links and historical reference.

# Skills Making

A growing collection of focused agent skills: small, reusable workflows that help people get specific work done in their projects.

## Install a skill

Install the AGENTS.md field study review with the [`skills` CLI](https://github.com/vercel-labs/skills):

```sh
npx skills add Today20092/skills --skill agents-md-field-study
```

The CLI will ask which supported coding agent to install it for. Add `--global` to install it for your user account instead of the current project.

## Skills

| Skill | What it does |
| --- | --- |
| [`agents-md-field-study`](skills/agents-md-field-study/SKILL.md) | Reviews a project's `AGENTS.md` files against Coldtea's study of the 100 most-starred GitHub repositories that have one. It presents evidence-based recommendations, then helps apply the ones you choose. |

Skills are user-invoked and focused on one workflow. Each skill lives in its own directory under `skills/`; its `SKILL.md` explains when and how to use it. More project-specific skills will be added here over time.

## Add a skill

Create a directory under `skills/` with a `SKILL.md` containing a lowercase, hyphenated `name`, a concise `description`, and the workflow instructions. Keep supporting research in a linked reference file when it helps the skill make better decisions. Add the skill to the table above with a one-sentence description.

## Source

The AGENTS.md review draws on [Coldtea's AGENTS.md field study](https://www.coldtea.ai/blog/agents-md-field-study). Its findings describe practices observed in large repositories; they are prompts for project-specific recommendations, not universal requirements.
