# Codex v2.9 — Render Continuity Rules

Project: The Great Citadel
Version: v2.9
Role: 360 room references, room blueprints, door renders, reference image retrieval, continuity priority, and render request lookup workflow.

---

# Purpose

The Great Citadel uses visual reference assets to improve continuity between renders.

These assets are not a substitute for the Codex. They are continuity aids that help future renders preserve room appearance, object placement, lighting, doorway views, and visual identity.

Canonical topology, compass bearings, room definitions, door locations, direct adjacency, and non-adjacency always take precedence over visual references.

---

# Reference Asset Types

## 360 Room Reference

A 360 Room Reference is a 2:1 equirectangular panorama generated from inside a room.

Purpose:

- Serve as the room's primary visual memory.
- Allow human inspection of the room from all directions.
- Provide continuity for future standard room renders.
- Reduce drift across repeated renders.

A 360 Room Reference may intentionally override the standard forward-hemisphere rule because it captures the full room.

## Room Blueprint Reference

A Room Blueprint Reference is a simple top-down or diagrammatic asset showing room geometry, compass orientation, door locations, major fixed features, and direct adjacency.

Purpose:

- Preserve geometry and compass placement.
- Clarify where doors, stations, and major objects belong.
- Support audit of 360 panoramas and standard room renders.

Blueprints do not replace Map Core.

## Door Render Reference

A Door Render Reference is a small visual reference showing what should be visible through a canonical open doorway from the source room into the destination room.

Purpose:

- Provide visual continuity for framed doorway views.
- Prevent generic-room substitutions beyond open doors.
- Preserve the immediate doorway relationship between adjacent rooms.

Door renders are generated in the opposite direction of the doorway view they support, using the destination room as seen through the source room's open door.

---

# Reference Image Folder Structure

Reference images belong under:

/chatGPT/referenceVault/images/

Recommended structure:

/chatGPT/referenceVault/images/{roomSlug}/
  {roomSlug}_360_v1.png
  {roomSlug}_blueprint_v1.png

/chatGPT/referenceVault/images/doors/{sourceRoomSlug}_{destinationRoomSlug}/
  door_{destinationRoomSlug}_{destinationDoorSlug}_from_{sourceRoomSlug}_v1.png
  door_{sourceRoomSlug}_{sourceDoorSlug}_from_{destinationRoomSlug}_v1.png

Example:

/chatGPT/referenceVault/images/garden/
  garden_360_v1.png
  garden_blueprint_v1.png

/chatGPT/referenceVault/images/entryHall/
  entryHall_360_v1.png
  entryHall_blueprint_v1.png

/chatGPT/referenceVault/images/doors/garden_entryHall/
  door_entryHall_west_from_garden_v1.png
  door_garden_east_from_entryHall_v1.png

---

# Naming Rules

Room slugs should be stable camelCase or lowerCamelCase identifiers:

- entryHall
- garden
- smallLibrary
- greatHall
- hallOfDiscovery
- mediaAntechamber
- historyAntechamber
- philosophyAntechamber
- artsAntechamber
- personalAntechamber
- inventorsAntechamber

360 room references use:

{roomSlug}_360_v{number}.png

Room blueprints use:

{roomSlug}_blueprint_v{number}.png

Door renders use:

door_{destinationRoomSlug}_{destinationDoorSlug}_from_{sourceRoomSlug}_v{number}.png

---

# Image Reference Index Rule

All approved, candidate, rejected, superseded, or missing reference images must be tracked in:

/chatGPT/referenceVault/Codex_v2.9_Image_Reference_Index.md

A reference image is active only when:

1. It is listed in the Image Reference Index.
2. Its status is approved canonical.
3. Its GitHub path is exact.
4. It is successfully fetched or otherwise available in the active tool context when needed for rendering.

---

# GitHub Image Retrieval Rule

When a render request needs reference images, the assistant must:

1. Read /chatGPT/referenceVault/Codex_v2.9_Image_Reference_Index.md.
2. Identify approved 360, blueprint, and door-render assets for the requested room, view, and visible doorway set.
3. Fetch the listed image files from GitHub by exact repository path when tool support permits image retrieval.
4. Use only verified fetched images as visual reference inputs.
5. If a referenced image cannot be fetched, report the missing path and continue with text-only Codex rules only when the image is not required.
6. Do not assume an image exists because it is listed in the index.

A GitHub path is metadata, not the image itself. For image generation, the referenced image must be available as an actual fetched, uploaded, or attached image in the current chat/tool context before it can be used as a visual reference.

---

# Reference Resolution Order

When compiling a room render, resolve visual continuity sources in this order:

1. Door Render Reference for any visible open doorway.
2. 360 Room Reference for the requested room.
3. Room Blueprint Reference for the requested room.
4. Room Render Definitions.
5. Room Index topology.
6. Map Core topology and compass rules.
7. General Citadel Canon.

This order controls visual continuity only. Topology and canon always override image references if conflict occurs.

---

# 360 Room Reference Workflow

When the user requests a 360 room reference:

1. Identify the requested room.
2. Compile room topology from Room Index and Map Core.
3. Compile room visual identity from Room Render Definitions.
4. Override standard render format to 2:1 equirectangular panorama.
5. Override standard forward-hemisphere rule so the full room may be visible.
6. Preserve fixed compass orientation.
7. Include all canonical doors on their correct compass walls.
8. Include required room features.
9. Exclude non-canonical doors, corridors, buildings, shortcuts, and connections.
10. Print the compiled prompt and ask for approval before generation.
11. After generation, audit the panorama before it can be promoted as an approved canonical reference.

---

# Room Blueprint Workflow

When the user requests a room blueprint:

1. Identify the requested room.
2. Use fixed compass orientation: North top, East right, South bottom, West left.
3. Show room boundary, canonical doors, major fixed features, stations, and direct adjacency.
4. Exclude non-canonical connections.
5. Use topology over decoration.
6. Print the compiled prompt and ask for approval before generation.
7. After generation, audit against Room Index and Map Core before promotion.

---

# Door Render Workflow

When the user requests a door render or when an open doorway is visible in a room render:

1. Identify the source room.
2. Identify the source door.
3. Identify the destination room.
4. Identify the destination door and its canonical compass wall.
5. Compile the destination-room view as seen through the source room's open doorway.
6. Preserve immediate doorway continuity. Do not invent an intermediate corridor unless one is canonically defined.
7. Use the destination room's visual canon, not generic fantasy imagery.
8. Keep the door render focused on what would be visible through the doorway, not a full-room hero shot unless explicitly requested.
9. Print the compiled prompt and ask for approval before generation.
10. After generation, audit before promotion.

---

# Open Door Continuity Rule

When a standard room render includes an open canonical doorway, the visible space beyond that doorway must be derived from the approved Door Render Reference for that connection when one exists.

If no approved Door Render Reference exists, derive the visible space from the destination room's Room Index, Room Render Definitions, and compass orientation.

Never use a generic library, generic hall, generic garden, generic corridor, or generic fantasy room beyond an open doorway when a canonical destination room is known.

---

# 45-Degree Continuity Rule

When generating adjacent compass views of the same room, the assistant should use the approved 360 Room Reference as the primary continuity source.

If no approved 360 Room Reference exists, use the nearest approved compass render or door render when available.

Adjacent compass views are:

North -> Northeast -> East -> Southeast -> South -> Southwest -> West -> Northwest -> North

The purpose is to preserve visible overlap between directions and reduce visual drift.

---

# Promotion Rule

Generated images are not canonical merely because they were generated.

To promote an image to approved canonical reference status:

1. The image must be audited against the active Codex.
2. The user must approve it as a canonical reference.
3. The image file must be saved in the correct GitHub reference image path.
4. The Image Reference Index must be updated with path, status, purpose, and version.

---

# Missing Reference Handling

If the Image Reference Index lists a reference image that cannot be retrieved, report:

- room
- reference type
- missing path
- whether rendering can continue text-only

Do not silently ignore missing references.

---

# Conflict Handling

If a reference image contradicts canonical topology, the image is non-canonical or partially non-canonical.

Textual Codex topology wins over visual reference images.

The assistant must not reproduce reference-image mistakes in future renders.

End of Codex v2.9 — Render Continuity Rules.
