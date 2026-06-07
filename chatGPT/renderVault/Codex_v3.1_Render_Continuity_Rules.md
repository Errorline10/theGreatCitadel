# Codex v3.1 — Render Continuity Rules

Project: The Great Citadel
Version: v3.1
Role: 360 room references, 360 panorama compass normalization, room blueprints, exterior references, door renders, reference image retrieval, continuity priority, and render request lookup workflow.
Supersedes: /chatGPT/renderVault/Codex_v3.0_Render_Continuity_Rules.md

---

# Purpose

The Great Citadel uses visual reference assets to improve continuity between renders.

These assets are continuity aids that help future renders preserve room appearance, exterior appearance, object placement, lighting, doorway views, compass consistency, and visual identity.

Canonical topology, compass bearings, room definitions, exterior definitions, door locations, direct adjacency, and non-adjacency always take precedence over visual references.

---

# 360 Panorama Compass Normalization Rule

All 360 equirectangular room and exterior reference images must use a fixed compass origin.

The horizontal center of the panorama represents canonical North.

Compass mapping:

- Horizontal center = North.
- Right quarter = East.
- Left quarter = West.
- Far left edge and far right edge form the South seam.

The Citadel does not rotate. The panorama capture rotates around the fixed Citadel coordinate system.

If a 360 image is generated with a different compass origin, it must be marked non-canonical or regenerated before promotion.

For the Garden 360 reference, the Entry Hall doorway on the east wall should appear around the right-quarter position, and the northwest Buddha should appear between the left-quarter West position and the center North position.

---

# Reference Asset Types

## 360 Room Reference

A 360 Room Reference is a 2:1 equirectangular panorama generated from inside a room and normalized so the image center is North.

## Room Blueprint Reference

A Room Blueprint Reference is a top-down or diagrammatic asset showing room geometry, compass orientation, door locations, major fixed features, and direct adjacency.

## Exterior Reference

An Exterior Reference is an approved view of the Outside of the Citadel, such as aerial northwest, bridge arrival, garden exterior, or exterior blueprint.

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

All approved, candidate, rejected, superseded, or missing reference images must be tracked in /chatGPT/referenceVault/Codex_v3.1_Image_Reference_Index.md.

A reference image is active only when it is listed in the Image Reference Index, its status is approved canonical, its GitHub path is exact, and it is successfully fetched or otherwise available in the active tool context when needed for rendering.

---

# GitHub Image Retrieval Rule

When a render request needs reference images, the assistant must read the Image Reference Index, identify approved reference assets, fetch listed image files from GitHub by exact repository path when tool support permits image retrieval, and use only verified fetched images as visual reference inputs.

A GitHub path is metadata, not the image itself. For image generation, the referenced image must be available as an actual fetched, uploaded, or attached image in the current chat/tool context before it can be used as a visual reference.

---

# Reference Resolution Order

For room renders: Door Render Reference, then 360 Room Reference, then Room Blueprint Reference, then Room Render Definitions, then Room Index, then Map Core, then General Canon.

For exterior renders: approved exterior reference for requested station or nearest view, then exterior blueprint, then Exterior Index, then Map Core exterior alignment, then Render Core exterior audit rules, then General Canon.

Topology and canon always override image references if conflict occurs.

---

# 360 Room Reference Workflow

When the user requests a 360 room reference, identify the requested room, compile topology and visual identity, override standard render format to 2:1 equirectangular panorama, override the forward-hemisphere rule, preserve fixed compass orientation, include all canonical doors on correct compass walls, normalize the image so the center is North, include required room features, exclude non-canonical connections, print the compiled prompt, and ask for approval before generation.

---

# Exterior Reference Workflow

When the user requests an exterior reference, use Exterior Index as the controlling source. Select the station or exterior view. Preserve exterior structural rules, southwest bridge and landing platform rules, Garden west of Entry Hall exterior mass, and unified no-hallway structure rules. For 360 exterior references, normalize the image so center is North.

---

# Door Render Workflow

When the user requests a door render or when an open doorway is visible in a room render, identify the source room, source door, destination room, destination door, and canonical compass wall. Compile the destination-room view as seen through the source room's open doorway. Preserve immediate doorway continuity and do not invent an intermediate corridor unless one is canonically defined.

---

# Promotion Rule

Generated images are not canonical merely because they were generated.

To promote an image to approved canonical reference status, it must be audited against the active Codex, approved by the user, saved in the correct GitHub reference image path, and recorded in the Image Reference Index.

A 360 panorama cannot be promoted unless it passes the 360 Panorama Compass Normalization Rule.

---

# Conflict Handling

If a reference image contradicts canonical topology, exterior structure, room canon, or 360 compass normalization, the image is non-canonical or partially non-canonical.

Textual Codex topology, exterior rules, and compass normalization rules win over visual reference images.

End of Codex v3.1 — Render Continuity Rules.
