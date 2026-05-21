# 🎣 Fishing Log Dashboard

An interactive, single-file fishing tournament dashboard built with HTML, CSS, and Chart.js. Tracks catch records across anglers, species, and years with a Power BI-style interface.

**[View Live Dashboard →](https://stevencarota.github.io/fishing-dashboard)**

---

## Features

- **Year & species filters** — toggle any combination of years (2023–2026) and species to isolate the data you care about
- **Angler dropdown** — drill into a single fisherman's record across all years
- **Size range sliders** — filter catches by minimum and maximum fish length to focus on trophy fish
- **Catches by angler** — horizontal bar chart showing volume leaders, colour-coded by dominant species
- **Species breakdown** — doughnut chart with percentage splits across Walleye, Pike, and Bass
- **Length distribution** — histogram of fish sizes in 5 cm bins, reactive to the size sliders
- **Year-over-year** — bar chart showing total catch volume per season
- **Biggest fish leaderboard** — ranked table of each angler's personal best catch with species and year

All charts and metrics update simultaneously when any filter changes.

---

## Data

Catch records from **2023 to 2026** covering the following anglers:

> Adam · Frank · James · Joe Fisc · Joey · Jon · Justin · Mauro · Mike · Rob · Roy · Ryan · Shawn · Steve · Tim · Wayne

Species tracked: **Walleye**, **Pike**, **Bass** (including Smallmouth Bass)

### Data quality notes

- 2024 Pike entries are largely recorded as 45 cm — likely estimated values, not exact measurements
- Two 2026 entries (9 cm Walleye) appear to be data entry errors
- 2023 data contains many repeated values consistent with estimated/rounded measurements

---

## Usage

No build step. No dependencies to install. Just open `index.html` in any modern browser.

```bash
# Clone the repo
git clone https://github.com/stevencarota/fishing-dashboard.git

# Open directly
open fishing-dashboard/index.html
```

Or visit the live GitHub Pages link above.

---

## Tech stack

| Layer | Tool |
|---|---|
| Structure & logic | Vanilla HTML + JavaScript |
| Charts | [Chart.js 4.4.1](https://www.chartjs.org/) via CDN |
| Fonts | [DM Sans + DM Mono + Playfair Display](https://fonts.google.com/) via Google Fonts |
| Hosting | GitHub Pages |

No frameworks. No build tools. One file.

---

## Screenshot

> *(Add a screenshot here — press `Cmd+Shift+4` on Mac or `Win+Shift+S` on Windows, then drag the image into the repo)*

---

## License

Data is private catch records. Dashboard code is free to reuse and adapt.
