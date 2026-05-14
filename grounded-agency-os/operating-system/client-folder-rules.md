# Client Folder Rules

Each client must have one folder.

Recommended format:

`clients/[year]-[brand-slug]/`

Example:

`clients/2026-kopi-senja/`

## Standard Client Folder

```txt
clients/[client]/
├── 00-client-profile.md
├── 01-intake.md
├── 02-session-log.md
├── 03-decisions.md
├── foundation-audit/
├── brand-system/
├── landing-page/
├── implementation/
├── approvals/
├── revisions/
├── messages/
├── meetings/
├── assets/
└── final-delivery/
```

## Rules

- Do not place client files in root.
- Do not mix clients in one file.
- Store assumptions in each output.
- Store client decisions in `03-decisions.md`.
- Store every approval in `/approvals`.
- Store revision requests in `/revisions`.
- Store final files in `/final-delivery` only after human review.
