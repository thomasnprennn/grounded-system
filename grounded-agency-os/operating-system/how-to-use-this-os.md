# How to Use This OS

This OS is designed to make AI work like an internal operator, not a random chat assistant.

## Basic Flow

1. Create or choose a client folder.
2. Choose the workflow.
3. Ask Codex/AI to read the relevant workflow files.
4. Run one step at a time.
5. Save outputs inside the client folder.
6. Review before sending anything to client.

## How to Start a Session

Use this format:

```txt
Read AGENTS.md and the relevant workflow files first.
Client: [name]
Workflow: [Foundation Audit / Brand System Build / Landing Page]
Goal today: [specific output]
Do not edit unrelated files.
Save output to /clients/[client-slug]/[folder]/.
Mark assumptions clearly.
```

## What Not to Do

Do not ask AI:

"Bikin audit brand ini."

Too broad.

Ask:

"Run A3 visual audit using screenshots provided in /clients/kopi-senja/assets/screenshots. Save findings to /clients/kopi-senja/foundation-audit/03-visual-audit.md. Do not write recommendations yet."

## Recommended Workflow Discipline

- One session = one workflow step.
- One client = one folder.
- One output = one file.
- One final delivery = human reviewed.
