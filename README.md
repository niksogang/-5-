# KISS Roulette Lab

Personal, mobile-first American roulette tracker. Static HTML/CSS/JS, no dependencies, no tracking, no account required.

## Features
- Responsive mobile keypad for `0`, `00`, `1–36`
- Local persistent history (localStorage), separate tables, undo, wipe
- JSON backup and restore to move data between devices
- Test predictions from table, historical frequency, deterministic control and a hybrid
- Walk-forward backtesting: each model scores only against spins occurring after the inputs used
- Recent-history and frequency visualizations

## Run locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a new **public** repository on GitHub (e.g., `kiss-roulette-lab`).
2. Upload `index.html` and `README.md` to the repository root; commit to `main`.
3. In **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. The site URL will normally be `https://YOUR_USERNAME.github.io/kiss-roulette-lab/` once GitHub publishes it.
5. On iPhone, open the URL in Safari and use **Share → Add to Home Screen** for app-like launch.

**Privacy:** GitHub Pages publicly hosts site source files; input histories stay locally in the visitor's browser, unless exported by the user. Data does **not** synchronize automatically between devices or after Safari data deletion. To synchronize automatically, a backend database and sign-in would be needed.

**Statistical limits:** Independent American roulette spins each give any three distinct numbers a 3/38 = 7.89% chance. These models are exploratory and do not demonstrate a betting advantage. Do not use the tracker as a promise of future wins.

## Seed state
The first opening includes the latest stated table: `28, 16, 7, 7, 36, 5, 3, 14`. Remove, correct or create a new table as needed.
