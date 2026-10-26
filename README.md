# Hi, I'm Artur 👋

**Developer from Kyiv, Ukraine.** I build software as a small multi-agent
operation: coding agents implement, an independent agent audits, and nothing is
accepted until it's verified against the files on disk. Most of my work sits where
AI agents meet real data — trading research, market audits and automation that
has to be right, not just plausible.

## What I do

- **Multi-agent development systems** — Builder/Auditor workflows where building
  and verification are separate roles: written briefs, acceptance checklists and
  results confirmed on disk, not taken from an agent's summary.
- **Market audit toolkits** — pre-mint NFT scoring and L2 shutdown-risk analysis
  that read public sources like a risk desk and publish their verdicts,
  including the FAILs.
- **Paper-trading research** — long-horizon experiments with the rules frozen
  before the start: forward tests, backtests and honest post-mortems instead of
  cherry-picked wins.
- **Data pipelines and bots** — Python services on Linux/systemd, Telegram
  tooling, parsers and monitoring built to run unattended for months.

## How I work: Builder vs Auditor

Most AI coding failures I hit were not bad code — they were confident summaries of work
that never happened. My fix is separation of duties:

1. **Builder** agent implements from a written brief.
2. **Auditor** agent (Codex) re-checks numbers, code and claims from primary sources.
3. **Acceptance** happens only after the result is verified on disk: tests re-run,
   counts recalculated, claims traced to sources.

The workflow, templates and checklists are open:
[**codex-ops-system**](https://github.com/vap1024/codex-ops-system)

## Featured projects

| Project | What it does |
| --- | --- |
| [codex-ops-system](https://github.com/vap1024/codex-ops-system) | One agent builds, Codex audits, nothing ships unverified — an operating system for multi-agent development: frozen briefs, source-checked audits, acceptance verified on disk |
| [l2-project-audit](https://github.com/vap1024/l2-project-audit) | Will this L2 die before the market notices? An audit toolkit that reads public announcements like a risk desk: delisting and shutdown classification, token-fate analysis, a 0–10 health score |
| [nft-collection-audit](https://github.com/vap1024/nft-collection-audit) | Mint or skip — decided by a score, not by hype. A pre-mint audit with a hard 7.0 gate, wash-trading heuristics and contract risk checks, plus a 30-day tracker that grades every call, wins and FAILs alike |

All three were built with Codex in October 2026 and ship with tests, CI and synthetic demo data only.

## Stack

Python · AI coding agents (Codex, Claude Code) · Telegram bots · data pipelines ·
Linux/systemd · paper-trading experiment frameworks with frozen rules

## Now

- Documenting the Builder vs Auditor workflow in Russian and Ukrainian for builders in Eastern Europe
- Running long-horizon paper experiments where the rules are frozen before the start — and the FAIL verdicts get published too
- Feedback, issues and ideas on the featured projects are welcome — that's the point of keeping all of this open
