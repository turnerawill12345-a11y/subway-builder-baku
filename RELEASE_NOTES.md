# Baku — v0.5.0

**Created by William Turner** · 🇦🇿 Azerbaijan · City code `BAKU`

Discover Baku, Azerbaijan's capital, where the historic Old City meets the modern Flame Towers on the shores of the Caspian Sea.

Explore the Absheron Peninsula, from industrial Sumqayit to the coastal settlements of Mardakan and Pirallahi, through bustling urban neighbourhoods, growing suburbs and seaside communities.

## Features

- Geographic coverage of metropolitan Baku, Sumqayit and the Absheron Peninsula.
- OpenStreetMap-derived streets, building footprints, place names and coastlines.
- Residential and workplace demand at 1,394 demand locations.
- 76,351 synthetic commuting groups representing 1,345,134 modelled commuters.
- Pirallahi Island land/water rendering correction and more balanced residential and workplace bubble placement.

## Data and quality notes

2026 State Statistical Committee of Azerbaijan population statistics inform residential demand. Detailed commuter origins, job destinations and mode choice are **synthetic** and are not calibrated against an observed commuting survey. The simulated commuter count is **not** the total regional population. No separate special-demand categories (airports, universities, attractions, etc.) are modelled in this release.

## Attribution

Map and model assembled by **William Turner**. Geographic features © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), ODbL. Reference population tables © State Statistical Committee of the Republic of Azerbaijan (subject to agency terms).

## Release assets

`BAKU.zip` — map ZIP with config, tiles, buildings, road geometry and demand data, with files at archive root. `manifest.json` — separate manifest declaring compatible Subway Builder versions.

**Compatibility note:** The manifest currently declares `>=1.7.2`; confirm this matches the game build in which Baku was tested. This release has been play-tested by the creator, but travel-demand realism has not been externally validated.
