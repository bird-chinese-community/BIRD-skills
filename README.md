# BIRD Agent Skills

This repository hosts agent skills for BIRD routing configuration, editor setup, and CI/CD workflows.

## Skills

- [`bird-agent`](./bird-agent) — Write, validate, format, and debug BIRD (BIRD1/2/3) routing
  daemon configuration files.
- [`birdcc-installer`](./birdcc-installer) — Install BIRD editor support and the `birdcc`
  command-line toolkit.
- [`birdcc-cicd`](./birdcc-cicd) — Add the `setup-birdcc` GitHub Action to CI/CD workflows.

## Usage

These skills follow the [Agent Skills](https://agentskills.io/)
convention. Each skill includes:

- `SKILL.md` — Skill manifest and usage instructions
- `agents/openai.yaml` — OpenAI agent invocation metadata
- `scripts/` — PEP 723 stdlib-only helper scripts runnable with `uv run`
- `references/` — Focused reference guides

## License

Same as the BIRD-LSP project.
