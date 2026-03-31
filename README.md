# Endless-March-Calculators
A calculator that will manually track your character count and output your XP gain, gold, and DM rewards.

## 🔥 Live Preview (GitHub Pages)
This project can be hosted using **GitHub Pages**. Once Pages is enabled for the `main` branch, the app will be available at:

https://grubbmasterflex-glitch.github.io/Endless-March-Calculators/

### How to enable GitHub Pages
1. Go to **Settings → Pages** in this repository.
2. Under **Source**, select **Branch: `main`** and **Folder: `/ (root)`**.
3. Click **Save**.

The site should become live within a minute.

## 🚀 Local Preview
To preview locally:

```bash
python -m http.server 8000
```

Then open:

http://localhost:8000

## Changelog

### 2026-03-31
- Added a dark mode toggle for the calculator UI.
- Added theme preference persistence so the selected light or dark mode is restored on return visits.
- Added saved form state for calculator fields using cookies and local storage so in-progress entries persist across refreshes.
- Updated quest reward rules so DMs receive player-rate quest XP on Tier 1 and Tier 2 quests, and time-based RP XP on other quests.
- Updated quest reward rules so DMs receive gold at the player rate.
- Updated quest reward rules so players receive 1 SP per quest.
- Updated the Tier 1 / Tier 2 checkbox label to reflect the DM quest XP rule in the UI.
- Kept player mote rewards unchanged.
- Updated DM mote rewards so each quest grants 1 base mote even under 4 hours, with 1 additional mote for every 2 hours beyond the 4-hour base duration.
