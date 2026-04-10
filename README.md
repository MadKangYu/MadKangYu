# KangYu

I improve agent runtime behavior, CLI update flows, and CI reliability.

My work is centered on making real systems quieter, clearer, and easier to verify.

## Main work

- Reduced Telegram fallback activation log noise in [`hermes-agent`](https://github.com/MadKangYu/hermes-agent/tree/codex/telegram-fallback-log-level) and landed the upstream change in [PR #5615](https://github.com/NousResearch/hermes-agent/pull/5615)
- Improved CLI update behavior with [#7303](https://github.com/NousResearch/hermes-agent/pull/7303) and [#7299](https://github.com/NousResearch/hermes-agent/pull/7299)
- Tightened docs and runtime alignment with [#7284](https://github.com/NousResearch/hermes-agent/pull/7284) and [#7280](https://github.com/NousResearch/hermes-agent/pull/7280)
- Recovered failing CI by propagating baseline fixes across active PR branches and re-verifying them with targeted test runs

## Focus

- AI agent runtime and CLI workflow design
- Operator tooling for Hermes and OpenClaw based setups
- GitHub and GitLab contribution loops
- Knowledge systems built around Obsidian

## Selected public repos

- [`tiered-scraper`](https://github.com/MadKangYu/tiered-scraper) - multi-stage web scraping with AI-assisted CAPTCHA solving
- [`ai-agent-landscape`](https://github.com/MadKangYu/ai-agent-landscape) - curated reference of major AI agent platforms and tools
- [`prompt-caching-slides`](https://github.com/MadKangYu/prompt-caching-slides) - presentation on prompt caching and Claude Code
- [`MadKangYu-FigMa-Mcp`](https://github.com/MadKangYu/MadKangYu-FigMa-Mcp) - Figma MCP guide and workflow reference

## Working style

- verification-first
- CLI-first
- docs/runtime parity over surface-level polish
- fix root causes instead of repeated symptoms

## Stack

`Python` `TypeScript` `GitHub Actions` `GitHub CLI` `GitLab CLI` `Hermes` `OpenClaw` `Obsidian`
