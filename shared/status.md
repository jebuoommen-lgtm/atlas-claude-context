# Status — 2026-05-12

## Atlas (Hermes Agent)
- Working on: Smart Align API integration, daily briefing automation
- - ✅ Smart Align API connected — 72 patients, 253 payments, 88 invoices live
  - - ✅ Firecrawl API set as primary web access (search + extraction)
    - - ✅ Playwright MCP removed — CAPTCHA blocked, Firecrawl superior
      - - ✅ Browserbase configured as passive fallback (no key needed)
        - - ✅ Daily briefing cron + cost report + task management active (6 cron jobs)
          - - ✅ Quick code quality check set up: `c` alias (Ruff + Mypy)
            - - Next: Paginate full payment history, set up Smart Align data pull skill
              - - Blockers: None
               
                - ## Claude Cowork
                - - Working on: Mizpah Smart Align Meta Ads — WhatsApp CTWA switchover
                  - - ✅ Confirmed WABA (975590361562290) Connected, Verified, High Quality
                    - - ✅ Facebook Page linked to +91 73384 55808 as Primary WhatsApp number
                      - - ✅ Created 4 new WhatsApp-destination ad sets (one per campaign)
                        - - ✅ Investigated BestoSys WABA integration — no conflict risk with CTWA ad leads
                          - - ✅ BestoSys confirmed: same Meta API ok, but different number required for lead gen bot
                            - - ✅ Corrected campaign IDs in MIZPAH_BRAND.md (Kerala Local + NRI Gulf were wrong)
                              - - Next: User to register new WhatsApp number for Mizpah Smart Align lead bot; then register on WABA + update 4 ad sets to new number
                                - - Next: Upload video creatives (Video 4 priority) and activate campaigns
                                  - - Blockers: New WhatsApp number not yet obtained; no creatives uploaded yet
                                   
                                    - ## Notes
                                    - - **Dual status architecture**: Hermes config (SOUL.md + CONTEXT.md + memory) = machine-readable agent context. GitHub repo files = human-readable shared status between Atlas and Claude Cowork.
                                      - - Repo: jebuoommen-lgtm/atlas-claude-context
                                        - - PAT generated for Atlas (no expiration, repo scope) — `/api/atlas/` endpoints live
                                          - - End-of-session auto-export protocol established via browser tool
                                            - - BestoSys auto-responses only fire on button presses from known patients — safe to run CTWA ads on same number short-term, but two-number strategy adopted for clean separation
