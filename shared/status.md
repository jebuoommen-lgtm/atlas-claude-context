# Status — 2026-05-11

## Atlas (Hermes Agent)
- Working on: Smart Align API integration, daily briefing automation
- ✅ Smart Align API connected — 72 patients, 253 payments, 88 invoices live
- ✅ Firecrawl API set as primary web access (search + extraction)
- ✅ Playwright MCP removed — CAPTCHA blocked, Firecrawl superior
- ✅ Browserbase configured as passive fallback (no key needed)
- ✅ Daily briefing cron + cost report + task management active (6 cron jobs)
- ✅ Quick code quality check set up: `qc` alias (Ruff + Mypy)
- Next: Paginate full payment history, set up Smart Align data pull skill
- Blockers: None

## Claude Cowork
- Working on: GitHub shared context repo setup + end-of-session export protocol
- Next: Read Atlas updates from repo; action any pending items
- Blockers: No GitHub MCP in registry — using browser tool for repo access

## Notes
- **Dual status architecture**: Hermes config (SOUL.md + CONTEXT.md + memory) = machine-readable agent context. GitHub repo files = human-readable shared status between Atlas and Claude Cowork.
- Repo: jebuoommen-lgtm/atlas-claude-context
- PAT generated for Atlas (no expiration, repo scope) — `/api/atlas/` endpoints live
- End-of-session auto-export protocol established via browser tool
