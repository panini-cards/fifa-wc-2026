# Panini FIFA World Cup 2026 — Adrenalyn XL Collection Tracker

A single-page tracker for the Panini FIFA World Cup 2026 Adrenalyn XL trading-card
collection (630 cards).

- Quick-add card numbers (`10, 15, 22-25`) to record what you own.
- Click a tile to toggle owned. Right-click / long-press to set an exact count for duplicates.
- Overall + per-team + per-set progress bars.
- Search by number, team, or player. Filter by Owned / Missing / Doubles.
- Export a missing list and a doubles list for trading. Export/import a JSON backup.
- Data stays in your browser (localStorage). No account, no server.

**Live:** https://zdenko-kovac.github.io/panini_world_cup_cards_collection/

## Local development

```bash
python3 -m http.server 8000
# open http://localhost:8000/
# tests: http://localhost:8000/tests.html
```

## Status

Currently in **pilot mode** — `checklist.json` contains a subset of the 630 cards
(Golden Ballers, Argentina, and Extras) so the app is fully usable while the rest
of the checklist is being transcribed from the Panini PDF.

## Files

- `index.html` — the whole app (markup, CSS, JS in one file).
- `checklist.json` — the card master list.
- `tests.html` — browser-run assertions for pure functions.
