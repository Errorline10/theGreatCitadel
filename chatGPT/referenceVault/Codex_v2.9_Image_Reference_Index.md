# Codex v2.9 — Image Reference Index

Project: The Great Citadel
Version: v2.9
Role: Approved image reference registry for 360 room references, room blueprints, and door-render continuity assets.

---

# Index Status

This index defines the approved storage locations and status rules for visual reference assets.

Reference images listed here are canonical only when their status is approved canonical and the file is successfully retrieved or available in the active tool context.

At initial v2.9 publication, most image assets are placeholders until manually saved to GitHub and promoted by user approval.

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
- notes: Candidate 360 panorama was generated in chat and should be manually saved to this path before promotion.

## Blueprint Reference

- asset_id: garden_blueprint_v1
- path: /chatGPT/referenceVault/images/garden/garden_blueprint_v1.png
- status: missing
- purpose: Preserve Garden geometry, compass orientation, east doorway, northwest Buddha placement, raked sand, stacked stones, and major feature locations.
- use for: Garden 360 audits, Garden standard room renders, Garden door renders.

## Door Render References

### Entry Hall visible from Garden

- asset_id: door_entryHall_west_from_garden_v1
- path: /chatGPT/referenceVault/images/doors/garden_entryHall/door_entryHall_west_from_garden_v1.png
- status: missing
- purpose: Show Entry Hall through the Garden East Door when rendering Garden-facing-east views.
- source room: Garden
- source door: East Door
- destination room: Entry Hall
- destination door: West Door
- use for: Garden east-facing renders, Garden northeast/southeast views when the Entry Hall doorway is visible.

### Garden visible from Entry Hall

- asset_id: door_garden_east_from_entryHall_v1
- path: /chatGPT/referenceVault/images/doors/garden_entryHall/door_garden_east_from_entryHall_v1.png
- status: missing
- purpose: Show Garden through the Entry Hall West Door when rendering Entry Hall views where the west doorway is visible.
- source room: Entry Hall
- source door: West Door
- destination room: Garden
- destination door: East Door
- use for: Entry Hall north, northwest, west, and southwest-facing views when the Garden doorway is visible.

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
- use for: all Entry Hall standard room renders, Entry Hall compass-view continuity, Entry Hall visual audit.

## Blueprint Reference

- asset_id: entryHall_blueprint_v1
- path: /chatGPT/referenceVault/images/entryHall/entryHall_blueprint_v1.png
- status: missing
- purpose: Preserve Entry Hall geometry, north-south passage layout, North Door to Small Library, South Door to Outside, West Door to Garden, and major feature placement.
- use for: Entry Hall 360 audits, Entry Hall standard room renders, Entry Hall door renders.

## Door Render References

### Small Library visible from Entry Hall

- asset_id: door_smallLibrary_south_from_entryHall_v1
- path: /chatGPT/referenceVault/images/doors/entryHall_smallLibrary/door_smallLibrary_south_from_entryHall_v1.png
- status: missing
- purpose: Show Small Library through the Entry Hall North Door when rendering Entry Hall-facing-north views.
- source room: Entry Hall
- source door: North Door
- destination room: Small Library
- destination door: South Door
- use for: Entry Hall north-facing renders and adjacent compass views where the North Door is visible.

### Entry Hall visible from Small Library

- asset_id: door_entryHall_north_from_smallLibrary_v1
- path: /chatGPT/referenceVault/images/doors/entryHall_smallLibrary/door_entryHall_north_from_smallLibrary_v1.png
- status: missing
- purpose: Show Entry Hall through the Small Library South Door when rendering Small Library-facing-south views.
- source room: Small Library
- source door: South Door
- destination room: Entry Hall
- destination door: North Door
- use for: Small Library south-facing renders and adjacent compass views where the South Door is visible.

---

# Small Library Reference Set

Room: Small Library
Room slug: smallLibrary
Reference set: Small Library v1

## 360 Room Reference

- asset_id: smallLibrary_360_v1
- path: /chatGPT/referenceVault/images/smallLibrary/smallLibrary_360_v1.png
- status: missing
- purpose: Primary visual memory for Small Library room renders.

## Blueprint Reference

- asset_id: smallLibrary_blueprint_v1
- path: /chatGPT/referenceVault/images/smallLibrary/smallLibrary_blueprint_v1.png
- status: missing
- purpose: Preserve Small Library geometry, north-south linear path, northeast Instruction Manual and Guest Book station, South Door to Entry Hall, and North Door to Foundational Door / Great Hall.

---

# Great Hall Reference Set

Room: Great Hall
Room slug: greatHall
Reference set: Great Hall v1

## 360 Room Reference

- asset_id: greatHall_360_v1
- path: /chatGPT/referenceVault/images/greatHall/greatHall_360_v1.png
- status: missing
- purpose: Primary visual memory for Great Hall room renders and eight-spoke compass layout review.

## Blueprint Reference

- asset_id: greatHall_blueprint_v1
- path: /chatGPT/referenceVault/images/greatHall/greatHall_blueprint_v1.png
- status: missing
- purpose: Preserve Great Hall eight-opening radial compass geometry and Great Knowledge Compass placement.

---

# Retrieval Rule

Before using any reference image in a generation request, verify that the exact path can be fetched from GitHub or that the image has been uploaded/attached in the active chat.

Do not treat missing or candidate references as approved visual inputs.

Missing or candidate references may be mentioned in the compiled prompt as unavailable or pending.

End of Codex v2.9 — Image Reference Index.
