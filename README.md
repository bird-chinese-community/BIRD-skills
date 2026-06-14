# BIRDCC Agent Skills

This repository hosts agent skills for the BIRD Chinese Community ecosystem.

## Skills

- [`bird-agent`](./bird-agent) — Work with BIRD (BIRD1/2/3) routing daemon
  configurations, diagnostics, formatting, and validation.
- [`birdcc-installer`](./birdcc-installer) — Help users install BIRDCC editor
  plugins, CLI tooling, and CI integrations.

## Usage

These skills follow the [Agent Skills](https://agentskills.io/)
convention. Each skill includes:

- `SKILL.md` — Skill manifest and usage instructions
- `agents/openai.yaml` — OpenAI agent invocation metadata
- `scripts/` — PEP 723 stdlib-only helper scripts runnable with `uv run`
- `references/` — Focused reference guides

## License

Same as the BIRD-LSP project.
