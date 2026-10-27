# Awesome Coding Agent Orchestration [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools that run and orchestrate fleets of parallel AI coding agents (Claude Code, Codex, opencode, Cursor) as command centers, IDEs, harnesses, and dashboards.

As coding moves from one assistant to many parallel agents working across git worktrees, a new class of tooling has appeared to launch, supervise, and coordinate them. This list tracks the open and notable ones. **Stars, contributors, and last-commit badges update live** via Shields, so the activity signal stays current.

## Contents

- [Command centers & ADEs](#command-centers--ades)
- [Agentic IDEs](#agentic-ides)
- [Harnesses & frameworks](#harnesses--frameworks)
- [Terminal multiplexers](#terminal-multiplexers)
- [Task boards & Kanban](#task-boards--kanban)
- [Cost & observability](#cost--observability)
- [Related lists](#related-lists)
- [Contributing](#contributing)

## Command centers & ADEs

| Tool | Stars | Contributors | Updated | What |
| --- | --- | --- | --- | --- |
| **[Agor](https://github.com/preset-io/agor)** | ![Stars](https://img.shields.io/github/stars/preset-io/agor?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/preset-io/agor?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/preset-io/agor?style=flat-square&label=&color=informational) | Multiplayer canvas with git worktrees |
| **[Citadel](https://github.com/SethGammon/Citadel)** | ![Stars](https://img.shields.io/github/stars/SethGammon/Citadel?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/SethGammon/Citadel?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/SethGammon/Citadel?style=flat-square&label=&color=informational) | Operating layer with memory and cost telemetry |
| **[clawport-ui](https://github.com/JohnRiceML/clawport-ui)** | ![Stars](https://img.shields.io/github/stars/JohnRiceML/clawport-ui?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/JohnRiceML/clawport-ui?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/JohnRiceML/clawport-ui?style=flat-square&label=&color=informational) | Command center for Claude Code agent teams |
| **[Helmor](https://github.com/dohooo/helmor)** | ![Stars](https://img.shields.io/github/stars/dohooo/helmor?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/dohooo/helmor?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/dohooo/helmor?style=flat-square&label=&color=informational) | Local multi-agent dev workbench |
| **[Maestro](https://github.com/RunMaestro/Maestro)** | ![Stars](https://img.shields.io/github/stars/RunMaestro/Maestro?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/RunMaestro/Maestro?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/RunMaestro/Maestro?style=flat-square&label=&color=informational) | Agent orchestration command center |
| **[Mission Control](https://github.com/builderz-labs/mission-control)** | ![Stars](https://img.shields.io/github/stars/builderz-labs/mission-control?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/builderz-labs/mission-control?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/builderz-labs/mission-control?style=flat-square&label=&color=informational) | Self-hosted orchestration with spend monitoring |
| **[Orca](https://github.com/stablyai/orca)** | ![Stars](https://img.shields.io/github/stars/stablyai/orca?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/stablyai/orca?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/stablyai/orca?style=flat-square&label=&color=informational) | Fleet ADE for any coding agent; desktop and mobile |
| **[Paseo](https://github.com/getpaseo/paseo)** | ![Stars](https://img.shields.io/github/stars/getpaseo/paseo?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/getpaseo/paseo?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/getpaseo/paseo?style=flat-square&label=&color=informational) | Orchestrate agents from desktop and mobile |
| **[PocketPaw](https://github.com/pocketpaw/pocketpaw)** | ![Stars](https://img.shields.io/github/stars/pocketpaw/pocketpaw?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/pocketpaw/pocketpaw?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/pocketpaw/pocketpaw?style=flat-square&label=&color=informational) | Self-hosted multi-agent command center |
| **[supacode](https://github.com/supabitapp/supacode)** | ![Stars](https://img.shields.io/github/stars/supabitapp/supacode?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/supabitapp/supacode?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/supabitapp/supacode?style=flat-square&label=&color=informational) | Worktree coding-agents command center (macOS) |
| **[Superset](https://github.com/superset-sh/superset)** | ![Stars](https://img.shields.io/github/stars/superset-sh/superset?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/superset-sh/superset?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/superset-sh/superset?style=flat-square&label=&color=informational) | Code editor that runs an army of agents locally |
| **[Talavine Code](https://github.com/scrossen/talavine-code)** | ![Stars](https://img.shields.io/github/stars/scrossen/talavine-code?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/scrossen/talavine-code?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/scrossen/talavine-code?style=flat-square&label=&color=informational) | Desktop workbench for parallel coding agents and cross-model design review |

## Agentic IDEs

| Tool | Stars | Contributors | Updated | What |
| --- | --- | --- | --- | --- |
| **[jat](https://github.com/joewinke/jat)** | ![Stars](https://img.shields.io/github/stars/joewinke/jat?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/joewinke/jat?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/joewinke/jat?style=flat-square&label=&color=informational) | Agentic IDE to supervise 20+ parallel agents |
| **[stagewise](https://github.com/stagewise-io/stagewise)** | ![Stars](https://img.shields.io/github/stars/stagewise-io/stagewise?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/stagewise-io/stagewise?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/stagewise-io/stagewise?style=flat-square&label=&color=informational) | Agentic IDE with app previews and git workflows |

## Harnesses & frameworks

| Tool | Stars | Contributors | Updated | What |
| --- | --- | --- | --- | --- |
| **[agent-orchestrator](https://github.com/AgentWrapper/agent-orchestrator)** | ![Stars](https://img.shields.io/github/stars/AgentWrapper/agent-orchestrator?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/AgentWrapper/agent-orchestrator?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/AgentWrapper/agent-orchestrator?style=flat-square&label=&color=informational) | Plans tasks; handles CI, merges, reviews |
| **[Babysitter](https://github.com/a5c-ai/babysitter)** | ![Stars](https://img.shields.io/github/stars/a5c-ai/babysitter?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/a5c-ai/babysitter?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/a5c-ai/babysitter?style=flat-square&label=&color=informational) | Deterministic self-orchestration |
| **[Bernstein](https://github.com/sipyourdrink-ltd/bernstein)** | ![Stars](https://img.shields.io/github/stars/sipyourdrink-ltd/bernstein?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/sipyourdrink-ltd/bernstein?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/sipyourdrink-ltd/bernstein?style=flat-square&label=&color=informational) | Audit-grade orchestration with signed logs |
| **[claude_codex_bridge](https://github.com/SeemSeam/claude_codex_bridge)** | ![Stars](https://img.shields.io/github/stars/SeemSeam/claude_codex_bridge?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/SeemSeam/claude_codex_bridge?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/SeemSeam/claude_codex_bridge?style=flat-square&label=&color=informational) | Mix Codex, Claude, Gemini, Cursor, OpenCode |
| **[CORAL](https://github.com/Human-Agent-Society/CORAL)** | ![Stars](https://img.shields.io/github/stars/Human-Agent-Society/CORAL?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/Human-Agent-Society/CORAL?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/Human-Agent-Society/CORAL?style=flat-square&label=&color=informational) | Lightweight multi-agent autonomous infra |
| **[Genie](https://github.com/automagik-dev/genie)** | ![Stars](https://img.shields.io/github/stars/automagik-dev/genie?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/automagik-dev/genie?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/automagik-dev/genie?style=flat-square&label=&color=informational) | Dispatches parallel agents in worktrees |
| **[GoClaw](https://github.com/nextlevelbuilder/goclaw)** | ![Stars](https://img.shields.io/github/stars/nextlevelbuilder/goclaw?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/nextlevelbuilder/goclaw?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/nextlevelbuilder/goclaw?style=flat-square&label=&color=informational) | OpenClaw in Go; multi-tenant isolation |
| **[loushang](https://github.com/zhnt/loushang)** | ![Stars](https://img.shields.io/github/stars/zhnt/loushang?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/zhnt/loushang?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/zhnt/loushang?style=flat-square&label=&color=informational) | Python harness with provider routing |
| **[oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)** | ![Stars](https://img.shields.io/github/stars/Yeachan-Heo/oh-my-claudecode?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/Yeachan-Heo/oh-my-claudecode?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/Yeachan-Heo/oh-my-claudecode?style=flat-square&label=&color=informational) | Teams-first multi-agent orchestration |
| **[Omnigent](https://github.com/omnigent-ai/omnigent)** | ![Stars](https://img.shields.io/github/stars/omnigent-ai/omnigent?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/omnigent-ai/omnigent?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/omnigent-ai/omnigent?style=flat-square&label=&color=informational) | Swap harnesses; policy and sandboxing |
| **[opencrew](https://github.com/AlexAnys/opencrew)** | ![Stars](https://img.shields.io/github/stars/AlexAnys/opencrew?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/AlexAnys/opencrew?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/AlexAnys/opencrew?style=flat-square&label=&color=informational) | Multi-agent OS on OpenClaw and Slack |
| **[ruflo](https://github.com/ruvnet/ruflo)** | ![Stars](https://img.shields.io/github/stars/ruvnet/ruflo?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/ruvnet/ruflo?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/ruvnet/ruflo?style=flat-square&label=&color=informational) | Claude meta-harness with multi-agent swarms |
| **[SWE-AF](https://github.com/Agent-Field/SWE-AF)** | ![Stars](https://img.shields.io/github/stars/Agent-Field/SWE-AF?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/Agent-Field/SWE-AF?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/Agent-Field/SWE-AF?style=flat-square&label=&color=informational) | Autonomous SWE fleet for production PRs |

## Terminal multiplexers

| Tool | Stars | Contributors | Updated | What |
| --- | --- | --- | --- | --- |
| **[amux](https://github.com/mixpeek/amux)** | ![Stars](https://img.shields.io/github/stars/mixpeek/amux?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/mixpeek/amux?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/mixpeek/amux?style=flat-square&label=&color=informational) | Run dozens of parallel agents via tmux |
| **[herdr](https://github.com/ogulcancelik/herdr)** | ![Stars](https://img.shields.io/github/stars/ogulcancelik/herdr?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/ogulcancelik/herdr?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/ogulcancelik/herdr?style=flat-square&label=&color=informational) | Agent multiplexer in your terminal |

## Task boards & Kanban

| Tool | Stars | Contributors | Updated | What |
| --- | --- | --- | --- | --- |
| **[agent-kanban](https://github.com/saltbo/agent-kanban)** | ![Stars](https://img.shields.io/github/stars/saltbo/agent-kanban?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/saltbo/agent-kanban?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/saltbo/agent-kanban?style=flat-square&label=&color=informational) | Agent-first task board / mission control |
| **[kandev](https://github.com/kdlbs/kandev)** | ![Stars](https://img.shields.io/github/stars/kdlbs/kandev?style=flat-square&logo=github&label=&color=2b3137) | ![Contributors](https://img.shields.io/github/contributors/kdlbs/kandev?style=flat-square&label=&color=555) | ![Updated](https://img.shields.io/github/last-commit/kdlbs/kandev?style=flat-square&label=&color=informational) | AI Kanban and development environment |

## Cost & observability

- [ByteCosts](https://bytecosts.com) - Source-linked pricing for thousands of AI models with cost calculators; size up what a fleet of parallel agents costs.

## Related lists

- [awesome-agent-orchestrators](https://github.com/andyrewlee/awesome-agent-orchestrators) - List of agent orchestrators.
- [awesome-multi-agent-orchestrators](https://github.com/Agent-Analytics/awesome-multi-agent-orchestrators) - Curated directory for multi-agent orchestration.
- [awesome-harness-engineering](https://github.com/ai-boost/awesome-harness-engineering) - Tools, patterns, and evals for agent harness engineering.
- [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) - Skills, hooks, commands, and orchestrators for Claude Code.

## Contributing

Contributions welcome. Read the [contribution guidelines](CONTRIBUTING.md). One tool per pull request, in the right section, alphabetically. Stat badges are generated from the repo slug, so just add the row; numbers fill in automatically.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the maintainers have waived all copyright and related rights to this work (CC0 1.0).
