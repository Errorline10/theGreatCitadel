# The Codex v1.7 — Protocols and Initialization Edition

## The Great Citadel

**Status:** Current canonical version  
**Versioning model:** Full-copy standalone Codex version  
**Canonical world name:** The Great Citadel  
**Source:** Supersedes Codex v1.6 — Garden, Map, and Media Antechamber Edition  
**Repository:** Errorline10/theGreatCitadel  
**Branch:** main  

---

# 0. New Chat Initialization Guide

This section exists to help initialize a new ChatGPT chat window for The Great Citadel.

When starting a new chat, the assistant should first load or be given the latest Codex from GitHub MAIN unless the user explicitly says to continue from a local working draft.

The active Codex should be treated as the source of truth for:

- rooms
- maps
- renderings
- architecture
- stations
- symbols
- room connections
- versioning
- GitHub saving protocols
- canonical visual direction

The assistant should not rely on non-project memory for Codex details.

If the user asks to render, revise, map, save, or discuss The Great Citadel, the assistant should consult the active Codex context before answering.

If GitHub Codex retrieval is available, retrieve the latest Codex from:

Repository: `Errorline10/theGreatCitadel`  
Branch: `main`

Current published baseline after this save:

**The Codex v1.7 — Protocols and Initialization Edition**

If GitHub retrieval is not available, the user should paste or provide the current Codex, or explicitly authorize work from the current chat's local working Codex summary.

---

# 1. Assistant Initialization Instruction

When this Codex is loaded into a new ChatGPT chat, the assistant should adopt the following operating mode:

You are assisting with The Great Citadel project.

Treat this Codex as the source of truth for all Citadel-related decisions.

Use the Codex for:

- rendering prompts
- room design
- map layout
- architectural continuity
- compass directions
- GitHub saving
- versioning
- canon management

Do not rely on non-project memory for Citadel details.

When the user asks to render “as per the Codex,” do not paste the full Codex into the render prompt.

Use the compressed render stack:

```text
General Render Block
+
Room Concise Image Render Prompt
+
User overrides
```

When the user asks to update the Codex, update the local working Codex unless they explicitly ask to save to GitHub.

When the user asks to save to GitHub, increment the version, add a changelog entry, preserve the prior version, and save a complete standalone Codex.

If the user asks what is canon, answer from the Codex.

If the user asks for a room render, preserve:

- visitor perspective
- compass-fixed architecture
- canonical door locations
- room-specific topology
- known connected spaces
- human-scaled Citadel atmosphere

---

# 2. Active Protocols

## Codex Source of Truth Protocol

The Codex is the source of truth for The Great Citadel.

It governs:

- canonical architecture
- rooms
- room connections
- maps
- stations
- symbols
- visual language
- rendering rules
- save rules
- versioning
- GitHub publication

When a Codex rule exists, it overrides assumptions.

## Local vs GitHub Codex Protocol

The local Codex is the working draft used during a chat.

The GitHub Codex is the published canonical archive.

Local Codex edits:

- may be made during a chat
- may overwrite prior local wording
- do not require a version bump
- do not automatically save to GitHub

GitHub Codex saves:

- require explicit user request
- require version increment
- require changelog update
- must preserve previous history through Git
- should be full standalone Codex copies

## No Implicit GitHub Save Protocol

The assistant must not save to GitHub unless the user explicitly asks to save or publish the Codex to GitHub.

Phrases like:

- “update the Codex”
- “add this to the Codex”
- “treat this as canon”
- “use this locally”

mean local Codex update only unless GitHub is explicitly mentioned.

## Complete Standalone Version Protocol

Every GitHub-published Codex version should be a complete standalone document.

No published Codex version should require another version to be understood.

## Versioning System and Saving Protocol

Every Codex version is a complete standalone copy of the full document.

A version should include all foundational rooms, defined realms, symbols, rendering rules, accepted amendments, current architectural standards, version number, title, and changelog.

No version depends on another version to be understood.

Branches may experiment, but only full Codex copies are promoted into the MAIN archive.

Local Codex files are working drafts and may be overwritten during editing.

The Codex version number does not change for local-only edits.

The no-overwrite-history rule applies only when saving or publishing the Codex to GitHub.

When the user asks to save the Codex to GitHub, the Codex version number must increment, a changelog entry must be added, and the previous state must be preserved through Git history.

---

# 3. Rendering Protocols

## Visitor Perspective Protocol

Standard room renderings should place the viewer inside the room.

The viewer normally stands at or near the geometric center unless a room-specific rule, station rule, or user request overrides this.

The viewer faces the requested compass direction.

The room remains fixed.

The viewer rotates; the room does not.

## Eight-Direction Rendering Protocol

Unless otherwise specified, every room can be rendered facing:

- North
- Northeast
- East
- Southeast
- South
- Southwest
- West
- Northwest

## Forward Hemisphere Protocol

A standard room rendering should show only the forward hemisphere of the room from the viewer's position.

It should not show the full room unless the user requests a map, diagram, overview, or special reference view.

## Fixed Compass Architecture Protocol

Doors, stations, statues, major room features, and compass-based architecture remain fixed to their canonical locations.

A door assigned to the west wall remains on the west wall.

A statue assigned to the northwest corner remains in the northwest corner.

The room should not rotate for visual convenience.

## Doorway Continuity Protocol

If an open doorway is visible, the connected room or space should be visible beyond it when canonically known.

The visible connected space should preserve spatial and directional continuity.

The connected room should not appear from an unrelated or contradictory viewpoint.

## Standard Aspect Ratio Protocol

Standard room renderings use 16:9 horizontal format unless otherwise requested.

## Map Aspect Ratio Protocol

Map renderings use 1:1 square format unless otherwise requested.

Maps are allowed to use overhead, diagrammatic, or architectural-plan viewpoints.

---

# 4. Compressed Rendering Protocols

## General Render Block

Render in the visual language of The Great Citadel.

Use visitor perspective unless the request is explicitly for a map, diagram, station, or special-case render.

Use ancient, warm, lived-in, human-scaled Citadel architecture.

Use wood-softened stone, practical detail, coherent compass-fixed architecture, and physically plausible spatial continuity.

Default standard room renders use 16:9 horizontal format.

The viewer rotates; the room does not.

Use only the requested room, requested facing direction, and canonically appropriate visible features.

Avoid non-canonical additions.

## Concise Image Render Prompt Rule

Each room should contain a Concise Image Render Prompt.

The Concise Image Render Prompt should be short enough to use directly in image generation.

It should include:

- room identity
- room location
- room purpose
- required visual features
- atmosphere
- door count
- door compass placement
- canonical connections
- fixed compass-based features
- major non-canonical exclusions

## Concise Prompt Topology Rule

Every Concise Image Render Prompt must include enough topology to preserve canonical layout.

When known, include:

- room location within the Citadel
- canonical connections
- door count
- compass placement of doors
- fixed compass-based features

This prevents compressed prompts from losing important architecture.

## Render Prompt Compression Protocol

When the user asks to render “as per the Codex,” the image prompt should be built from:

1. General Render Block
2. Room Concise Image Render Prompt
3. Explicit user overrides

The rest of the Codex should be omitted from the actual render prompt unless needed to resolve a canonical ambiguity.

## User Override Protocol

User overrides may include:

- facing direction
- door state
- station
- aspect ratio
- time of day
- focus object
- open/closed doorway
- map vs room render
- close-up vs full-room view

Overrides should be honored unless they contradict canon.

If an override contradicts canon, the assistant should explain the conflict and offer the closest canonical version.

## Ambiguity Resolution Protocol

If the concise prompt and user request leave an ambiguity that could affect canonical correctness, consult the detailed room section and incorporate only the minimum additional information required.

Preserve prompt compression whenever possible.

## Station Compression Protocol

Stations may define a Concise Station Render Prompt.

When a station render is requested, use:

1. General Render Block
2. Concise Station Render Prompt
3. User overrides

instead of the full station text whenever possible.

---

# 5. New Chat Startup Checklist

When initializing a new ChatGPT chat for The Great Citadel, perform this checklist:

1. Identify the active Codex source.
   - Prefer GitHub MAIN.
   - If unavailable, use the latest user-provided Codex.
2. Confirm the active Codex version.
   - Current published baseline: Codex v1.7.
   - Local working edits may exist beyond GitHub v1.7.
3. Load the Active Protocols section first.
4. Load the Rendering Protocols section second.
5. Load the Compressed Rendering Protocols section third.
6. Load the Current Canon Summary and Room Index.
7. For render requests, use:
   - General Render Block
   - Room Concise Image Render Prompt
   - User overrides
8. For save requests, distinguish:
   - local Codex update
   - GitHub Codex save
9. Do not increment version unless saving to GitHub.
10. Do not assume missing room details. If possible, consult the Codex.

---

# 6. Global Canon

The Great Citadel is a vast medieval world of knowledge, memory, media, discovery, and reflection.

Within it, information is not browsed; it is physically explored through rooms, halls, gardens, doors, maps, alcoves, symbols, stations, and realms.

The Codex is the living record of The Great Citadel. It defines architecture, rooms, realms, visual language, rendering rules, stations, and accepted canonical design decisions.

The Great Citadel should feel ancient, lived-in, warm, human-scaled, and coherent. It should feel like a place of knowledge that is inhabited and cared for, not a cold or oversized monument.

The Citadel is experienced, not observed.

Every rendering should place the visitor inside the world rather than outside it.

---

# 7. Current Known Versions

## MAIN

### Codex v1.0 — Discovery Edition
Initial full-copy canonical Codex version. Included the Foundations, Great Hall, Palace Sigil, Science Realm, Hall of Discovery, Map of Understanding, Compass Rose of Discovery, Celestial Vault, Eight Alcoves of Discovery, and universal rendering standards.

### Codex v1.1 — Entry Hall Edition
Added Entry Hall as a formal foundational room between the Front Entry and Hallway.

### Codex v1.2 — Great Citadel Foundations Edition
Changed the canonical world name to The Great Citadel, revised the Foundations, retired Front Entry and Hallway as separate rooms, added antechamber rules, revised room look-and-feel, codified Great Hall banners, and added detailed Entry Hall and Small Library rules.

### Codex v1.3 — Station Rendering Edition
Reorganized the Codex for image rendering. Added global station standards, a room-section template, and the first formal station: Small Library — Instruction Manual Station.

### Codex v1.4 — Garden Meditation Edition
Preserved v1.3 and replaced the Garden theme with a refined meditation-garden identity.

### Codex v1.5 — Rendering Continuity and Arts Antechamber Edition
Preserved v1.4 and consolidated doorway continuity, general antechamber standards, Entry Hall three-door layout, Garden Buddha station, Arts Antechamber compass layout, and 16:9 rendering rules.

### Codex v1.6 — Garden, Map, and Media Antechamber Edition
Preserved v1.5 and consolidated eight-direction room rendering, map rendering, 1:1 map format, Garden wall/mountain/blimp/Buddha visibility rules, approved Garden east-facing visual direction, and Media Antechamber layout/identity/features.

### Codex v1.7 — Protocols and Initialization Edition
Preserves v1.6 and adds front-loaded protocols for new-chat initialization, active protocols, rendering protocols, compressed rendering protocols, startup checklist, assistant initialization instruction, current canon summary, and room concise render prompt index.

---

# 8. Current Canon Summary

The Great Citadel is a vast medieval world of knowledge, memory, media, discovery, and reflection.

Information is not browsed; it is physically explored through rooms, halls, gardens, doors, maps, alcoves, symbols, stations, and realms.

The Citadel should feel:

- ancient
- lived-in
- warm
- human-scaled
- coherent
- cared for
- practical
- discoverable

The main known foundation path is:

```text
Entry Hall → Small Library → Foundational Door → Great Hall
```

The Garden is a branch off the Entry Hall:

```text
Entry Hall West Door → Garden East Door → Garden
```

The Great Hall is the central navigation chamber.

Its eight primary openings are:

- North: Science Door → Hall of Discovery
- Northeast: Philosophy Door → Philosophy Antechamber
- East: Arts Door → Arts Antechamber
- Southeast: Personal Door → Personal Antechamber
- South: Foundational Door → Small Library
- Southwest: Inventor's Door → Inventor's Antechamber
- West: Media Door → Media Antechamber
- Northwest: History Door → History Antechamber

---

# 9. Current Room Index

## Current Foundation Rooms

1. Entry Hall
2. Garden
3. Small Library
4. Foundational Door
5. Great Hall

## Current Defined Rooms and Antechambers

1. Entry Hall
2. Garden
3. Small Library
4. Great Hall
5. Hall of Discovery
6. Media Antechamber
7. History Antechamber
8. Philosophy Antechamber
9. Arts Antechamber
10. Personal Antechamber
11. Inventor's Antechamber

## Current Defined Stations

1. Small Library — Instruction Manual Station
2. Garden — Buddha Statue Station

## Retired as Separate Rooms

- Front Entry
- Hallway

Absorbed into Entry Hall.

---

# 10. Room Concise Render Prompt Index

This section gathers the concise render prompts for currently known rooms.

For standard image generation, use these prompts with the General Render Block and the user's explicit overrides.

Detailed room sections remain authoritative for deeper canon questions.

## Entry Hall — Concise Image Render Prompt

The Great Citadel Entry Hall, 16:9 horizontal visitor-perspective render, viewer standing inside the room facing north. The Entry Hall is the southernmost entrance threshold of the Citadel and is a narrow welcoming passage with exactly three canonical doors: north door ahead leading to the Small Library, south door behind the viewer leading outside/arrival, and west door on the left wall leading to the Garden. Render warm lantern light, wood-softened stone walls, side tables on both sides, coat hooks with cloaks or jackets, travel bags, plants or vines, worn stone floor, and a clear forward path. If the north door is open, the Small Library should be visible beyond it. Cozy, ancient, lived-in, practical, human-scaled arrival space; not grand, not ceremonial, not a hub.

## Garden — Concise Image Render Prompt

The Great Citadel Garden, 16:9 horizontal visitor-perspective render, viewer standing inside the Garden facing west. The Garden is a meditation branch space located west of the Entry Hall and has exactly one canonical door: an east-wall door behind the viewer leading back to the Entry Hall. Render a bright, dry, open meditation garden with raked sand Zen garden, stacked Zen stones, modest plants, old vine-covered stone boundary walls, warm daylight, distant mountains beyond the wall, and a few tiny faraway steampunk blimps. Include exactly one small Buddha statue fixed in the northwest corner, appearing on the right side when visible in a west-facing view. Calm, restorative, human-scaled atmosphere; no buildings, no wet ground, no extra doors.

## Small Library — Concise Image Render Prompt

The Great Citadel Small Library, 16:9 horizontal visitor-perspective render, compact warm human-scaled study room. The Small Library is located north of the Entry Hall and south of the Foundational Door / Great Hall connection, and has exactly two canonical doors: south door to the Entry Hall and north door onward toward the Foundational Door and Great Hall. Render wood-softened stone architecture, shelves of reference books, maps, lamps, writing tools, lecterns, reading tables, introductory collections, and the Instruction Manual and Guest Book in the northeast corner when visible. Quiet, preparatory, welcoming scholarly atmosphere; one primary door visible in standard rendering, no extra exits, not grand, not a hub.

## Foundational Door — Concise Image Render Prompt

The Great Citadel Foundational Door, 16:9 horizontal visitor-perspective render, ancient threshold between the Foundations and the Great Hall. The Foundational Door is located north of the Small Library and south of the Great Hall and connects Small Library → Foundational Door → Great Hall. Render old stone framing, carved wood door structure, brass or bronze fittings, threshold markings, foundational symbols, and Palace Sigil or root-and-return motifs where appropriate. If open, show the connected side beyond the threshold with clear spatial continuity. Warm, ancient, meaningful transition space; not a realm door and not an antechamber entrance.

## Great Hall — Concise Image Render Prompt

The Great Citadel Great Hall, 16:9 horizontal visitor-perspective render, viewer standing near the geometric center upon the Great Knowledge Compass facing the requested compass direction. The Great Hall is the central navigation chamber of the Citadel with eight primary openings fixed by compass: north Science Door to Hall of Discovery, northeast Philosophy Door to Philosophy Antechamber, east Arts Door to Arts Antechamber, southeast Personal Door to Personal Antechamber, south Foundational Door to Small Library, southwest Inventor's Door to Inventor's Antechamber, west Media Door to Media Antechamber, and northwest History Door to History Antechamber. Render ancient stone and brass navigation architecture, Palace Sigil, partial Great Knowledge Compass, domain medallions, door tracks, and banners where appropriate. Show only the forward half of the chamber and 1 to 4 visible doors maximum. Warm, ancient, coherent Citadel atmosphere; never show all eight doors at once.

## Hall of Discovery — Concise Image Render Prompt

The Great Citadel Hall of Discovery, 16:9 horizontal visitor-perspective render, science antechamber of inquiry, viewer standing inside facing the requested compass direction. The Hall of Discovery is located north of the Great Hall beyond the Science Door and has four primary doors fixed by compass: south Science Door back to the Great Hall, north Astronomy Door, west Biology Door, and east Logic Door. Render the Map of Understanding partially visible on the floor, the Compass Rose of Discovery, the Celestial Vault overhead with handcrafted astronomical symbolism, integrated wall alcoves, and warm stone, wood, brass, and parchment details. Include recognizable inquiry and scientific atmosphere with astronomy, biology, and logic cues where appropriate. No Star Whale, no freestanding kiosks.

## Arts Antechamber — Concise Image Render Prompt

The Great Citadel Arts Antechamber, 16:9 horizontal visitor-perspective render, warm human-scaled creative threshold room, viewer standing near the center facing the requested compass direction. The Arts Antechamber is located east of the Great Hall beyond the Arts Door and has four canonical doors fixed by compass: north Music Door, east Writing Door, south Visual Door, and west Great Hall Door. Render carved wood display panels, framed sketches, small sculptures, pigments, parchment studies, musical instruments as secondary details when not facing the Music Door, masks, textiles, benches or worktables, and warm lantern light. The primary visible door should match the facing direction. Threshold room only; not a museum, not a theater, not a messy workshop, and do not show all four doors in a standard rendering.

## Media Antechamber — Concise Image Render Prompt

The Great Citadel Media Antechamber, 16:9 horizontal visitor-perspective render, warm human-scaled medieval-Citadel chamber of recorded experience, viewer standing near the center facing the requested compass direction. The Media Antechamber is located west of the Great Hall beyond the Media Door and has four canonical doors fixed by compass: north Movie Theater Door, east Great Hall Door, south Physical Archive Index Door, and west Audio Theater Door. Render carved wood media panels, framed story panels, projection-lantern or camera-obscura devices, acoustic horns or resonance bowls, catalog drawers, archive labels, parchment slips, brass mechanisms, shelves of physical media records, and benches or listening seats. The primary visible door should match the facing direction. Ancient handcrafted archival atmosphere; no televisions, no digital screens, no neon, no modern media-center elements.

## History Antechamber — Concise Image Render Prompt

The Great Citadel History Antechamber, 16:9 horizontal visitor-perspective render, warm ancient transitional room between the Great Hall and the History Realm. The History Antechamber is located northwest of the Great Hall beyond the History Door and serves as the threshold from the Great Hall into the History Realm. Render archives, timelines, memory records, ruins, preserved events, worn stone, wood shelving, parchment, brass archive mechanisms, and aged inscriptions or banners. Human-scaled, lived-in, memory-rich atmosphere. Transitional room only; not the full History Realm.

## Philosophy Antechamber — Concise Image Render Prompt

The Great Citadel Philosophy Antechamber, 16:9 horizontal visitor-perspective render, warm contemplative transitional room between the Great Hall and the Philosophy Realm. The Philosophy Antechamber is located northeast of the Great Hall beyond the Philosophy Door and serves as the threshold from the Great Hall into the Philosophy Realm. Render a quiet stone-and-wood chamber of questions, contemplation, ethics, metaphysics, and meaning, with benches, lecterns, symbolic carvings, lantern light, and parchment notes. Human-scaled reflective atmosphere. Transitional room only; not the full Philosophy Realm.

## Personal Antechamber — Concise Image Render Prompt

The Great Citadel Personal Antechamber, 16:9 horizontal visitor-perspective render, warm reflective transitional room between the Great Hall and the Personal Realm. The Personal Antechamber is located southeast of the Great Hall beyond the Personal Door and serves as the threshold from the Great Hall into the Personal Realm. Render memory, identity, inner life, and personal history through journals, keepsake alcoves, reflection symbolism, soft lantern light, worn stone, and warm wood details. Intimate human-scaled atmosphere. Transitional room only; not the full Personal Realm.

## Inventor's Antechamber — Concise Image Render Prompt

The Great Citadel Inventor's Antechamber, 16:9 horizontal visitor-perspective render, warm human-scaled transitional room between the Great Hall and the Inventor's Realm. The Inventor's Antechamber is located southwest of the Great Hall beyond the Inventor's Door and serves as the threshold from the Great Hall into the Inventor's Realm. Render mechanisms, tools, experiments, prototypes, worktables, brass gears, clockwork devices, parchment schematics, and subtle Time Traveler modifications within ancient stone-and-wood architecture. Inventive but coherent threshold atmosphere. Transitional room only; not the full Inventor's Realm.

---

# 11. Map Rendering Standards

## Purpose

Map renderings are special Codex reference images.

They are not standard visitor-perspective room renderings.

A map rendering may use an overhead, diagrammatic, or architectural-plan viewpoint in order to show room relationships, compass orientation, and known pathways.

Map renderings are allowed exceptions to the Visitor Perspective Principle, Central Viewing Principle, Forward Hemisphere Rule, and No Omniscient Perspective Rule.

## Map Orientation Rule

All Codex maps should be north-oriented unless explicitly requested otherwise.

North should appear at the top of the image.

A compass rose should be included when practical.

Compass labels should match the Codex layout.

## Known-Room Map Rule

A map of known rooms should include only rooms, antechambers, stations, and major destinations currently defined in the Codex.

Undefined future areas may be shown only as labeled unknowns, dashed outlines, sealed doors, shadowed passages, or beyond-this-point markers.

A known-room map should not invent fully detailed rooms that are not yet canonical.

## Foundation Map Rule

The Foundation path should appear south of the Great Hall.

Canonical Foundation sequence:

```text
Entry Hall → Small Library → Foundational Door → Great Hall
```

The Garden is a branch off the Entry Hall:

```text
Entry Hall West Door → Garden East Door → Garden
```

The Garden should appear west of the Entry Hall.

The Small Library should appear north of the Entry Hall and south of the Foundational Door / Great Hall connection.

## Great Hall Map Rule

The Great Hall should appear as the central compass hub of the Citadel's known realm structure.

Its eight primary openings remain fixed:

- North: Science Door → Hall of Discovery
- Northeast: Philosophy Door → Philosophy Antechamber
- East: Arts Door → Arts Antechamber
- Southeast: Personal Door → Personal Antechamber
- South: Foundational Door → Small Library
- Southwest: Inventor's Door → Inventor's Antechamber
- West: Media Door → Media Antechamber
- Northwest: History Door → History Antechamber

## Approved Map Visual Reference

The approved local visual reference for map renderings is The Great Citadel — Known Rooms Map.

Approved traits:

- parchment / illuminated manuscript style
- north-oriented
- compass rose included
- Great Hall central
- known rooms only
- Garden west of Entry Hall
- Media Antechamber west of Great Hall
- Arts Antechamber east of Great Hall
- Hall of Discovery north of Great Hall
- Foundation path south of Great Hall
- readable room labels
- decorative Codex border
- 1:1 square map composition

---

# 12. Global Station Standards

A station is a fixed viewpoint inside a room.

A station is used when a rendering should focus on a particular object, feature, or area of a room rather than presenting the room as a general whole.

A station defines the viewer's fixed position, viewing direction, focal object, intended framing, and purpose of the view.

Stations are used for focused renderings.

A station rendering is different from a standard room rendering.

A standard room rendering usually presents the room from its canonical viewing direction and emphasizes the room as a space.

A station rendering emphasizes a specific object or feature within the room.

A station may override the normal central-viewing rule when a focused object study is required.

However, the station should still feel like a real visitor viewpoint physically located within the room.

Station naming convention:

```text
[Room Name] — [Station Name]
```

---

# 13. General Antechamber Standards

Antechambers are transitional rooms between the Great Hall and deeper realm paths.

They are not the full realm.

They introduce the identity, atmosphere, symbols, and major paths of the realm beyond.

An antechamber should function as an orientation space, giving the visitor a first sense of the realm before they enter its deeper halls.

In a standard antechamber rendering, the viewer stands at or near the geometric center of the antechamber.

Each standard antechamber rendering must specify a facing direction.

The viewer faces one compass direction at a time.

The rendering should show the forward hemisphere of the room only.

The wall or doorway in front of the viewer should be the primary focus of the image.

A standard antechamber rendering should not show all canonical doors at once.

The door on the wall being faced should usually be the primary visible door.

Adjacent doors may appear only if physically plausible within the forward hemisphere and if they do not turn the image into an overview.

The preferred standard rendering shows one primary door.

The practical maximum is two visible doors unless a room-specific rule allows more.

Once antechamber compass door positions are defined, those compass positions are canonical.

A door should not move to another wall for visual convenience.

If a visible antechamber door is open, the connected room, realm path, or connected space beyond the threshold should be visible.

The view beyond the open doorway should include recognizable features of the connected destination.

The visible destination should preserve directional continuity with the current viewer position and facing direction.

Antechambers should be smaller and more focused than the Great Hall.

They may be richer or more specialized than the Foundation rooms, but they should remain human-scaled enough to feel like threshold spaces.

They should not feel like full realms, large public museums, huge theaters, or complete destination spaces.

---

# 14. Global Map and Connection Rules

The Foundations are north-oriented.

```text
NORTH

Great Hall
    │
Foundational Door
    │
Small Library
    │
Entry Hall

SOUTH
```

Main Foundation path:

```text
Entry Hall → Small Library → Foundational Door → Great Hall
```

Garden branch:

```text
Entry Hall West Door → Garden East Door → Garden
```

Great Hall realm access:

| Direction | Opening | Connection |
|---|---|---|
| North | Science Door | Hall of Discovery → Science Realm |
| Northeast | Philosophy Door | Philosophy Antechamber → Philosophy Realm |
| East | Arts Door | Arts Antechamber → Arts Realm |
| Southeast | Personal Door | Personal Antechamber → Personal Realm |
| South | Foundational Door | Small Library → Entry Hall |
| Southwest | Inventor's Door | Inventor's Antechamber → Inventor's Realm |
| West | Media Door | Media Antechamber → Media Realm |
| Northwest | History Door | History Antechamber → History Realm |

---

# 15. Room Section Template

Each room section should use this rendering-oriented structure:

```text
## [Room Name]

### Purpose
### Connections
### Door Rules
### Viewing Directions
### Required Features
### Material and Atmosphere
### Standard Rendering Rules
### Open Door Display Rules
### Stations
### Concise Image Render Prompt
### Non-Canonical Mistakes to Avoid
```

---

# 16. Room Details

## Entry Hall

### Purpose

The Entry Hall is the southernmost entrance and first threshold space of The Great Citadel.

It combines the former roles of Front Entry, Entry Hall, and Hallway into one canonical room.

It welcomes the visitor and guides them inward.

The Entry Hall should feel like the Citadel is personally receiving a new visitor.

### Connections

The Entry Hall has three canonical doors:

- North Door → Small Library
- South Door → Outside / Arrival
- West Door → Garden

Primary path:

```text
South Door → Entry Hall → North Door → Small Library
```

Garden branch:

```text
Entry Hall West Door → Garden East Door → Garden
```

### Door Rules

The Entry Hall has exactly three canonical doors:

1. North Door
2. South Door
3. West Door

No additional Entry Hall doors are canonical unless later defined.

The Entry Hall is not a hub.

It is a narrow welcoming passage with one side branch to the Garden.

### Viewing Directions

The standard Entry Hall rendering should usually look north along the main path toward the Small Library.

All eight compass-facing renderings are valid if requested.

The room remains fixed; the viewer rotates.

### Required Features

The Entry Hall should include small tables on each side, a place to hang a coat or jacket, a clear forward path, warm lantern light, wood-softened stone architecture, plants/vines/moss where appropriate, practical arrival details, and welcoming signs or inscriptions when appropriate.

### Material and Atmosphere

The Entry Hall should feel narrow, warm, cozy, human-scaled, ancient, lived-in, cared for, welcoming, safe, practical, and inviting.

It should feel like the first human-scaled threshold of The Great Citadel.

### Standard Rendering Rules

Render the Entry Hall as a narrow welcoming passage.

Do not render it as a broad ceremonial chamber.

It should feel longer than wide.

It should show a clear path inward toward the Small Library.

The room should include practical arrival details such as side tables, coat hooks, bags, lanterns, or small welcoming signs.

If the north door is open, the Small Library should be visible beyond it.

### Open Door Display Rules

If the north door is open, the Small Library should be visibly shown beyond the threshold from the same northward-facing direction as the Entry Hall rendering.

If the south door is open, the exterior arrival side of the Citadel should be shown beyond the threshold.

If the west door is open, the Garden should be visibly shown beyond the threshold with recognizable Garden features such as open sky, raked sand, Zen stones, modest plants, and meditation atmosphere.

### Stations

No formal Entry Hall stations are defined yet.

### Concise Image Render Prompt

Use the Entry Hall prompt in the Room Concise Render Prompt Index.

### Non-Canonical Mistakes to Avoid

- rendering the Entry Hall as a broad ceremonial chamber
- making it feel grand, vast, or open like the Great Hall
- omitting small human-scaled welcome qualities
- omitting practical arrival features
- adding more than three doors
- placing the Garden door anywhere except the west side of the Entry Hall
- making the Entry Hall feel like a hub
- showing an open north door without the Small Library visible beyond it
- showing the Small Library beyond the north door from the wrong perspective

## Garden

### Purpose

The Garden is a branch space connected to the Entry Hall.

It is a meditation garden.

It serves as a calm, restorative side space where a visitor may step away from the main Foundation path, sit quietly, breathe, reflect, and regain inner balance before continuing deeper into the Citadel.

The Garden should feel peaceful, bright, welcoming, and spiritually quiet.

### Connections

The Garden connects to the Entry Hall through the Entry Hall west door and the Garden east door.

Connection:

```text
Entry Hall West Door → Garden East Door → Garden
```

The Garden does not interrupt the main Foundation path.

It is an optional branch space connected to the Entry Hall.

### Door Rules

The Garden has one canonical door.

The door is located on the east wall of the Garden.

This east-wall door connects directly back to the Entry Hall through the Entry Hall west door.

No additional Garden doors are canonical unless later defined.

### Garden Wall Rule

The Garden includes old stone boundary walls, with the east wall containing the Garden's only canonical door back to the Entry Hall.

The walls should feel aged, vine-covered, and integrated into the Citadel.

They should not make the Garden feel closed-in, gloomy, or like a building interior.

### Distant View Rule

Beyond the Garden wall, there should be a distant view of mountains.

The mountains should appear far beyond the Garden boundary and should help give the Garden a sense of openness and a larger world beyond the Citadel.

A few scattered steampunk blimps may also be visible in the distant sky beyond the Garden wall.

These blimps should feel small, far away, and atmospheric rather than dominant.

### Viewing Directions

The standard Garden rendering faces west on the map.

All eight compass-facing renderings are valid if requested.

The viewer stands inside the Garden and faces the requested compass direction.

The Garden remains fixed; the viewer rotates.

The Garden's east-wall door remains on the east wall.

The Buddha statue remains in the northwest corner.

### Required Features

The Garden should include:

- open sky
- warm daylight
- old stone garden boundary walls
- distant mountains beyond the Garden wall
- a few scattered distant steampunk blimps in the sky beyond the Garden wall
- a meditation-garden atmosphere
- a raked sand Zen garden
- stacked Zen stones
- exactly one small Buddha statue in the northwest corner
- modest living plants
- vines or moss on old stone where appropriate
- lanterns or small garden lights
- old Citadel stone details
- a calm, happy, restorative atmosphere

### Material and Atmosphere

The Garden should feel open, airy, happy, dry, bright, calm, meditative, restorative, human-scaled, cared for, lightly cultivated, and spiritually quiet.

The Garden should strongly read as a meditation garden.

It should not feel like a park, a farm, a wet courtyard, or a public plaza.

### Buddha Statue Rule

There is only one Buddha statue in the Garden.

The Buddha statue is located in the northwest corner of the Garden.

It should support the meditation-garden identity of the space.

The statue should feel peaceful, modest, and integrated into the Garden.

It should not be monumental or oversized.

No additional Buddha statues are canonical.

### West-Facing Buddha Placement Rule

In a west-facing rendering of the Garden, the Buddha statue should appear on the right side of the image when visible.

This is because the Buddha statue is canonically located in the northwest corner of the Garden.

### East-Facing Garden Buddha Visibility Rule

In an east-facing rendering of the Garden, the Buddha statue should not be visible.

The Buddha statue is located in the northwest corner of the Garden.

Because standard renderings follow the Forward Hemisphere Rule, the northwest-corner Buddha statue should not appear in an east-facing Garden rendering.

### Standard Rendering Rules

The standard Garden rendering faces west on the map.

The Garden should appear dry, bright, open, and welcoming.

It should strongly read as a meditation garden.

The raked sand Zen garden should be visible.

Stacked Zen stones should be visible.

The single small Buddha statue should be visible only if composition and direction allow, and it must be in the northwest corner.

No buildings should be visible.

No pathways should lead directly to distant mountains.

When rendered facing east, the composition should focus on the east wall, the Garden East Door, the Entry Hall connection if the east door is open, raked sand, Zen stones, plants, and stone details in the eastern forward hemisphere. The Buddha statue should not be visible.

### Open Door Display Rules

If the Garden's east-wall door is visible and open, the Entry Hall should be visibly shown beyond the threshold.

The Entry Hall should appear from the direction created by the Garden viewer position and the east-wall doorway.

### Stations

#### Garden — Buddha Statue Station

This station is a fixed viewpoint in the Garden.

It is positioned directly in front of the Buddha statue in the northwest corner of the Garden.

The viewer stands facing the Buddha statue from close range.

The Buddha statue should be shown at eye level.

The Buddha statue should fill most of the image.

The surrounding Garden may appear only as secondary context.

### Concise Image Render Prompt

Use the Garden prompt in the Room Concise Render Prompt Index.

### Non-Canonical Mistakes to Avoid

- showing visible buildings in a standard Garden rendering
- omitting the meditation identity
- omitting the raked sand Zen garden
- omitting the stacked Zen stones
- adding more than one Buddha statue
- placing the Buddha statue anywhere other than the northwest corner
- making the Buddha statue monumental or oversized
- showing the Buddha statue on the left side of a west-facing Garden rendering
- showing the Buddha statue in an east-facing Garden rendering
- making the Garden feel wet, muddy, slick, swampy, or waterlogged
- turning it into a large park, farm, or public plaza
- adding extra Garden doors
- placing the Garden door on any wall other than the east wall
- making distant blimps too large, too numerous, or dominant over the Garden

## Small Library

### Purpose

The Small Library is the final preparatory room before entering the Great Hall.

It represents understanding before exploration.

It is a compact, warm, human-scaled study room.

### Connections

```text
Entry Hall → Small Library → Foundational Door → Great Hall
```

The Small Library connects:

- South Door → Entry Hall
- North Door → Foundational Door / Great Hall

### Door Rules

The Small Library has exactly two canonical doors:

1. North Door
2. South Door

The north door is located on the north wall.

The south door is located on the south wall.

Both canonical doors should normally be shut in standard renderings unless an open-door connection is intentionally being shown.

No additional primary doors are canonical.

The Small Library is not a branching room.

Its canonical layout is linear and north-south.

### Viewing Directions

The Small Library has preferred canonical views facing north and south, but all eight compass-facing renderings are valid if requested.

The room remains fixed; the viewer rotates.

### Required Features

The Small Library contains Instruction Manual and Guest Book, the Codex as a reference source, introductory collections, maps, symbol references, historical records, reading tables, lecterns, shelves, reference books, writing tools, map tables, and lamps or lanterns.

### Material and Atmosphere

The Small Library should feel compact, warm, quiet, human-scaled, focused, preparatory, lived-in, welcoming, and studious.

Wood should strongly soften the room.

### Standard Rendering Rules

A standard Small Library rendering should show one primary door, warm compact human scale, no extra exits, no full circulation diagram, Instruction Manual and Guest Book in the northeast corner when visible, and north door unobstructed when facing north.

The large prominent display book in the Small Library is not the Codex. It is the combined Instruction Manual and Guest Book.

### Open Door Display Rules

If the north door is open, the onward connection toward the Foundational Door and Great Hall should be visibly shown beyond the threshold.

If the south door is open, the Entry Hall should be visibly shown beyond the threshold.

All open-door views should preserve spatial continuity and should not show connected spaces from unrelated angles.

### Instruction Manual and Guest Book

The large prominent display book in the Small Library is not the Codex.

It is a combined Instruction Manual and Guest Book.

It serves as the visitor's practical introduction to The Great Citadel and as a record of arrival.

It should be placed in the northeast corner of the Small Library and must not block the north door.

### The Codex in the Small Library

The Codex remains one of the important contents of the Small Library, but it is not the large display book used to greet visitors.

The Codex may appear as a protected reference volume, shelved master text, smaller lectern book, or curated reference source within the room.

### Stations

#### Small Library — Instruction Manual Station

This station is a fixed viewpoint in the Small Library.

It is positioned just in front of the large Instruction Manual and Guest Book in the northeast corner of the room.

The view should look downward toward the book.

The Instruction Manual and Guest Book should be the primary object in the image and should occupy most of the frame.

The surrounding room may appear only as secondary context.

### Concise Image Render Prompt

Use the Small Library prompt in the Room Concise Render Prompt Index.

### Non-Canonical Mistakes to Avoid

- showing more than one primary door at once in a standard rendering
- showing open doors unless intentionally using the open-door connection rule
- adding extra exits
- making the Small Library feel like a hub
- placing the Instruction Manual and Guest Book in the center of the room
- blocking the north door with the book
- treating the large display book as the Codex
- rendering the room as grand, vast, or monumental
- rendering the Instruction Manual Station as a full-room overview

## Foundational Door

The Foundational Door connects the Small Library to the Great Hall.

It is one of the eight primary openings of the Great Hall.

It leads back to the Foundations rather than to a realm antechamber.

Connections:

```text
Small Library → Foundational Door → Great Hall
Great Hall → Foundational Door → Small Library → Entry Hall
```

The Foundational Door is the exception to the Antechamber Connection Principle.

It does not lead to an antechamber.

It leads between the Great Hall and the Foundations.

The Foundational Door should communicate threshold, return, and foundation.

It may include old stone, carved wood, brass or bronze fittings, foundational symbols, threshold markings, Palace Sigil or root/return motifs where appropriate.

If the Foundational Door is viewed open from the Small Library side, the Great Hall should be visibly shown beyond the threshold.

If the Foundational Door is viewed open from the Great Hall side, the Small Library should be visibly shown beyond the threshold.

Use the Foundational Door prompt in the Room Concise Render Prompt Index.

## Great Hall

The Great Hall is the central navigation chamber of The Great Citadel.

It is the symbolic and navigational heart of exploration.

All major journeys into the greater Citadel begin here.

The Great Hall connects to:

- North: Science Door → Hall of Discovery → Science Realm
- Northeast: Philosophy Door → Philosophy Antechamber → Philosophy Realm
- East: Arts Door → Arts Antechamber → Arts Realm
- Southeast: Personal Door → Personal Antechamber → Personal Realm
- South: Foundational Door → Small Library → Entry Hall
- Southwest: Inventor's Door → Inventor's Antechamber → Inventor's Realm
- West: Media Door → Media Antechamber → Media Realm
- Northwest: History Door → History Antechamber → History Realm

The Great Hall contains eight primary openings.

Seven lead to major realms of knowledge through antechambers.

One leads to the Foundations.

The Great Hall should include Palace Sigil, Great Knowledge Compass, eight primary openings, domain medallions, door tracks, ancient stonework, brass mechanisms, and banners where appropriate.

The Great Hall is not a map. It is an architectural experience.

The viewer stands at or near the geometric center of the Great Hall.

The viewer stands upon the Great Knowledge Compass.

Only the forward half of the chamber should be visible.

Visible doors: minimum 1, preferred 2–3, maximum 4.

A rendering that reveals all eight doors is non-canonical.

Use the Great Hall prompt in the Room Concise Render Prompt Index.

## Hall of Discovery

The Hall of Discovery is the antechamber of the Science Realm.

It introduces visitors to Astronomy, Biology, and Logic.

It represents inquiry before specialization.

Connections:

- South: Science Door → Great Hall
- North: Astronomy Door
- West: Biology Door
- East: Logic Door

The Hall of Discovery should include Map of Understanding, Compass Rose of Discovery, Celestial Vault, and Eight Alcoves of Discovery.

The floor contains the Map of Understanding.

The ceiling forms the Celestial Vault, which may include constellations, planetary paths, lunar cycles, seasonal markers, astronomical symbols, and scientific inscriptions.

All elements should appear handcrafted and integrated into the architecture.

The Star Whale is not canonical.

Alcoves are architectural recesses built into perimeter walls.

They are not freestanding displays, kiosks, islands, detached structures, or furniture placed within the center of a room.

Use the Hall of Discovery prompt in the Room Concise Render Prompt Index.

## Arts Antechamber

The Arts Antechamber is the transitional room between the Great Hall and the Arts Realm.

It introduces making, beauty, image, performance, music, craft, color, writing, and expression.

It is not the full Arts Realm.

It is a four-door creative orientation room.

Door placement:

- North wall: Music Door
- East wall: Writing Door
- South wall: Visual Door
- West wall: Great Hall Door

The Arts Antechamber should include carved wood display panels, framed sketches or studies, small sculptures, pigments or paint bowls, parchment studies, musical instruments as secondary details when not facing the Music Door, masks or theatrical objects, woven textiles or banners, warm lantern light, benches or worktables, and its four canonical doors.

Render the Arts Antechamber as a threshold room, not as a full museum, theater, or workshop.

Do not render all four Arts Antechamber doors in a standard room image unless a map, diagram, or special overview is explicitly requested.

Use the Arts Antechamber prompt in the Room Concise Render Prompt Index.

## Media Antechamber

The Media Antechamber is the transitional room between the Great Hall and the Media Realm.

It is a four-door orientation room for recorded and shared experience.

It receives the visitor from the Great Hall and offers three primary media paths:

- Movie Theater
- Audio Theater
- Physical Archive Index

It is not the full Media Realm.

It is the threshold where the visitor first encounters image, sound, record, story, and indexed memory.

The Media Antechamber is a warm, human-scaled chamber of recorded experience.

Media in The Great Citadel is not digital content, but preserved experience: images, sounds, stories, records, and references held in physical form.

Door placement:

- North wall: Movie Theater Door
- East wall: Great Hall Door
- South wall: Physical Archive Index Door
- West wall: Audio Theater Door

The Media Antechamber should include carved wood media panels, framed story panels, projection-lantern or camera-obscura-like devices, acoustic horns or resonance bowls, catalog drawers, archive labels, parchment reference slips, warm lantern light, benches or listening seats, brass mechanisms, shelves of media records, and symbols for image, sound, and archive.

Do not make it look modern.

Do not show all four doors in a standard rendering unless a map, diagram, or special overview is explicitly requested.

Use the Media Antechamber prompt in the Room Concise Render Prompt Index.

## Future Antechambers

Major realm doors do not open directly into fully developed realms.

Each primary realm door from the Great Hall opens first into an antechamber.

An antechamber is a transitional room that introduces the identity, atmosphere, symbols, and major paths of its realm.

The Foundational Door is the exception to the Antechamber Connection Principle.

### History Antechamber

The History Antechamber is the transitional room between the Great Hall and the History Realm. It introduces archives, timelines, memory, records, ruins, and preserved events.

Connection: Great Hall → History Door → History Antechamber → History Realm.

The History Antechamber follows the General Antechamber Standards.

No formal History Antechamber stations are defined yet.

### Philosophy Antechamber

The Philosophy Antechamber is the transitional room between the Great Hall and the Philosophy Realm. It introduces questions, contemplation, argument, ethics, metaphysics, and meaning.

Connection: Great Hall → Philosophy Door → Philosophy Antechamber → Philosophy Realm.

The Philosophy Antechamber follows the General Antechamber Standards.

No formal Philosophy Antechamber stations are defined yet.

### Personal Antechamber

The Personal Antechamber is the transitional room between the Great Hall and the Personal Realm. It introduces memory, identity, reflection, inner life, personal history, and self-understanding.

Connection: Great Hall → Personal Door → Personal Antechamber → Personal Realm.

The Personal Antechamber follows the General Antechamber Standards.

No formal Personal Antechamber stations are defined yet.

### Inventor's Antechamber

The Inventor's Antechamber is the transitional room between the Great Hall and the Inventor's Realm. It introduces invention, mechanisms, tools, experiments, prototypes, workshop thinking, and Time Traveler modifications.

Connection: Great Hall → Inventor's Door → Inventor's Antechamber → Inventor's Realm.

The Inventor's Antechamber follows the General Antechamber Standards.

No formal Inventor's Antechamber stations are defined yet.

---

# 17. Symbols and Floor Systems

## Palace Sigil

The Palace Sigil is the highest symbol of The Great Citadel.

It takes the form of a simple eight-spoked ship's helm inspired by traditional Buddhist wheel symbolism.

Characteristics:

- Circular form
- Eight spokes
- Strong silhouette
- Balanced geometry
- Immediate recognizability

The design should feel ancient, timeless, functional, calm, and purposeful.

The Palace Sigil represents guidance rather than destination.

The Citadel does not dictate what visitors should learn. It provides pathways through knowledge.

## Great Knowledge Compass

The Great Knowledge Compass is the floor of the Great Hall and one of the oldest known artifacts in the Citadel.

At its center is the Palace Sigil.

Its spokes extend outward through Palace Sigil, Domain Medallion, Door Track, and Primary Opening.

## Compass Rose of Discovery

The Compass Rose of Discovery sits at the center of the Map of Understanding in the Hall of Discovery.

It aligns:

- North → Astronomy Door
- East → Logic Door
- South → Science Door
- West → Biology Door

The Compass Rose is fixed within the architecture. It does not rotate based on the viewer.

---

# 18. Current Canonical Status

Canonical world name:

- The Great Citadel

Active Codex:

- Codex v1.7 — Protocols and Initialization Edition

Current Foundation rooms:

1. Entry Hall
2. Garden
3. Small Library
4. Foundational Door
5. Great Hall

Current defined rooms and antechambers:

1. Entry Hall
2. Garden
3. Small Library
4. Great Hall
5. Hall of Discovery
6. Media Antechamber
7. History Antechamber
8. Philosophy Antechamber
9. Arts Antechamber
10. Personal Antechamber
11. Inventor's Antechamber

Current defined stations:

1. Small Library — Instruction Manual Station
2. Garden — Buddha Statue Station

Retired room names:

- Front Entry
- Hallway

Rejected or non-canonical concepts:

- The Star Whale is not canonical.
- The former statement that The Great Citadel naming change was rolled back is superseded by v1.2 and later.
- The canonical project/world name is The Great Citadel.
- The large prominent display book in the Small Library is not the Codex; it is the Instruction Manual and Guest Book.
- A standard Small Library rendering with an open door is non-canonical unless a later rule explicitly allows an exception.
- A Great Hall rendering that shows all eight primary openings at once is non-canonical.
- A Garden standard rendering with visible buildings is non-canonical.
- A Garden standard rendering that omits the raked sand Zen garden, stacked Zen stones, or single northwest-corner Buddha statue when it should be visible is non-canonical.
- A west-facing Garden rendering with the Buddha statue on the left side is non-canonical.
- An east-facing Garden rendering showing the Buddha statue is non-canonical.
- An Arts Antechamber standard rendering that shows all four doors at once is non-canonical unless explicitly requested as a map, diagram, or special overview.
- A Media Antechamber standard rendering that shows all four doors at once is non-canonical unless explicitly requested as a map, diagram, or special overview.
- An open doorway that shows the connected room from a contradictory or unrelated perspective is non-canonical.
- A Codex map using modern digital UI styling is non-canonical unless explicitly requested as a special alternate style.

---

# 19. Changelog

## v1.7 — Protocols and Initialization Edition

Created a new full-copy standalone Codex version.

Preserved v1.6 and consolidated the latest local working updates from the chat session.

Added New Chat Initialization Guide.

Added Assistant Initialization Instruction.

Added Active Protocols section.

Added Rendering Protocols section.

Added Compressed Rendering Protocols section.

Added New Chat Startup Checklist.

Added Current Canon Summary.

Added Room Concise Render Prompt Index.

Added General Render Block.

Added Concise Image Render Prompt Rule.

Added Concise Prompt Topology Rule.

Added Render Prompt Compression Protocol.

Added User Override Protocol.

Added Ambiguity Resolution Protocol.

Added Station Compression Protocol.

Updated room template to include Concise Image Render Prompt.

Added concise image render prompts with room location data for:

- Entry Hall
- Garden
- Small Library
- Foundational Door
- Great Hall
- Hall of Discovery
- Arts Antechamber
- Media Antechamber
- History Antechamber
- Philosophy Antechamber
- Personal Antechamber
- Inventor's Antechamber

## v1.6 — Garden, Map, and Media Antechamber Edition

Created a new full-copy standalone Codex version.

Preserved v1.5 and consolidated the latest local working updates.

Added Eight-Direction Room Viewing Rule.

Expanded the Central Viewing Principle and Forward Hemisphere Rule to support eight-direction room rendering.

Added Fixed Compass Architecture Rule.

Added a dedicated Map Rendering Standards section.

Added Map Aspect Ratio Rule.

Added approved map visual reference for The Great Citadel — Known Rooms Map.

Updated Garden wall, distant mountain, steampunk blimp, and Buddha visibility rules.

Updated Media Antechamber identity, compass door layout, required features, door identity rules, and open-door display rules.

## v1.5 — Rendering Continuity and Arts Antechamber Edition

Created a full-copy standalone Codex version.

Added global 16:9 image-format rule, doorway display rules, doorway identification rules, directional-continuity rules, connected-room perspective rules, general antechamber standards, Entry Hall three-door layout, Garden Buddha statue placement and station, and detailed Arts Antechamber compass layout.

## v1.4 — Garden Meditation Edition

Created a full-copy standalone Codex version.

Replaced the previous patched Garden theme with a refined meditation-garden identity.

Defined the Garden as a dry, bright, open-air Zen meditation garden connected to the Entry Hall side door.

## v1.3 — Station Rendering Edition

Created a full-copy standalone Codex version.

Refactored the Codex structure for image rendering and added station-based rendering standards.

Added Small Library — Instruction Manual Station.

## v1.2 — Great Citadel Foundations Edition

Created a full-copy standalone Codex version.

Changed canonical world name to The Great Citadel.

Retired Front Entry and Hallway as separate rooms.

Unified them into Entry Hall.

Added save protocol, revised Foundations, added antechamber principle, revised room look-and-feel, Great Hall standards, and detailed Small Library rules.

## v1.1 — Entry Hall Edition

Created a full-copy standalone Codex version.

Added Entry Hall as a formal foundational room between the Front Entry and Hallway.

## v1.0 — Discovery Edition

Initial full-copy canonical Codex version.

Included the Foundations, Great Hall, Palace Sigil, Science Realm, Hall of Discovery, Map of Understanding, Compass Rose of Discovery, Celestial Vault, Eight Alcoves of Discovery, and universal rendering standards.
