# Codex v3.0 — Render Continuity Rules

Project: The Great Citadel
Version: v3.0
Role: 360 room references, room blueprints, exterior references, door renders, reference image retrieval, continuity priority, and render request lookup workflow.
Supersedes: /chatGPT/renderVault/Codex_v2.9_Render_Continuity_Rules.md

---

# Purpose

The Great Citadel uses visual reference assets to improve continuity between renders.

These assets are continuity aids that help future renders preserve room appearance, exterior appearance, object placement, lighting, doorway views, and visual identity.

Canonical topology, compass bearings, room definitions, exterior definitions, door locations, direct adjacency, and non-adjacency always take precedence over visual references.

---

# Reference Asset Types

## 360 Room Reference

A 360 Room Reference is a 2:1 equirectangular panorama generated from inside a room.

Purpose: serve as the room's primary visual memory, allow human inspection from all directions, and provide continuity for future standard room renders.

## Room Blueprint Reference

A Room Blueprint Reference is a simple top-down or diagrammatic asset showing room geometry, compass orientation, door locations, major fixed features, and direct adjacency.

## Exterior Reference

An Exterior Reference is an approved view of the Outside of the Citadel, such as aerial northwest, bridge arrival, garden exterior, or exterior blueprint.

Exterior references preserve the overall Citadel silhouette, dome arrangement, mountain placement, bridge direction, landing platform placement, and exterior Garden placement.

## Door Render Reference

A Door Render Reference is a small visual reference showing what should be visible through a canonical open doorway from the source room into the destination room.

---

# Reference Image Folder Structure

Reference images belong under:

/chatGPT/referenceVault/images/

Recommended structure:

/chatGPT/referenceVault/images/{roomSlug}/
  {roomSlug}_360_v1.png
  {roomSlug}_blueprint_v1.png

/chatGPT/referenceVault/images/outsideCitadel/
  outsideCitadel_aerialNW_v1.png
  outsideCitadel_blueprint_v1.png
  outsideCitadel_bridgeArrival_v1.png
  outsideCitadel_gardenExterior_v1.png

/chatGPT/referenceVault/images/doors/{sourceRoomSlug}_{destinationRoomSlug}/
  door_{destinationRoomSlug}_{destinationDoorSlug}_from_{sourceRoomSlug}_v1.png

---

# Image Reference Index Rule

All approved, candidate, rejected, superseded, or missing reference images must be tracked in:

/chatGPT/referenceVault/Codex_v3.0_Image_Reference_Index.md

A reference image is active only when it is listed in the Image Reference Index, its status is approved canonical, its GitHub path is exact, and it is successfully fetched or otherwise available in the active tool context when needed for rendering.

---

# GitHub Image Retrieval Rule

When a render request needs reference images, the assistant must:

1. Read /chatGPT/referenceVault/Codex_v3.0_Image_Reference_Index.md.
2. Identify approved reference assets for the requested room, exterior location, station, view, or visible doorway set.
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

When compiling an exterior render, resolve visual continuity sources in this order:

1. Approved exterior reference for the requested exterior station or nearest view.
2. Exterior blueprint reference.
3. Exterior Index.
4. Map Core exterior alignment rules.
5. Render Core exterior audit rules.
6. General Citadel Canon.

This order controls visual continuity only. Topology and canon always override image references if conflict occurs.

---

# 360 Room Reference Workflow

When the user requests a 360 room reference, identify the requested room, compile topology and visual identity, override standard render format to 2:1 equirectangular panorama, override the forward-hemisphere rule, preserve fixed compass orientation, include all canonical doors on correct compass walls, include required room features, exclude non-canonical connections, print the compiled prompt, and ask for approval before generation.

---

# Room Blueprint Workflow

When the user requests a room blueprint, use fixed compass orientation with North top, East right, South bottom, and West left. Show room boundary, canonical doors, major fixed features, stations, and direct adjacency. Exclude non-canonical connections.

---

# Exterior Reference Workflow

When the user requests an exterior reference, use Exterior Index as the controlling source. Select the station or exterior view. Preserve exterior structural rules, southwest bridge and landing platform rules, Garden west of Entry Hall exterior mass, and unified no-hallway structure rules. Print the compiled prompt and ask for approval before generation.

---

# Door Render Workflow

When the user requests a door render or when an open doorway is visible in a room render, identify the source room, source door, destination room, destination door, and canonical compass wall. Compile the destination-room view as seen through the source room's open doorway. Preserve immediate doorway continuity and do not invent an intermediate corridor unless one is canonically defined.

---

# Open Door Continuity Rule

When a standard room render includes an open canonical doorway, the visible space beyond that doorway must be derived from the approved Door Render Reference for that connection when one exists.

If no approved Door Render Reference exists, derive the visible space from the destination room's Room Index, Room Render Definitions, and compass orientation.

Never use a generic room beyond an open doorway when a canonical destination room is known.

---

# Promotion Rule

Generated images are not canonical merely because they were generated.

To promote an image to approved canonical reference status:

1. The image must be audited against the active Codex.
2. The user must approve it as a canonical reference.
3. The image file must be saved in the correct GitHub reference image path.
4. The Image Reference Index must be updated with path, status, purpose, and version.

---

# Conflict Handling

If a reference image contradicts canonical topology, exterior structure, or room canon, the image is non-canonical or partially non-canonical.

Textual Codex topology and exterior rules win over visual reference images.

The assistant must not reproduce reference-image mistakes in future renders.

End of Codex v3.0 — Render Continuity Rules.
