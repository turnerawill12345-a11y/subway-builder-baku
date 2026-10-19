# Baku 🇦🇿

**A custom map of Baku, Azerbaijan, for Subway Builder.**  
**Creator:** William Turner · **Map code:** `BAKU` · **Version:** `v0.5.0`

Discover Baku, Azerbaijan's capital, where the historic Old City meets the modern Flame Towers on the shores of the Caspian Sea.

Explore the Absheron Peninsula, from industrial Sumqayit to the coastal settlements of Mardakan and Pirallahi, through bustling urban neighbourhoods, growing suburbs and seaside communities.

## Coverage and highlights

- Baku, Sumqayit, Khirdalan and much of the Absheron Peninsula, including Pirallahi.
- Detailed roads, buildings, place names, water features and coastal geography derived from OpenStreetMap.
- Suitable for recreating or expanding the Baku Metro and planning new suburban and regional rail routes.
- Simulated residential and workplace travel demand distributed across the mapped region.

## Map details

| Detail | Value |
| --- | --- |
| Map name | Baku |
| Country | Azerbaijan (`AZ`) |
| Map code | `BAKU` |
| Creator | William Turner |
| Current version | `v0.5.0` |
| Mapped bounds | 49.40°–50.42° E, 40.10°–40.72° N |
| Demand locations | 1,394 |
| Commuting groups | 76,351 |
| Simulated commuters | 1,345,134 |

## Travel-demand modelling and limitations

Residential distribution is informed by 2026 administrative population figures from the State Statistical Committee of Azerbaijan, together with OpenStreetMap mapped buildings and geography. Administrative boundaries do not exactly match the playable map bounds.

**Employment locations, commuter trips and modal behaviour are synthetic estimates**, rather than observations from a travel survey. The 1,345,134 figure represents **modelled commuters, not the region's total population**. Special airport, university, tourism and other attraction-based trip types have **not** been modelled as separate demand categories in this release. Ridership should therefore be treated as gameplay-oriented estimates, not official projections.

## Release and installation

Once the public release is published, download `BAKU.zip` from [Releases](https://github.com/turnerawill12345-a11y/subway-builder-baku/releases) and import the ZIP through **RailYard → Library → Import Asset**. Do not extract it before importing. A separate `manifest.json` release asset declares game-version compatibility.

## Screenshots

In-game screenshots of the final `v0.5.0` map will be added to the RailYard registry gallery before public listing.

## Data sources and acknowledgements

- **Geographic data:** © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), licensed under the Open Database License (ODbL); data extract and map processing with open-source tools.
- **Reference population statistics:** [State Statistical Committee of the Republic of Azerbaijan](https://www.stat.gov.az/), administrative-territorial population tables for the beginning of 2026.
- **Map processing:** community mapping tools including Depot, PMTiles and related geospatial utilities.

Map assembly and demand modelling: **William Turner**. This project is an unofficial community map and is not affiliated with the Subway Builder developers or the government of Azerbaijan.
