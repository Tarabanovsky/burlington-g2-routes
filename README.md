# Burlington G2 practice routes

An unofficial practice app for the **G2 road test at DriveTest Burlington** (1250 Brant St). It shows
three routes that test-takers have reported, with checkpoints for each turn, stop sign, speed-limit
change and the likely 3-point-turn spot. Each checkpoint has coaching from the official Ontario MTO
Driver's Handbook.

- **On a phone:** open the site, choose a route, tap **Start drive**, and drive. GPS tracking moves
  through the checkpoints on its own, and **Voice** reads each one aloud.
- **On a laptop:** use **Tap through** mode to step through the checkpoints (Next/Back, click a
  checkpoint, or click the progress bar; the arrow keys work too).

**Unofficial.** DriveTest does not publish routes, and examiners vary them. The turn-by-turn comes
from 2018 test-taker reports; the same areas are still named in 2022–2026 reports. The drive back to
the centre and the exact 3-point-turn spot are inferred, and the app labels them that way.

**Safety.** Mount the phone and start before you move. In Ontario a driver may not hold or touch a
phone while driving, and a G1 or G2 driver's first conviction means a 30-day suspension
([ontario.ca](https://www.ontario.ca/page/distracted-driving)).

## Data and licences
- Road geometry, speed limits, signals and stop signs: © OpenStreetMap contributors,
  [ODbL](https://www.openstreetmap.org/copyright). Map tiles: OpenStreetMap
  ([tile usage policy](https://operations.osmfoundation.org/policies/tiles/)).
- Coaching text: paraphrased from *The Official MTO Driver's Handbook*
  ([ontario.ca](https://www.ontario.ca/document/print/book/80362)).
- Map library: [Leaflet](https://leafletjs.com) 1.9.4, BSD-2-Clause (`vendor/leaflet/LICENSE`).

The `data.js` file is generated, so don't edit it by hand. It's built from the research folder
`research/xx-01-burlington-g2-routes` in Eugene's `ai-lab` repo
(`python3 scripts/build_routes.py`), and the full sources are listed in the app under **About**.
