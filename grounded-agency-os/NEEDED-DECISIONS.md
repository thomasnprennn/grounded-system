# Needed Decisions

The system is usable now as v1. These decisions would make it more complete.

## 01 — Client Data Storage

Choose the source of truth for client data:

- Option A: File-based only in `/clients`
- Option B: Notion database + synced notes
- Option C: Custom dashboard + database
- Option D: Hybrid: files for AI work, dashboard for project status

Recommended v1: file-based first, dashboard later.

## 02 — Client Naming Convention

Recommended:

`clients/[brand-slug]/`

Example:

`clients/kopi-senja/`

Need decision:
- use lowercase slug only?
- include year/month?
- include package code?

Suggested final format:

`clients/2026-kopi-senja/`

## 03 — Deliverable Format

Need decision per package:

- Foundation Audit: Markdown, PDF, or HTML report?
- Brand System Build: PDF + Figma/Canva links?
- Full Implementation: folder handoff + dashboard + PDF summary?

Recommended:
- internal drafts in markdown
- client delivery in PDF or clean HTML

## 04 — Tool Stack

Current assumed stack:

- Codex in VS Code for file execution
- ChatGPT/Claude for strategy refinement
- Google Forms for intake
- Google Drive for asset delivery
- Vercel/GitHub for web builds

Need decision:
- Notion or custom dashboard?
- Google Drive or local repo for client assets?
- Figma or Canva as default brand guide/template tool?

## 05 — Default Client Market

The system assumes indie brands, especially coffee shops, fashion, local products, and creative services.

Need decision:
- start only with coffee shops?
- allow fashion/local products now?
- keep all indie brands but prioritize coffee shops?

## 06 — Legal/Contract Layer

Still missing:

- contract template
- invoice wording
- cancellation agreement
- client approval signature format
- asset licensing rules

## 07 — Metrics Layer

Need decision:

What counts as proof after project?

Possible metrics:
- before/after visual coherence
- clarity score improvement
- client testimonial
- website conversion behavior
- inquiries after launch
- content consistency after 30 days
