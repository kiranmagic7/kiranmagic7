# Hi, I'm Kiran

I build developer tools, agent workflows, and research infrastructure where small failures create real drag: CLIs that hang, usage meters that drift, config paths that break, docs that lie, and editor state bugs that feel random until someone proves the root cause.

My work is simple to judge: reproduce the issue, respect the product, keep the diff sharp, and leave maintainers with tests they can trust.

**29 public upstream pull requests merged since February 2026.**

Small fixes when the fix should be small. High standards every time.

![Swift](https://img.shields.io/badge/-Swift-FA7343?style=flat-square&logo=swift&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![CLI](https://img.shields.io/badge/-CLI-000000?style=flat-square&logo=gnu-bash&logoColor=white) ![macOS](https://img.shields.io/badge/-macOS-000000?style=flat-square&logo=apple&logoColor=white) ![Testing](https://img.shields.io/badge/-Testing-2E7D32?style=flat-square&logo=githubactions&logoColor=white) ![Docs](https://img.shields.io/badge/-Docs-555555?style=flat-square&logo=readthedocs&logoColor=white)

## Start Here

- **[CodexBar](https://github.com/steipete/CodexBar)** - 16 merged PRs across usage metering, provider history, config paths, docs integrity, and CLI edge cases.
- **[OpenClaw](https://github.com/openclaw/openclaw), [Crabbox](https://github.com/openclaw/crabbox), [gogcli](https://github.com/openclaw/gogcli)** - runtime boundaries, sandbox/session behavior, and docs validation.
- **[Plate](https://github.com/udecode/plate)** - editor UX fixes where table and MDX behavior needed precise state handling.
- **[Rueidis](https://github.com/redis/rueidis) and [Rushstack](https://github.com/microsoft/rushstack)** - package and systems tooling fixes with small, reviewable changes.
- **[Vercel AI](https://github.com/vercel/ai), [Langflow](https://github.com/langflow-ai/langflow), [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk)** - active upstream work in AI workflow and protocol tooling.

## Current Focus

### Agentic Engineering Tools

- Usage and billing accuracy across real CLI behavior
- Provider parsing, fallback paths, cache behavior, and subprocess boundaries
- Config diagnostics that tell the truth without surprising users

### Maintainer-Grade Open Source

- Narrow PRs with clear behavioral proof
- Tests that protect the actual regression
- Docs updates that make the product easier to operate

### Editor and Product Reliability

- State bugs that present as UX bugs
- Markdown, MDX, and table behavior where data shape matters
- Small interface fixes that reduce repeated friction

### Research Infrastructure

- Knowledge systems with source traceability
- Verification-first workflows
- Structured repositories that make review possible

## Selected Upstream Work

| Area | Repositories | Examples |
| --- | --- | --- |
| Developer tools and usage systems | CodexBar, tokentally | [Claude CLI rate-limit handling](https://github.com/steipete/CodexBar/pull/1685), [provider utilization history](https://github.com/steipete/CodexBar/pull/1588), [nested usage normalization](https://github.com/steipete/tokentally/pull/16) |
| Runtime and agent tooling | OpenClaw, Crabbox, gogcli | [Modal run-session handles](https://github.com/openclaw/crabbox/pull/452), [E2B run-session handles](https://github.com/openclaw/crabbox/pull/451), [docs anchor validation](https://github.com/openclaw/gogcli/pull/812) |
| Editor and product UX | Plate, CodexBar | [MDX table preservation](https://github.com/udecode/plate/pull/5007), [column drop target ref](https://github.com/udecode/plate/pull/5003), [Windsurf Devin session lookup](https://github.com/steipete/CodexBar/pull/1579) |
| Systems and package tooling | Rueidis, Rushstack | [Redis array command builders](https://github.com/redis/rueidis/pull/1002), [Rush pnpm recursive query defaults](https://github.com/microsoft/rushstack/pull/5822) |
| AI and workflow tools | Vercel AI, Langflow, MCP TypeScript SDK | [chat response preservation](https://github.com/vercel/ai/pull/16145), [component code search guard](https://github.com/langflow-ai/langflow/pull/13620), [debounce relatedRequestId fix](https://github.com/modelcontextprotocol/typescript-sdk/pull/2135) |

## How I Work

1. Reproduce before diagnosing.
2. Understand the product surface, not only the failing line.
3. Keep the diff small enough to review seriously.
4. Add tests where the bug could come back.
5. Write PR notes that make the maintainer's job easier.
6. Leave the codebase calmer than I found it.

## GitHub Activity

![GitHub Contribution Graph](https://gitlyy.vercel.app/api/contribution?username=kiranmagic7&hide_border=true)

## What I'm Doing

- Tightening usage and cost visibility for AI developer tools
- Hardening CLI, config, and runtime boundaries
- Contributing focused fixes to high-signal upstream projects
- Building research systems where claims can be traced instead of guessed

## Philosophy

> Small diffs. Real tests. Clean PRs.

I do not chase large diffs. I chase leverage.
