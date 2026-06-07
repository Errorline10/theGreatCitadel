# Codex v3.2 — Image Reference Index

Project: The Great Citadel
Version: v3.2
Role: Approved image reference registry for 360 room references, room blueprints, exterior references, door-render continuity assets, reference metadata, and recommended save paths.
Supersedes: /chatGPT/referenceVault/Codex_v3.1_Image_Reference_Index.md

---

# Index Status

This index defines approved storage locations and status rules for visual reference assets.

Reference images listed here are canonical as actual visual inputs only when their status is approved canonical and the file is successfully retrieved or available in the active tool context.

Reference entries may be used as descriptive continuity metadata without requiring the image file to be loaded, unless the user explicitly asks to use actual reference images.

All 360 equirectangular references must satisfy the 360 Panorama Compass Normalization Rule in /chatGPT/renderVault/Codex_v3.2_Render_Continuity_Rules.md before promotion.

---

# Status Values

approved canonical: reviewed, accepted, and usable as visual continuity reference.

candidate: generated or planned but not yet approved.

missing: expected path exists in the reference plan but file has not yet been saved or verified.

rejected: not canonical and must not be used as reference.

superseded: replaced by a newer approved reference.

---

# Root Image Folder

/chatGPT/referenceVault/images/

---

# Outside of the Citadel Reference Set

Exterior location: Outside of the Citadel
Location slug: outsideCitadel
Reference set: Outside Citadel v1

## Aerial Northwest Reference

- asset_id: outsideCitadel_aerialNW_v1
- path: /chatGPT/referenceVault/images/outsideCitadel/outsideCitadel_aerialNW_v1.png
- status: approved canonical
- purpose: Primary exterior aerial northwest reference for Outside of the Citadel.
- station: Aerial Overview Station
- use for: exterior overview renders, exterior continuity, exterior audit, exterior station development.
- notes: User approved the render as the canonical exterior direction and intends to manually upload it to this path. If retrieval fails, report the path as missing if actual image input is required.

## Exterior Blueprint Reference

- asset_id: outsideCitadel_blueprint_v1
- path: /chatGPT/referenceVault/images/outsideCitadel/outsideCitadel_blueprint_v1.png
- status: missing
- purpose: Preserve exterior compass geometry, main dome, eight smaller domes, Entry Hall exterior mass, Garden west of Entry Hall, bridge southwest, and southwest landing platform.

---

# Garden Reference Set

Room: Garden
Room slug: garden
Reference set: Garden v1

## 360 Room Reference

- asset_id: garden_360_v1
- path: /chatGPT/referenceVault/images/garden/garden_360_v1.png
- status: candidate
- purpose: Primary visual memory for Garden room renders and interactive 360 review.
- use for: all Garden standard room renders, Garden compass-view continuity, Garden visual audit.
- normalization: must be center North, right quarter East, left quarter West, far edges South seam before promotion.

## Blueprint Reference

- asset_id: garden_blueprint_v1
- path: /chatGPT/referenceVault/images/garden/garden_blueprint_v1.png
- status: missing
- purpose: Preserve Garden geometry, compass orientation, east doorway, northwest Buddha placement, raked sand, stacked stones, and major feature locations.

## Door Render References

- asset_id: door_entryHall_west_from_garden_v1
- path: /chatGPT/referenceVault/images/doors/garden_entryHall/door_entryHall_west_from_garden_v1.png
- status: missing
- purpose: Show Entry Hall through the Garden East Door when rendering Garden-facing-east views.

- asset_id: door_garden_east_from_entryHall_v1
- path: /chatGPT/referenceVault/images/doors/garden_entryHall/door_garden_east_from_entryHall_v1.png
- status: missing
- purpose: Show Garden through the Entry Hall West Door when rendering Entry Hall views where the west doorway is visible.

---

# Entry Hall Reference Set

Room: Entry Hall
Room slug: entryHall
Reference set: Entry Hall v1

- asset_id: entryHall_360_v1
- path: /chatGPT/referenceVault/images/entryHall/entryHall_360_v1.png
- status: missing
- purpose: Primary visual memory for Entry Hall room renders and interactive 360 review.
- normalization: must be center North, right quarter East, left quarter West, far edges South seam before promotion.

- asset_id: entryHall_blueprint_v1
- path: /chatGPT/referenceVault/images/entryHall/entryHall_blueprint_v1.png
- status: missing
- purpose: Preserve Entry Hall geometry, north-south passage layout, North Door to Small Library, South Door to Outside, West Door to Garden, and major feature placement.

---

# Hall of Discovery Reference Set

Room: Hall of Discovery
Room slug: hallOfDiscovery
Reference set: Hall of Discovery v1

- asset_id: hallOfDiscovery_360_v1
- path: /chatGPT/referenceVault/images/hallOfDiscovery/hallOfDiscovery_360_v1.png
- status: candidate
- purpose: Primary visual memory for Hall of Discovery 360 review and future standard renders.
- normalization: center North, right quarter East, left quarter West, far edges South seam.
- door count: exactly four canonical doors only.
- center capture: true geometric center of room.
- overlay rule: no labels, arrows, captions, UI graphics, or compass text unless explicitly requested.

- asset_id: hallOfDiscovery_blueprint_v1
- path: /chatGPT/referenceVault/images/hallOfDiscovery/hallOfDiscovery_blueprint_v1.png
- status: missing
- purpose: Preserve Hall of Discovery compass geometry, true center point, Astronomy north, Logic east, Science south, Biology west, Map of Understanding, Compass Rose of Discovery, Celestial Vault, and Eight Alcoves of Discovery.

## Hall of Discovery Door Render References

- asset_id: door_astronomy_north_from_hallOfDiscovery_v1
- path: /chatGPT/referenceVault/images/doors/hallOfDiscovery_astronomy/door_astronomy_north_from_hallOfDiscovery_v1.png
- status: missing
- purpose: Show Astronomy through the Hall of Discovery North Door.

- asset_id: door_biology_west_from_hallOfDiscovery_v1
- path: /chatGPT/referenceVault/images/doors/hallOfDiscovery_biology/door_biology_west_from_hallOfDiscovery_v1.png
- status: missing
- purpose: Show Biology through the Hall of Discovery West Door.

- asset_id: door_logic_east_from_hallOfDiscovery_v1
- path: /chatGPT/referenceVault/images/doors/hallOfDiscovery_logic/door_logic_east_from_hallOfDiscovery_v1.png
- status: missing
- purpose: Show Logic through the Hall of Discovery East Door.

- asset_id: door_greatHall_south_from_hallOfDiscovery_v1
- path: /chatGPT/referenceVault/images/doors/hallOfDiscovery_greatHall/door_greatHall_south_from_hallOfDiscovery_v1.png
- status: missing
- purpose: Show Great Hall through the Hall of Discovery South Science Door.

---

# Retrieval Rule

Before using any reference image as an actual visual input in a generation request, verify that the exact path can be fetched from GitHub or that the image has been uploaded/attached in the active chat.

Do not claim a missing or candidate reference image has been loaded.

Do not treat missing or candidate references as approved visual inputs.

If an approved canonical reference path cannot be fetched and actual image input is required, report the missing path and do not silently substitute a generic image.

If actual image input is not required, reference entries may be used as descriptive metadata only.

End of Codex v3.2 — Image Reference Index.