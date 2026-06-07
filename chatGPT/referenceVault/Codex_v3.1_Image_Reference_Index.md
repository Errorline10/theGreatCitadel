# Codex v3.1 — Image Reference Index

Project: The Great Citadel
Version: v3.1
Role: Approved image reference registry for 360 room references, room blueprints, exterior references, and door-render continuity assets.
Supersedes: /chatGPT/referenceVault/Codex_v3.0_Image_Reference_Index.md

---

# Index Status

This index defines approved storage locations and status rules for visual reference assets.

Reference images listed here are canonical only when their status is approved canonical and the file is successfully retrieved or available in the active tool context.

All 360 equirectangular references must satisfy the 360 Panorama Compass Normalization Rule in /chatGPT/renderVault/Codex_v3.1_Render_Continuity_Rules.md before promotion.

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
- notes: User approved the render as the canonical exterior direction and intends to manually upload it to this path. If retrieval fails, report the path as missing until the image is present in GitHub.

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

# Retrieval Rule

Before using any reference image in a generation request, verify that the exact path can be fetched from GitHub or that the image has been uploaded/attached in the active chat.

Do not treat missing or candidate references as approved visual inputs.

If an approved canonical reference path cannot be fetched, report the missing path and do not silently substitute a generic image.

End of Codex v3.1 — Image Reference Index.
