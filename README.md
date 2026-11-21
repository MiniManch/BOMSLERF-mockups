# BOMSLERF — Mockups

Every screen, flow and interface Sprint 3 / Sprint 4 needs built, as a picture you can paste
and a page you can open. One folder per Jira issue.

**→ [INDEX.md](INDEX.md) — the full issue-by-issue table**

## The three places and how they fit together

| | What it owns | Who |
|---|---|---|
| **[BomSlerf-GDD](https://github.com/Bomslerf/BomSlerf-GDD)** | the **rules** — mechanics, numbers, characters, 3D package | Steve |
| **This repo** | the **pictures** — what each screen looks like | Mano |
| **[Jira](https://stiv90000.atlassian.net/browse/BOM-1)** | the **work** — who builds what, when | the team |

🔴 **The GDD is the source of truth.** Where a mockup here disagrees with it, the GDD wins and
the mockup gets redrawn. Where a Jira issue disagrees with it, the issue gets corrected.
Nothing in this repo overrides a rule.

## How to use it

**Pasting into a Jira issue** — grab the raw image URL:

```
https://raw.githubusercontent.com/MiniManch/BOMSLERF-mockups/main/issues/BOM-51/BOM-51.png
```

**Sending to Amir** — link the issue folder, e.g. [`issues/BOM-51/`](issues/BOM-51/). It shows
the picture, the Jira link and the exact GDD section the rules come from, on one page.

**Looking at it properly** — open the `.html` next to each `.png`. Same content, real text you
can select, with links in the header bar.

## Layout

```
issues/BOM-51/
  ├── BOM-51.png     the mockup as an image — for pasting
  ├── BOM-51.html    the same thing, interactive
  └── README.md      links to Jira, to the GDD section, and back here
sheets/              the original multi-issue sheets, still browsable
```

## The browsable sheets

| Sheet | What it holds |
|---|---|
| [`all-mockups.html`](sheets/all-mockups.html) | every Sprint 4 issue — click one, see only its mockups |
| [`missing-mockups.html`](sheets/missing-mockups.html) | the 10 drawn on 7 Nov for issues that had none |
| [`full-flow.html`](sheets/full-flow.html) | auth → home → queue → loading → in-game → endings |
| [`blocks-bc.html`](sheets/blocks-bc.html) | combat feedback and character blocks (B0–B9, C1–C7) |
| [`game-endings.html`](sheets/game-endings.html) | the four end-of-match screens |
| [`character-select-panel.html`](sheets/character-select-panel.html) | BOM-41 / BOM-121 select panel |
| [`auth.html`](sheets/auth.html) | registration and login |
| [`sprint4-runway.html`](sheets/sprint4-runway.html) | the Sprint 4 schedule and asset manifest |
| [`gdd-reconciliation.html`](sheets/gdd-reconciliation.html) | what the GDD contradicted in Jira, 16 Nov |

## Known gaps

These issues still have **no** mockup and should get one:

- **BOM-97** — the Final Stage arena (spotlight, 4 pillars, 4 scenery walls, 2 bushes, 4 boxes).
  Added to the GDD on 21 Nov in [`02 §7.3.1`](https://github.com/Bomslerf/BomSlerf-GDD/blob/main/docs/02_Core_Mechanics.md).
- **Base healing and the base laser** — [`02 §9.2`](https://github.com/Bomslerf/BomSlerf-GDD/blob/main/docs/02_Core_Mechanics.md),
  added 21 Nov. No Jira issue yet.
- **Sprint out of combat** — [`02 §14.1`](https://github.com/Bomslerf/BomSlerf-GDD/blob/main/docs/02_Core_Mechanics.md),
  added 21 Nov. No Jira issue yet.

## Things in here that are now out of date

The GDD moved on 21 Nov and some mockups predate it:

| Mockup | What changed |
|---|---|
| BOM-51 deathcam | respawn is tiered 10→27 s; the 3-2-1 countdown shows only in the last 3 s |
| BOM-80 flag floor | colours are per-player — orange blocked, green/red split by side |
| BOM-56 flag capture | there are **three** win conditions, not one capture |
| BOM-70 grass exit | the 1.5 s is the reveal-on-attack rule, not a bug |
| BOM-71 device FOV | under a 7 m dark map a wider screen shows terrain, not enemies |
| all sheets | the UI palette bans purple — `#0C447C` / `#378ADD` / `#FFD700` |

---

*Generated 2026-11-21.*
