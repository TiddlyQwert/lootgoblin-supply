# Loot Goblin Supply Co. — Operations Journal (CANONICAL)

> **This repo file is the canonical ops journal.** Cron-woken sessions may not see
> `/mnt/agents/upload/` (learned 2026-09-08: cron sandbox showed it empty while
> interactive sessions see it fine). Rules for every session:
> 1. Read THIS file + `LEDGER.md` + `BUSINESS_PLAN.md` from the repo first.
> 2. Secrets (Printify token, Discord webhook URL) live ONLY in
>    `/mnt/agents/upload/SECRETS.md` — NEVER commit them here.
> 3. If SECRETS.md is unavailable (cron session), skip token-requiring work
>    (order checks) and note it — do not ask the human to re-drop unless an
>    interactive session also fails.
> 4. Notifications to the human ride in COMMIT MESSAGES ([STATUS]/[MILESTONE]/
>    [URGENT]/[HUMAN NEEDED]) — the repo's GitHub→Discord webhook delivers them.
> 5. Append session entries here (newest at bottom) and push with your work.

---

## Session 1 — 2026-09-06 (niche → brand hub)
- Niche chosen: tabletop-RPG / dice-goblin POD merch (evidence: 387 Etsy listings vs
  3,600 searches/mo "loot goblin", KD 16/100; beat pickleball, nursing, fishing, crochet).
  Full comparison: `/mnt/agents/upload/research/niche-selection.md` (interactive sessions).
- Trademark red lines: no WotC marks on products/designs/tags ("Dungeons & Dragons",
  "D&D", "Dungeon Master", WotC creature names). Editorial references inside articles
  are allowed (nominative fair use) — affirmed S5b.
- Repo + GitHub Pages landing page created; human connected custom domain
  lootgoblin-supply.com (owner-purchased, est. ~$10–12/yr).

## Session 2 — 2026-09-06 (LAUNCH DAY)
- Human created Printify account + Pop-Up Store + provided API token (interactive
  SECRETS.md only). Payout method: Printify Balance (revisit withdrawals >$20k).
- **[MILESTONE] STORE LIVE**: https://loot-goblin-supply-co.printify.me — 16 products
  (8 tees $23.99 / 8 mugs $16.99, est. profit ~$7–10/unit, $0 spent).
- Designs (8): Dice Goblin; Professional Loot Goblin; Nat 20 Energy; Crit Happens;
  Roll for Initiative; My Other Hoard Is Dice; Game Master — I Make It Up As I Go;
  Powered by Dice & Questionable Decisions.
- Discord direct webhook: network-blocked from sandbox (permanent). Fix: repo webhook
  with /github suffix → Discord; commit messages carry notifications.

## Session 3 — 2026-09-07 (art v2 + SEO wave 1)
- Human feedback: v1 text-only designs not appealing → catalog art v2:
  4 AI woodcut illustrations (goblin / dragon hoard / GM screen / crit d20) +
  4 code-drawn vintage badge emblems. All 16 products updated + republished.
- Printify API learnings: published products expand to full variant list — every
  variant must appear in print_areas (catch-all area for disabled ones);
  publish.json requires all fields true.
- SEO wave 1: dice-goblin-meaning, gifts-for-dice-goblins, game-master-gift-ideas
  + sitemap.xml + robots.txt. IndexNow key deployed + submitted.
- Human verified domain in Google Search Console (DNS). Orders: 0.

## Session 4a — 2026-09-08 09:10 UTC (cron-woken)
- Cron fired successfully. BUT cron sandbox did not show /mnt/agents/upload files
  → treated as state loss; rebuilt JOURNAL/LEDGER in repo (correct instinct —
  repo is now canonical). Order check blocked (no token in cron session).
- +2 SEO pages: nat-20-meaning, loot-goblin-meaning (with FAQ schema).

## Session 4b — 2026-09-08 15:04 UTC (interactive, human ping)
- Order check: 0. Rewrote the 2 pages (overwrite, same URLs — dedupe lesson:
  check repo before writing). IndexNow resubmitted. Human informed crons work.

## Session 5 — 2026-09-09 09:12 UTC (cron-woken)
- +2 SEO pages: tabletop-rpg-gift-guide, dice-tray-gift-guide. Homepage gained
  "Guides from the hoard" section → 8 indexable URLs. Google indexation of the
  homepage CONFIRMED (site: query shows indexed content).

## Session 5b — 2026-09-09 13:39 UTC (interactive)
- Root-caused dual-brain split; repo declared canonical ops brain; this file +
  LEDGER + BUSINESS_PLAN consolidated here. Order check: 0 (day 3, pre-traffic).
- Editorial decision: "D&D" stays in one gift-guide title (nominative editorial
  use; products/designs/tags remain 100% generic). Don't "fix" or escalate it.

## Standing queue for future sessions
- Daily: order check (if token available), 1–2 SEO pages (next ideas: "dice bag
  gift guide", "tabletop rpg stocking stuffers", "best mugs for game night"),
  sitemap + IndexNow, [STATUS] commit, journal+ledger append, schedule next wake-up.
- Weekly: fuller [STATUS] (traffic if GSC data shared, orders, revenue, credit).
- Pivot clock: started 2026-09-07 (launch). Zero sales after 3 weeks of genuine
  traffic effort (~2026-09-28) → post-mortem + pivot (runner-ups in niche-selection).
- Phase 2 products (hats $27.99, tote bags) once traffic justifies.
