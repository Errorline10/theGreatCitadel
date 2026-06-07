# Codex v3.0 — Image Reference Index

Project: The Great Citadel
Version: v3.0
Role: Approved image reference registry for 360 room references, room blueprints, exterior references, and door-render continuity assets.
Supersedes: /chatGPT/referenceVault/Codex_v2.9_Image_Reference_Index.md

---

# Index Status

This index defines approved storage locations and status rules for visual reference assets.

Reference images listed here are canonical only when their status is approved canonical and the file is successfully retrieved or available in the active tool context.

At v3.0 publication, the exterior aerial northwest render is listed as approved canonical at the path selected for manual upload. If the file has not yet been manually uploaded, retrieval must report it as unavailable until present.

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

## Bridge Arrival Reference

- asset_id: outsideCitadel_bridgeArrival_v1
- path: /chatGPT/referenceVault/images/outsideCitadel/outsideCitadel_bridgeArrival_v1.png
- status: missing
- purpose: View from southwest bridge toward the Citadel.

## Garden Exterior Reference

- asset_id: outsideCitadel_gardenExterior_v1
- path: /chatGPT/referenceVault/images/outsideCitadel/outsideCitadel_gardenExterior_v1.png
- status: missing
- purpose: Exterior view focused on the Garden west of Entry Hall exterior mass.

## North Dome Reference

- asset_id: outsideCitadel_northDome_v1
- path: /chatGPT/referenceVault/images/outsideCitadel/outsideCitadel_northDome_v1.png
- status: missing
- purpose: Exterior view focused on the northern main dome and eight smaller dome arrangement.

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

## 360 Room Reference

- asset_id: entryHall_360_v1
- path: /chatGPT/referenceVault/images/entryHall/entryHall_360_v1.png
- status: missing
- purpose: Primary visual memory for Entry Hall room renders and interactive 360 review.

## Blueprint Reference

- asset_id: entryHall_blueprint_v1
- path: /chatGPT/referenceVault/images/entryHall/entryHall_blueprint_v1.png
- status: missing
- purpose: Preserve Entry Hall geometry, north-south passage layout, North Door to Small Library, South Door to Outside, West Door to Garden, and major feature placement.

## Door Render References

- asset_id: door_smallLibrary_south_from_entryHall_v1
- path: /chatGPT/referenceVault/images/doors/entryHall_smallLibrary/door_smallLibrary_south_from_entryHall_v1.png
- status: missing
- purpose: Show Small Library through the Entry Hall North Door when rendering Entry Hall-facing-north views.

- asset_id: door_entryHall_north_from_smallLibrary_v1
- path: /chatGPT/referenceVault/images/doors/entryHall_smallLibrary/door_entryHall_north_from_smallLibrary_v1.png
- status: missing
- purpose: Show Entry Hall through the Small Library South Door when rendering Small Library-facing-south views.

---

# Small Library Reference Set

Room: Small Library
Room slug: smallLibrary
Reference set: Small Library v1

- asset_id: smallLibrary_360_v1
- path: /chatGPT/referenceVault/images/smallLibrary/smallLibrary_360_v1.png
- status: missing
- purpose: Primary visual memory for Small Library room renders.

- asset_id: smallLibrary_blueprint_v1
- path: /chatGPT/referenceVault/images/smallLibrary/smallLibrary_blueprint_v1.png
- status: missing
- purpose: Preserve Small Library geometry, north-south linear path, northeast Instruction Manual and Guest Book station, South Door to Entry Hall, and North Door to Foundational Door / Great Hall.

---

# Great Hall Reference Set

Room: Great Hall
Room slug: greatHall
Reference set: Great Hall v1

- asset_id: greatHall_360_v1
- path: /chatGPT/referenceVault/images/greatHall/greatHall_360_v1.png
- status: missing
- purpose: Primary visual memory for Great Hall room renders and eight-spoke compass layout review.

- asset_id: greatHall_blueprint_v1
- path: /chatGPT/referenceVault/images/greatHall/greatHall_blueprint_v1.png
- status: missing
- purpose: Preserve Great Hall eight-opening radial compass geometry and Great Knowledge Compass placement.

---

# Retrieval Rule

Before using any reference image in a generation request, verify that the exact path can be fetched from GitHub or that the image has been uploaded/attached in the active chat.

Do not treat missing or candidate references as approved visual inputs.

If an approved canonical reference path cannot be fetched, report the missing path and do not silently substitute a generic image.

End of Codex v3.0 — Image Reference Index.
