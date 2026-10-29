# Finance Research Guidelines

A Codex skill for scholarly finance and economics research. It keeps research execution aligned with the assigned economic question and ordered substantive task, protects completed research stages from repeated unproductive work, and emphasizes measurement validity, empirical inference, and manuscript contributions.

## Contents

- `skill/finance-research-guidelines/SKILL.md` — the research discipline and action-selection rules.
- `skill/finance-research-guidelines/agents/openai.yaml` — skill metadata.

## Install for Codex

```sh
git clone https://github.com/azazhang/finance-research-guidelines-skill.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/finance-research-guidelines-skill/skill/finance-research-guidelines" ~/.codex/skills/finance-research-guidelines
```

For standing application to academic research, add this instruction to `~/.codex/AGENTS.md`:

> For all academic finance and economics research, read and apply the installed `finance-research-guidelines` skill at the beginning of research execution and keep it active when selecting subsequent substantive actions. Follow the current user instructions and the project's authorized ordered plan.

The skill complements project-specific research instructions and the separately installed `finance-literature-review` and `finance-paper-writing` skills.

## License

MIT.
