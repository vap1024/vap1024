# Hi, I'm Artur 👋

**Developer from Kyiv, Ukraine.** I run my projects as a small multi-agent
operation: coding agents build, an independent agent audits, and nothing is accepted
until it's verified against the files on disk.

## How I work: Builder vs Auditor

Most AI coding failures I hit were not bad code — they were confident summaries of work
that never happened. My fix is separation of duties:

1. **Builder** agent implements from a written brief.
2. **Auditor** agent (Codex) re-checks numbers, code and claims from primary sources.
3. **Acceptance** happens only after the result is verified on disk: tests re-run,
   counts recalculated, claims traced to sources.

The workflow, templates and checklists are open:
[**codex-audit-workflow**](https://github.com/vap1024/codex-audit-workflow)

## Featured projects

| Project | What it does |
| --- | --- |
| [codex-audit-workflow](https://github.com/vap1024/codex-audit-workflow) | Builder vs Auditor toolkit: audit-brief generator, claim checker, acceptance checklist |
| [contact-base-builder](https://github.com/vap1024/contact-base-builder) | Turns raw creator exports into a clean, deduplicated contact base with a conflict report |
| [agent-goal-control](https://github.com/vap1024/agent-goal-control) | File-based goal tracking for agent-assisted work: statuses, stale-goal detection, digests |

All three were built with Codex in October 2026 and ship with tests and synthetic demo data only.

## Stack

Python · AI coding agents (Codex, Claude Code) · Telegram bots · data pipelines ·
Linux/systemd · paper-trading experiment frameworks with frozen rules

## Now

- Documenting the Builder vs Auditor workflow in Russian and Ukrainian for builders in Eastern Europe
- Running long-horizon paper experiments where the rules are frozen before the start — and the FAIL verdicts get published too
