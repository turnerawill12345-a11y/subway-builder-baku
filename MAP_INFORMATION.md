# Baku — Map Information and Data Quality

**Creator:** William Turner  
**Game:** Subway Builder (RailYard community map)  
**Map name:** Baku  
**City code:** `BAKU`  
**Country:** Azerbaijan (`AZ`)  
**Release:** v0.5.0

## Map description

Discover Baku, Azerbaijan's capital, where the historic Old City meets the modern Flame Towers on the shores of the Caspian Sea.

Explore the Absheron Peninsula, from industrial Sumqayit to the coastal settlements of Mardakan and Pirallahi, through bustling urban neighbourhoods, growing suburbs and seaside communities.

## Geographic coverage

Baku and substantial portions of the Absheron Peninsula, including Sumqayit, Khirdalan, Mardakan, and Pirallahi.

| Attribute | Value |
| --- | --- |
| Bounding coordinates | 49.40°–50.42° E, 40.10°–40.72° N |
| Approximate east–west extent | 86.6 km |
| Approximate north–south extent | 68.8 km |
| **Total bounding-box area** | **5,961 km²**, including sea |
| **Estimated land area within bounding box** | **2,512 km²**, excluding mapped water |
| Estimated mapped-water area | Approximately 3,449 km² |
| Roads in supplied GeoJSON | 12,551 road features |
| Indexed buildings | 46,442 |
| Runway and taxiway features | 258 |

**Area methodology:** Area was derived from the v0.5.0 basemap's water polygons, clipped to the map bounding box and measured using an equal-area projection. The level-10 and level-11 layers produce approximately 2,514 and 2,512 km² of land respectively. These are approximate GIS measurements, **not an official administrative area or a validated measure of land suitable for construction**. The bounding rectangle extends into the Caspian Sea and is not the same as the administrative extent of Baku.

## Population and transport demand

| Attribute | Value |
| --- | --- |
| Reference population, beginning of 2026 | 3,219,600 |
| Population geography | The 12 Baku administrative districts, Sumqayit city and Absheron district, not a precise clipped in-map census |
| Residential/workplace demand locations | 1,394 |
| Synthetic origin–destination commuting groups | 76,351 |
| Simulated commuters | 1,345,134 |

**Do not equate the reference population to the population inside the playable bounding box.** Some administrative districts and settlements extend outside the map's geographic bounds. Likewise, the 1,345,134 commuters are a **synthetic trip-making cohort**, not an official census count, employment total, or ridership prediction.

**Demand methodology:** The demand model allocates population using 2026 administrative statistics, OSM building locations, and spatial heuristics. Jobs are placed using heuristic commercial and centrality weights. Commuting flows are generated with a synthetic home–work model and approximate trip distances and durations; actual recorded commuting, measured workplace employment, observed mode shares and road network routing are **not** inputs. The map has been successfully loaded in-game and visually checked, but demand has not been independently calibrated against a public travel survey.

## Special demand

The basemap shows some airports, hospitals, educational facilities, parks and other amenities as geographic features, but **this release does not create separate category-specific visitor or passenger demand**.

| Feature | Geographic visualization | Dedicated simulated demand |
| --- | --- | --- |
| Airports, runways, taxiways | Yes | No airport passenger demand |
| Hospitals | Mapped healthcare land use | No special patient/visitor demand |
| Universities and colleges | Some mapped educational sites | No separate student demand |
| Parks and attractions | Some mapped features | No separate visitor demand |
| Homes and workplaces | Yes | Yes, synthetic commuting |

**RailYard special-demand tags:** select **none** for airports, hospitals, universities, schools, entertainment, parks and ferries until these categories are explicitly added to the model.

## Data sources

1. [OpenStreetMap contributors](https://www.openstreetmap.org/copyright) — roads, coastlines, buildings, points of interest and geographic features, distributed under ODbL; original extraction date October 2026.
2. [State Statistical Committee of the Republic of Azerbaijan](https://www.stat.gov.az/) — 2026 administrative population reference tables.
3. Map assembly and simulation using community map tools and custom Python processing (including Depot, Planetiler, PMTiles and other OSM utilities).

**Limitations:** GIS datasets may be incomplete; OSM building coverage is uneven; administrative figures are not neatly clipped to the map's landmass; job counts and commute flows are heuristic rather than empirically validated. These considerations matter when comparing this map's demand data with census-calibrated or travel-survey-calibrated releases.

## Gallery assets

Requested cover artwork: the user's Baku city emblem (submitted image 2).

Requested in-game gallery order:
1. Residential demand overview (submitted image 1)
2. Clean full-map overview (submitted image 3)
3. Central Baku street detail (submitted image 5)
4. Suburban coastal detail (submitted image 4)

The current **Publish New Map** form exposes one `Gallery Images` field, without a dedicated cover-art field. The emblem should be added first if the registry uses the first gallery image as its card preview; the four game screenshots should follow in the exact order above.

## Source code and releases

[Repository](https://github.com/turnerawill12345-a11y/subway-builder-baku) · [Releases](https://github.com/turnerawill12345-a11y/subway-builder-baku/releases)

This is an unofficial user-created map, not affiliated with the Subway Builder developers or Azerbaijan's national or local authorities.
