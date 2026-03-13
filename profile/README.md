<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/botminter/.github/main/profile/readme-banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/botminter/.github/main/profile/readme-banner-light.png">
    <img alt="BotMinter" src="https://raw.githubusercontent.com/botminter/.github/main/profile/readme-banner-light.png" width="400">
  </picture>
</p>

<p align="center">
  A batteries-included CLI to bootstrap and manage your autonomous team of coding agents.<br>
  Claude Code, Gemini CLI, Codex, and more.
</p>

<p align="center">
  <a href="https://botminter.github.io/botminter/">Docs</a> &middot;
  <a href="https://botminter.github.io/botminter/getting-started/">Getting Started</a> &middot;
  <a href="https://github.com/botminter/botminter">Source</a>
</p>

---

You already know how to run a team - hire people into roles, give them context, define a process, check in on progress.

**BotMinter makes your coding agents work the same way.**

You hire agents into roles. You choose a workflow or create your own. You scope what each one knows. You set the guardrails. Everything lives in a Git repo, and the CLI handles the rest.

Then you watch them work, review their output, and keep refining. Tighten a constraint, add knowledge, adjust a role - day by day, your team gets sharper.

### Team roles and process

Define who does what, how work moves between agents, and what quality gates apply. Shape the workflow to match how you want your team to operate.

### Sandboxed runtime

Each agent runs in its own local workspace, isolated from the others.

### GitHub-native coordination

Agents pick up work from GitHub issues, update status with labels, and deliver through PRs. Every decision is on your board - not buried in a terminal session.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/botminter/.github/main/profile/board-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/botminter/.github/main/profile/board-light.svg">
    <img alt="GitHub project board showing agent coordination" src="https://raw.githubusercontent.com/botminter/.github/main/profile/board-light.svg" width="720">
  </picture>
</p>

### Layered knowledge and constraint scoping

From coarse-grained to fine-grained - write it once at the right scope, every relevant agent picks it up:

```
team-wide              All your agents, all projects
  └─ project-wide      All your agents on this project
      └─ member-wide   This agent, all projects
          └─ member+project   This agent, this project
```

### Human-in-the-loop communication

From full approval gates to fully autonomous. You decide how much control you keep.

---

All of this comes wired together in a **profile** - a pre-configured package you pick once and customize from there. Different profiles configure each of these axes differently.

Everything lives in a Git repo you own.

> **Pre-Alpha** - under active development. See the [Roadmap](https://botminter.github.io/botminter/roadmap/) for current status.
