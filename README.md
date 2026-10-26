# KISS Roulette Lab V2

Mobile-first American roulette history and original-table analysis. Static HTML/CSS/JS; runs on GitHub Pages.

## Original source table
All 38 rows are transcribed from the supplied screenshot, including alternative variants and slash-separated choices. A transition counts once if the next number belongs to the union of all variants for the previous number. Each variant is also scored independently. Expected matches are calculated from the number of unique covered pockets divided by 38, separately for each observed transition.

## Features
- Mobile keypad, multiple tables, undo, localStorage persistence
- JSON backup and restore
- Original source table: all variants, per-row and per-variant hit rates
- Chronological transition audit, theoretical expected hits
- Existing experimental models and frequency analysis

## Hosting
Upload `index.html` and `README.md` to repository root; enable GitHub Pages on main / root.

This is a historical analysis tool, not a winning strategy. The table has not been shown to predict independent roulette spins.
