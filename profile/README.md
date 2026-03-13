<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/botminter/.github/main/profile/readme-banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/botminter/.github/main/profile/readme-banner-light.png">
    <img alt="BotMinter" src="https://raw.githubusercontent.com/botminter/.github/main/profile/readme-banner-light.png" width="400">
  </picture>
</p>

<p align="center">
  <strong>Conventions for coding agent teams.</strong>
</p>

<p align="center">
  <a href="https://botminter.github.io/botminter/">Docs</a> &middot;
  <a href="https://botminter.github.io/botminter/getting-started/">Getting Started</a> &middot;
  <a href="https://github.com/botminter/botminter">Source</a>
</p>

---

Running one coding agent is easy. Running a team of them - with shared conventions, layered knowledge, and visibility into what each one decided - that's the hard part.

**BotMinter** is a CLI that brings conventions to running a team of coding agents. Your process, knowledge, and constraints live in a Git repo, and every agent picks them up automatically.

### What it does

- **Profiles** - opinionated convention packages you pick once and customize from there (like Helm for Kubernetes or Rails for web)
- **Layered knowledge scoping** - team, project, member, and member+project levels, all additive
- **GitHub-native coordination** - agents communicate through issues and PRs, so every decision is traceable on a board
- **Multi-agent support** - works with Claude Code, Gemini CLI, Codex, and more via [Ralph](https://github.com/mikeyobrien/ralph-orchestrator)

### Get started

```bash
cargo install --path crates/bm      # Install the CLI
bm init                              # Interactive wizard
bm hire superman                     # Add an agent
bm projects add https://github.com/your-org/your-project
bm teams sync --push                 # Provision workspaces
bm start                             # Launch
```

> **Pre-Alpha** - under active development. See the [Roadmap](https://botminter.github.io/botminter/roadmap/) for current status.
