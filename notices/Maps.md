# Map credits

`HiddenCube.png` is the AION 2 Hidden Cube artwork © NCSOFT, obtained from the Aion2.gg Hidden Cube guide and converted to PNG.

- [Hidden Cube guide](https://aion2.gg/map/hidden-cubes)
- [Original artwork](https://26z9clbm06.ufs.sh/f/M3KtUJweBx2Qc72ddba2dc3a2dbf78e24506c8eecf0a097c16a79)

`Verteron.jpg` and `Altgard.jpg` are resized JPEGs of the 4096 × 4096 World_L_A and World_D_A overviews from AION2 Interactive Map by Yihao Liu (tc-imba), retrieved from the Aion 2 Map Overlay mirror. The upstream project distributes the map data under CC BY-NC 4.0. The game map artwork is NCSOFT game content.

`VerteronDetail.zip` and `AltgardDetail.zip` contain the corresponding native 8192 × 8192 detail layers from the same mirror, split into 1024 × 1024 JPEGs. Tiles are numbered left to right, then top to bottom, without resizing or changing the terrain extent.

- [AION2 Interactive Map and data license](https://github.com/aion2-interactive-map/aion2-interactive-map#-license)
- [Aion 2 Map Overlay source and attribution](https://github.com/problem-xyz/aion2-map-overlay/blob/45a1c733b7e6b50a378ded2453187a2a9ef5a64f/NOTICE)
- [Verteron detail manifest](https://github.com/problem-xyz/aion2-map-overlay/blob/45a1c733b7e6b50a378ded2453187a2a9ef5a64f/assets/maps/verteron/manifest.json)
- [Altgard detail manifest](https://github.com/problem-xyz/aion2-map-overlay/blob/45a1c733b7e6b50a378ded2453187a2a9ef5a64f/assets/maps/altgard/manifest.json)
- [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)

The World_L_A bounds (±408,000 world units) and most landmark positions come from Arkive’s published data. The network coordinate orientation, +X right and −Y up, was checked by comparing a live teleport to the published Hideout in Front of the Ruins map. The terrain alignment is approximate. Live player and cube markers use the same coordinate transform.

- [World bounds](https://github.com/arkive-games/arkive/blob/53a4be0a461030f2577ad1fa891e3ea6479840f2/docs/superpowers/plans/2026-06-27-phase-1a-coordinate-transform.md#concrete-reference-values-verified-2026-06-27)
- [Published marker positions](https://github.com/arkive-games/arkive/blob/53a4be0a461030f2577ad1fa891e3ea6479840f2/frontend/apps/aion2/public/data/markers/World_L_A.yaml)
- [Hideout in Front of the Ruins map](https://metabot.gg/en/aion-2/zones/hideout-in-front-of-the-ruins)

`VerteronCubeSpots.csv` contains the 114 unique XY pairs from the 118 `hiddenCube` records in Yihao Liu's Verteron marker file. The CSV preserves the original bottom-left coordinates on the 8192 × 8192 map and omits other marker types, metadata, and duplicates. AetherSync flips the catalog Y axis when plotting it on the artwork. The catalog covers a subset of possible Verteron spawns and is distributed under the source's CC BY-NC 4.0 terms.

- [Original Verteron marker file](https://github.com/aion2-interactive-map/aion2-interactive-map/blob/d5a18635e74016efcbcc6c279e9c121a9b09ef35/public/data/markers/World_L_A.yaml)
- [Source license](https://github.com/aion2-interactive-map/aion2-interactive-map/blob/master/LICENSE)

`AltgardCubeSpots.csv` contains the 107 unique XY pairs from the 108 `hiddenCube` records in Yihao Liu's Altgard marker file, with the same filtering and coordinate conversion. Altgard uses zone ID `1110`. The ±408,000 world-unit extent and wire orientation were checked against seven public Altgard kibelisk positions from the game's data. The largest difference in this cross-check was about 1,240 world units. Live placement on Asia Siel still needs a check.

- [Original Altgard marker file](https://github.com/aion2-interactive-map/aion2-interactive-map/blob/d5a18635e74016efcbcc6c279e9c121a9b09ef35/public/data/markers/World_D_A.yaml)
- [Published zone IDs](https://github.com/SkeeveAN/Aion-DPS-Meter/blob/4484641aab3b0a95a585422072e02b2e22b0684f/Client/assets/aion2/bosses/field_bosses.json)
- [Waypoint cross-check](https://github.com/SkeeveAN/Aion-DPS-Meter/blob/4484641aab3b0a95a585422072e02b2e22b0684f/Client/assets/aion2/maps/kibelisks.json)
