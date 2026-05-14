# A7 — Root Cause Synthesis

## Purpose

Translate audit findings into system-level root problems.

## Inputs Needed

- visual audit
- narrative audit
- customer perception audit
- system coherence audit

## Files to Read

- AGENTS.md
- operating-system/quality-gates.md
- all previous Foundation Audit outputs

## Output to Create

- 3 prioritized root causes
- symptom → root cause → system issue → impact → system fix map

## Save To

`/clients/[client]/foundation-audit/07-root-cause-synthesis.md`

## Human Review

Human locks the root causes before report is generated.

## Quality Gate

- max 3 root causes
- each root cause has evidence
- fix is system-level
- no surface-only diagnosis

## AI Instruction

```txt
Synthesize the audit into 3 root causes. For each: list the symptoms, explain the root cause, identify the missing system, explain the business/customer impact, and propose a system fix. Do not write the final report yet.
```
