# grounded-agency-os

Internal file-based operating system for `gr( )unded studio`.

This repo is designed to be used with Codex, Claude Code, ChatGPT, or any AI coding/workflow assistant that can read and write files.

The goal: keep client work structured, repeatable, and separated.

## How to Use

1. Open this folder in VS Code.
2. Install the official Codex extension or use Codex CLI.
3. Make sure `AGENTS.md` is in the root folder.
4. For every new client, create a folder inside `/clients`.
5. Run one workflow at a time.
6. Review all output before sending to a client.

## Core Principle

Do not start with design.

Start with diagnosis:

Observation → Problem → Root Cause → System Issue → System Fix → Output

## Main Workflows

- `A-foundation-audit` — 1-week audit and diagnosis report.
- `B-brand-system-build` — 4–6 week brand system package.
- `C-full-implementation` — 8–12 week implementation package.
- `D-landing-page` — landing page strategy, copy, wireframe, and build brief.
- `E-sales-and-ops` — inbound, outbound, qualification, and proposal flow.
- `F-content-system` — Instagram/content planning for gr( )unded studio and clients.

## Suggested First Test

Ask Codex:

```txt
Read this repository first. Do not edit anything yet.
Explain how this agency OS works, what workflows exist, what files are missing, and how we should test it with one dummy client.
```

Then run:

```txt
Run the Foundation Audit workflow for a dummy client named Kopi Senja.
Use the files in /workflows/A-foundation-audit.
Create all outputs inside /clients/kopi-senja/.
Mark assumptions clearly.
Do not create final client-facing report until internal audit drafts are complete.
```
