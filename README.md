# KangYu · MadKangYu

**Turning noise into verified action.**

I make AI-agent operations observable, recoverable, and gated.

Current focus: agent runtime behavior, operator tooling, CLI update flows, CI reliability, and human-in-the-loop automation.

## Proof of work

- Made agent runtime failures easier to diagnose by reducing fallback log noise in [`NousResearch/hermes-agent`](https://github.com/NousResearch/hermes-agent/pull/5615).
- Improved CLI update flows so operators can move between versions with fewer surprises: [#7303](https://github.com/NousResearch/hermes-agent/pull/7303), [#7299](https://github.com/NousResearch/hermes-agent/pull/7299).
- Tightened documentation and runtime behavior so instructions match what the system actually does: [#7284](https://github.com/NousResearch/hermes-agent/pull/7284), [#7280](https://github.com/NousResearch/hermes-agent/pull/7280).
- Recovered failing CI by carrying baseline fixes across active PR branches and re-verifying them with targeted test runs.

## What I Make Reliable

- AI agent runtime behavior
- CLI and operator tooling
- CI reliability and release hygiene
- Human approval gates for automation
- Knowledge systems built around Obsidian

## Operating model

I treat useful automation as a gated decision system:

```text
field values -> gate checks -> next action
```

- **Fields** capture the minimum structured evidence needed to judge a situation: source, observed value, confidence, freshness, authority, action boundary, privacy boundary, verification method, and blocker.
- **Gates** decide whether the next step is allowed: source, permission, parsing, privacy, local proof, runtime availability, external action, and verification.
- **Actions** are only promoted when the gate state supports them. Listed is not usable. Connected is not writable. Installed is not post-ready.

## Selected Public Work

| Project | Why it matters |
| --- | --- |
| [`hermes-agent`](https://github.com/MadKangYu/hermes-agent) | Fork focused on runtime signal quality, CLI update behavior, and CI reliability. |
| [`figx`](https://github.com/MadKangYu/figx) | Pragmatic Figma CLI for macOS agent workflows and design handoff. |
| [`ai-agent-landscape`](https://github.com/MadKangYu/ai-agent-landscape) | Reference map for comparing AI agent platforms, tools, and infrastructure. |
| [`prompt-caching-slides`](https://github.com/MadKangYu/prompt-caching-slides) | Terminal-style explainer for Claude Code prompt caching lessons. |
| [`MadKangYu-FigMa-Mcp`](https://github.com/MadKangYu/MadKangYu-FigMa-Mcp) | Guide to Figma MCP workflows for Claude Code and design-to-code automation. |

## Visual identity

<p align="left">
  <img src="./assets/avatar-ky-signal-mark.png" alt="KY signal mark" width="96">
  <img src="./assets/verified-decision-engine.png" alt="Noise becomes evidence, evidence becomes action" width="96">
</p>

`Python` `TypeScript` `GitHub Actions` `GitHub CLI` `GitLab CLI` `Hermes` `OpenClaw` `Obsidian`

## Contact

- GitHub: [@MadKangYu](https://github.com/MadKangYu)
- Email available on request.

<!-- Avatar candidate: ./assets/avatar-ky-signal-mark.png -->
