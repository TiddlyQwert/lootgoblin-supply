# Loot Goblin Supply Co. — Ledger

> Reconstructed 2026-09-08 from repo commit history (original lost to sandbox
> wipe). Now versioned in-repo. Currency: USD.

## Cash flows

| Date | Item | Spend | Revenue | Notes |
|---|---|---|---|---|
| 2026-09-06 | Store setup + 16 products live (Printify Pop-Up) | $0.00 | — | POD: no inventory; production cost is deducted per-order by Printify |
| 2026-09-07 | Catalog art v2 + 3 SEO pages + indexing | $0.00 | — | $0 tools/ads; art generated in-session |
| 2026-09-07 | Orders confirmed to date | — | $0.00 | 0 orders at S3 check |
| 2026-09-08 | SEO wave 2 (2 pages, sitemap, internal links) | $0.00 | — | Session 4 |
| 2026-09-08 | Order check | — | n/a | **BLOCKED** — no Printify API token (lost w/ sandbox) |

**Totals: spend $0.00 · confirmed revenue $0.00 · net $0.00**

## Unit economics (from launch milestone)
- Tee: $23.99 list · est. profit ~$7–10 per unit
- Mug: $16.99 list · est. profit ~$7–10 per unit
- Printify deducts production + shipping at order time; no fixed costs.

## Open items / discrepancies
- **Domain** lootgoblin-supply.com: acquisition/renewal cost NOT recorded in
  recovered commits. Flag for human: confirm whether pre-owned or purchased;
  update this ledger if cost > $0.
- **Printify API token:** must be re-supplied by human (chat or upload file).
  NEVER commit it to this repo. Needed for: GET /v1/shops/28847163/orders.json
- **GSC verification token:** none found this session; pending human.

## Agent credit usage (self-assessment)
| Session | Usage | Notes |
|---|---|---|
| S1 (9/6) | lean | niche + hub setup |
| S2 (9/6) | lean | launch, 16 products |
| S3 (9/7) | normal | art v2 (image gen) + SEO wave 1 |
| S4 (9/8) | normal | state recovery + 2 pages; single batched push; no image gen |

Policy: stay at "normal" or below. Batch file changes into single commits.
No paid APIs. Image generation only when a design task justifies it.
