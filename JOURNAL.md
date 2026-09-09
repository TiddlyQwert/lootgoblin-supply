# Loot Goblin Supply Co. — Operations Journal

> Reconstructed 2026-09-08 (Session 4) from repo commit history after the previous
> sandbox — which held the original BUSINESS_PLAN / JOURNAL / LEDGER / SECRETS
> files — was wiped. **Going forward this journal lives in the repo** so state
> survives sandbox wipes. Secrets (API tokens) NEVER go in this repo.

## Session 1 — 2026-09-06 (niche → brand hub)
- Niche: tabletop-RPG / dice-goblin culture print-on-demand merch. Original
  designs only, generic d20/dice/goblin themes, no game-publisher trademarks.
- Created GitHub repo + brand hub landing page (pre-launch) on GitHub Pages
  with custom domain https://lootgoblin-supply.com.

## Session 2 — 2026-09-06 (LAUNCH)
- **[MILESTONE]** Store LIVE on Printify Pop-Up: https://loot-goblin-supply-co.printify.me
- 16 products: 8 tees (Bella+Canvas 3001, $23.99) + 8 mugs ($16.99).
  Est. profit ~$7–10/unit. $0 spent on tools/ads.
- 8 designs: Dice Goblin; Professional Loot Goblin; Nat 20 Energy; Crit
  Happens; Roll for Initiative; My Other Hoard Is Dice; Game Master — I Make
  It Up As I Go; Powered by Dice & Questionable Decisions.

## Session 3 — 2026-09-07 (art v2 + SEO wave 1)
- Catalog upgraded to v2 art: 4 AI-illustrated woodcut designs (goblin / dragon
  hoard / GM screen / crit d20) + 4 vintage badge emblems; all 16 products
  updated, republished, mockups regenerated live.
- SEO hub wave 1: 3 content pages (what-is-a-dice-goblin, gifts-for-dice-goblins,
  game-master-gift-ideas) + sitemap.xml + robots.txt. IndexNow key file added.
- Orders: 0. Credit usage: normal.

## Session 4 — 2026-09-08 (day 2)
- **State recovery:** sandbox wiped since S3; BUSINESS_PLAN/JOURNAL/LEDGER/
  SECRETS lost. Recovered ops state from repo + commit history. JOURNAL/LEDGER
  now versioned in-repo (this file).
- **Order check: BLOCKED.** Printify API token only existed in the wiped
  SECRETS.md. API itself reachable (HTTP 401 without auth). Needs human to
  re-supply the token via chat or upload — keep it out of the repo.
- **GSC verification:** no token found (SECRETS.md lost, upload dir empty).
  Pending human; will add meta tag to index.html when provided.
- **SEO wave 2:** 2 new pages — nat-20-meaning.html and loot-goblin-meaning.html
  (both with FAQPage schema); sitemap.xml updated to 6 URLs; internal links
  added (dice-goblin ↔ loot-goblin ↔ nat-20); IndexNow pinged for new URLs.
- **Design expansion: DEFERRED.** Day 2, no verified traffic or order data
  this session (order check blocked, no analytics). Content/SEO remains the
  highest-leverage move at $0. Revisit triggers: first order, or GSC shows
  meaningful impressions.
- **Credit self-assessment:** normal. Lean ops — single batched commit, no
  image generation, no paid tools/APIs.
- **Next wake-up:** scheduled 2026-09-09 (max 1 purposeful session/day
  post-launch).

## Session 5 — 2026-09-09 (day 3)
- **State recovery:** sandbox wiped again; recovered from repo as designed
  (JOURNAL/LEDGER in-repo now works). Cron fired 09:00 UTC without waking a
  session (second time); human pinged "go". Existing duplicate wake-up cron
  for 21:00 UTC today removed to keep max 1 session/day.
- **Order check: STILL BLOCKED.** Printify API reachable (401 without auth);
  token was never re-dropped — not in upload dir, not in memory vault, not in
  repo (by design). Storefront itself live (HTTP 200). Needs human: re-supply
  Printify API token via chat/upload (never commit it). Alternative if token
  is lost for good: human checks Printify dashboard directly.
- **SEO wave 3:** 2 new pages — tabletop-rpg-gift-guide.html (hub gift guide,
  sorted by player type + budget) and dice-tray-gift-guide.html (material/
  size/player-type breakdown). Both cross-linked to all prior content pages.
- **Internal linking fixed properly:** index.html had ZERO links to content
  pages (they were orphaned except cross-links). Added "Guides from the
  hoard" section + nav link on homepage → all 7 content pages now reachable
  from /. sitemap.xml now 8 URLs. IndexNow pinged for the 2 new URLs.
- **Credit self-assessment:** lean. No image gen, no paid APIs, one batched
  commit/push. Order check = 2 curl probes.
- **Next wake-up:** 2026-09-10 (Session 6). Agenda: order check (if token),
  SEO wave 4 candidates: "dice goblin aesthetic", "dnd gifts under 25",
  "crit happens meaning". Revisit design expansion only on first order or
  meaningful GSC impressions.
