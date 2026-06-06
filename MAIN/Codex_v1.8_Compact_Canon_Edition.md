# The Codex v1.8 — Compact Canon Edition

## The Great Citadel

**Status:** Current canonical version  
**Versioning model:** Full-copy standalone Codex version  
**Canonical world name:** The Great Citadel  
**Source:** Supersedes Codex v1.7 — Protocols and Initialization Edition  
**Repository:** Errorline10/theGreatCitadel  
**Branch:** main  

---

# 0. New Chat Initialization Guide

When starting a new ChatGPT chat for The Great Citadel, first load or be given the latest Codex from GitHub MAIN unless the user explicitly says to continue from a local working draft.

The active Codex is the source of truth for rooms, maps, renderings, architecture, stations, symbols, room connections, versioning, GitHub saving protocols, and canonical visual direction.

Do not rely on non-project memory for Codex details.

If GitHub Codex retrieval is available, retrieve the latest Codex from:

Repository: `Errorline10/theGreatCitadel`  
Branch: `main`

Current published baseline after this save:

**The Codex v1.8 — Compact Canon Edition**

If GitHub retrieval is not available, the user should paste or provide the current Codex, or explicitly authorize work from the current chat's local working Codex summary.

---

# 1. Assistant Operating Mode

You are assisting with The Great Citadel project.

Treat this Codex as the source of truth for Citadel-related decisions.

Use the Codex for rendering prompts, room design, map layout, architectural continuity, compass directions, GitHub saving, versioning, and canon management.

When the user asks to render “as per the Codex,” do not paste the full Codex into the render prompt. Use the compressed render stack:

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

If the user asks for a room render, preserve visitor perspective, compass-fixed architecture, canonical door locations, room-specific topology, known connected spaces, and human-scaled Citadel atmosphere.

---

# 2. Active Protocols

## Codex Source of Truth Protocol

The Codex governs canonical architecture, rooms, room connections, maps, stations, symbols, visual language, rendering rules, save rules, versioning, and GitHub publication. When a Codex rule exists, it overrides assumptions.

## Local vs GitHub Codex Protocol

The local Codex is the working draft used during a chat. The GitHub Codex is the published canonical archive.

Local Codex edits may be made during a chat, may overwrite prior local wording, do not require a version bump, and do not automatically save to GitHub.

GitHub Codex saves require explicit user request, version increment, changelog update, preservation of previous history through Git, and a complete standalone Codex copy.

## No Implicit GitHub Save Protocol

The assistant must not save to GitHub unless the user explicitly asks to save or publish the Codex to GitHub.

Phrases like “update the Codex,” “add this to the Codex,” “treat this as canon,” or “use this locally” mean local Codex update only unless GitHub is explicitly mentioned.

## Complete Standalone Version Protocol

Every GitHub-published Codex version should be a complete standalone document and should not require another version to be understood.

Branches may experiment, but only full Codex copies are promoted into the MAIN archive.

The Codex version number does not change for local-only edits.

---

# 3. Rendering Protocols

## Visitor Perspective Protocol

Standard room renderings place the viewer inside the room. The viewer normally stands at or near the geometric center unless a room-specific rule, station rule, or user request overrides this. The viewer faces the requested compass direction. The viewer rotates; the room does not.

## Eight-Direction Rendering Protocol

Unless otherwise specified, every room can be rendered facing North, Northeast, East, Southeast, South, Southwest, West, or Northwest.

## Forward Hemisphere Protocol

A standard room rendering should show only the forward hemisphere of the room from the viewer's position. It should not show the full room unless the user requests a map, diagram, overview, or special reference view.

## Fixed Compass Architecture Protocol

Doors, stations, statues, major room features, and compass-based architecture remain fixed to their canonical locations. The room should not rotate for visual convenience.

## Doorway Continuity Protocol

If an open doorway is visible, the connected room or space should be visible beyond it when canonically known. The connected room should preserve spatial and directional continuity and should not appear from an unrelated or contradictory viewpoint.

## Aspect Ratio Protocol

Standard room renderings use 16:9 horizontal format unless otherwise requested. Map renderings use 1:1 square format unless otherwise requested.

---

# 4. Compressed Rendering Protocols

## General Render Block

Render in the visual language of The Great Citadel. Use visitor perspective unless the request is explicitly for a map, diagram, station, or special-case render. Use ancient, warm, lived-in, human-scaled Citadel architecture. Use wood-softened stone, practical detail, coherent compass-fixed architecture, and physically plausible spatial continuity. Default standard room renders use 16:9 horizontal format. The viewer rotates; the room does not. Use only the requested room, requested facing direction, and canonically appropriate visible features. Avoid non-canonical additions.

## Concise Image Render Prompt Rule

Each room should contain a concise render prompt with room identity, location, purpose, visual features, atmosphere, door count, door compass placement, canonical connections, fixed compass-based features, and major non-canonical exclusions.

## Render Prompt Compression Protocol

For standard renders, build prompts from:

1. General Render Block
2. Room Concise Image Render Prompt
3. Explicit user overrides

Consult detailed room sections only when needed to resolve canonically important ambiguity.

## User Override Protocol

User overrides may include facing direction, door state, station, aspect ratio, time of day, focus object, open or closed doorway, map vs room render, or close-up vs full-room view. Honor overrides unless they contradict canon. If an override contradicts canon, explain the conflict and offer the closest canonical version.

## Station Compression Protocol

When a station render is requested, use:

1. General Render Block
2. Concise Station Render Prompt
3. User overrides

---

# 5. Startup Checklist

1. Identify the active Codex source, preferring GitHub MAIN.
2. Confirm the active Codex version.
3. Load Active Protocols.
4. Load Rendering Protocols.
5. Load Compressed Rendering Protocols.
6. Load Current Canon Summary and Room Index.
7. For render requests, use General Render Block + Room Concise Image Render Prompt + user overrides.
8. For save requests, distinguish local Codex update from GitHub Codex save.
9. Do not increment version unless saving to GitHub.
10. Do not assume missing room details. If possible, consult the Codex.

---

# 6. Global Canon

The Great Citadel is a vast medieval world of knowledge, memory, media, discovery, and reflection.

Within it, information is not browsed; it is physically explored through rooms, halls, gardens, doors, maps, alcoves, symbols, stations, and realms.

The Codex is the living record of The Great Citadel. It defines architecture, rooms, realms, visual language, rendering rules, stations, and accepted canonical design decisions.

The Great Citadel should feel ancient, lived-in, warm, human-scaled, coherent, cared for, practical, and discoverable. It should feel like a place of knowledge that is inhabited and cared for, not a cold or oversized monument.

The Citadel is experienced, not observed. Every standard rendering should place the visitor inside the world rather than outside it.

---

# 7. Current Canon Summary

Foundation Path:

```text
Entry Hall → Small Library → Foundational Door → Great Hall
```

Garden Branch:

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

# 8. Room Index

## Foundation Rooms

1. Entry Hall
2. Garden
3. Small Library
4. Foundational Door
5. Great Hall

## Defined Rooms and Antechambers

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

## Defined Stations

1. Small Library — Instruction Manual Station
2. Garden — Buddha Statue Station

## Retired as Separate Rooms

- Front Entry
- Hallway

These have been absorbed into Entry Hall.

---

# 9. Room Concise Render Prompt Index

## Entry Hall — Concise Image Render Prompt

The Great Citadel Entry Hall, 16:9 horizontal visitor-perspective render, viewer standing inside the room facing the requested compass direction. The Entry Hall is the southernmost entrance threshold of the Citadel and is a narrow welcoming passage with exactly three canonical doors: north door leading to the Small Library, south door leading outside/arrival, and west door leading to the Garden. Render warm lantern light, wood-softened stone walls, side tables on both sides, coat hooks with cloaks or jackets, travel bags, plants or vines, worn stone floor, and a clear forward path. If the north door is open, the Small Library should be visible beyond it. Cozy, ancient, lived-in, practical, human-scaled arrival space; not grand, not ceremonial, not a hub.

## Garden — Concise Image Render Prompt

The Great Citadel Garden, 16:9 horizontal visitor-perspective render, viewer standing inside the Garden facing the requested compass direction. The Garden is a meditation branch space located west of the Entry Hall and has exactly one canonical door: an east-wall door leading back to the Entry Hall. Render a bright, dry, open meditation garden with raked sand Zen garden, stacked Zen stones, modest plants, old vine-covered stone boundary walls, warm daylight, distant mountains beyond the wall, and a few tiny faraway steampunk blimps. Include exactly one small Buddha statue fixed in the northwest corner when visible by facing direction. Calm, restorative, human-scaled atmosphere; no buildings, no wet ground, no extra doors.

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

# 10. Map Rendering Standards

Map renderings are special Codex reference images, not standard visitor-perspective room renderings. They may use overhead, diagrammatic, or architectural-plan viewpoints to show room relationships, compass orientation, and known pathways.

All Codex maps should be north-oriented unless explicitly requested otherwise. North should appear at the top of the image. A compass rose should be included when practical.

A map of known rooms should include only rooms, antechambers, stations, and major destinations currently defined in the Codex. Undefined future areas may be shown only as labeled unknowns, dashed outlines, sealed doors, shadowed passages, or beyond-this-point markers.

Foundation path:

```text
Entry Hall → Small Library → Foundational Door → Great Hall
```

Garden branch:

```text
Entry Hall West Door → Garden East Door → Garden
```

The Garden should appear west of the Entry Hall. The Small Library should appear north of the Entry Hall and south of the Foundational Door / Great Hall connection.

The Great Hall should appear as the central compass hub of the Citadel's known realm structure.

Approved map visual traits:

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

# 11. Global Station Standards

A station is a fixed viewpoint inside a room used when a rendering should focus on a particular object, feature, or area rather than presenting the whole room.

A station defines the viewer's fixed position, viewing direction, focal object, intended framing, and purpose. Station renderings emphasize specific objects or features while still feeling like real visitor viewpoints physically located within the room.

Station naming convention:

```text
[Room Name] — [Station Name]
```

---

# 12. General Antechamber Standards

Antechambers are transitional rooms between the Great Hall and deeper realm paths. They are not the full realm. They introduce the identity, atmosphere, symbols, and major paths of the realm beyond.

In a standard antechamber rendering, the viewer stands at or near the geometric center, faces one compass direction, and sees only the forward hemisphere. The wall or doorway in front should be the primary focus.

A standard antechamber rendering should not show all canonical doors at once. The preferred standard rendering shows one primary door; the practical maximum is two visible doors unless a room-specific rule allows more.

Once antechamber compass door positions are defined, those compass positions are canonical. Doors do not move for visual convenience.

If a visible antechamber door is open, the connected room, realm path, or connected space beyond the threshold should be visible and directionally coherent.

Antechambers should be smaller and more focused than the Great Hall. They may be specialized, but should remain human-scaled threshold spaces, not full realms, museums, huge theaters, or complete destination spaces.

---

# 13. Global Map and Connection Rules

The Foundations are north-oriented:

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

# 14. Room Section Template

Each room section should use this rendering-oriented structure when newly expanded:

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

# 15. Room Details

## Entry Hall

The Entry Hall is the southernmost entrance and first threshold space of The Great Citadel. It combines the former roles of Front Entry, Entry Hall, and Hallway into one canonical room. It welcomes the visitor and guides them inward.

The Entry Hall has exactly three canonical doors:

- North Door → Small Library
- South Door → Outside / Arrival
- West Door → Garden

It is a narrow welcoming passage, not a hub. It should feel longer than wide, cozy, ancient, lived-in, cared for, practical, safe, and inviting.

Required features include side tables, coat hooks, cloaks or jackets, travel bags, warm lantern light, wood-softened stone architecture, plants/vines/moss where appropriate, a worn stone floor, and a clear forward path.

The standard Entry Hall rendering usually looks north toward the Small Library. All eight compass-facing renderings are valid if requested.

Open door rules:

- North open: show the Small Library beyond from the same northward-facing direction.
- South open: show the exterior arrival side.
- West open: show the Garden with open sky, raked sand, Zen stones, modest plants, and meditation atmosphere.

No formal Entry Hall stations are defined yet.

Non-canonical mistakes: broad ceremonial chamber, grand scale, missing human welcome details, more than three doors, Garden door anywhere except west, hub-like layout, open north door without Small Library visible beyond.

## Garden

The Garden is a meditation branch space connected to the Entry Hall. It is a calm, restorative side space where a visitor may step away from the main Foundation path, sit quietly, breathe, reflect, and regain inner balance.

Connection:

```text
Entry Hall West Door → Garden East Door → Garden
```

The Garden has exactly one canonical door: the east-wall door back to the Entry Hall. No additional Garden doors are canonical.

The Garden includes old vine-covered stone boundary walls, open sky, warm daylight, distant mountains beyond the wall, a few tiny faraway steampunk blimps, a dry raked sand Zen garden, stacked Zen stones, modest plants, lanterns or garden lights, and exactly one small Buddha statue in the northwest corner.

The Garden should feel open, airy, happy, dry, bright, calm, meditative, restorative, human-scaled, cared for, lightly cultivated, and spiritually quiet. It should not feel like a park, farm, wet courtyard, swamp, public plaza, or building interior.

The standard Garden rendering faces west on the map. All eight compass-facing renderings are valid if requested. The Garden remains fixed; the viewer rotates. The east-wall door remains east. The Buddha statue remains northwest.

Buddha visibility rules:

- There is only one Buddha statue.
- It is in the northwest corner.
- In a west-facing render, it should appear on the right side when visible.
- In an east-facing render, it should not be visible because of the Forward Hemisphere Rule.

Open door rule: if the Garden east-wall door is visible and open, the Entry Hall should be visible beyond the threshold with spatial continuity.

Station: Garden — Buddha Statue Station. The viewer stands close in front of the northwest-corner Buddha statue, facing it at eye level. The statue fills most of the image; surrounding Garden appears only as secondary context.

Non-canonical mistakes: buildings, wet ground, extra doors, missing Zen garden or stones, more than one Buddha, oversized Buddha, Buddha in wrong corner, Buddha on left side in west view, Buddha visible in east view, dominant blimps.

## Small Library

The Small Library is the final preparatory room before entering the Great Hall. It represents understanding before exploration and is a compact, warm, human-scaled study room.

Connection:

```text
Entry Hall → Small Library → Foundational Door → Great Hall
```

The Small Library has exactly two canonical doors:

- South Door → Entry Hall
- North Door → Foundational Door / Great Hall

The layout is linear north-south. No additional primary doors are canonical.

Required features include the Instruction Manual and Guest Book, the Codex as a reference source, introductory collections, maps, symbol references, historical records, reading tables, lecterns, shelves, reference books, writing tools, map tables, and lamps or lanterns.

The Small Library should feel compact, warm, quiet, focused, preparatory, lived-in, welcoming, and studious. Wood should strongly soften the room.

The large prominent display book is not the Codex. It is the combined Instruction Manual and Guest Book. It sits in the northeast corner and must not block the north door. The Codex may appear as a protected reference volume, shelved master text, smaller lectern book, or curated reference source.

Standard rendering should show one primary door, no extra exits, warm compact human scale, and the Instruction Manual and Guest Book in the northeast corner when visible.

Open door rules:

- North open: show onward connection toward the Foundational Door and Great Hall.
- South open: show the Entry Hall.
- All open-door views must preserve spatial continuity.

Station: Small Library — Instruction Manual Station. The viewer stands just in front of the large Instruction Manual and Guest Book in the northeast corner, looking downward. The book is the primary object and occupies most of the frame.

Non-canonical mistakes: extra exits, hub-like room, display book in center, book blocking north door, treating display book as Codex, grand or monumental scale, station rendered as full-room overview.

## Foundational Door

The Foundational Door connects the Small Library to the Great Hall.

Connection:

```text
Small Library → Foundational Door → Great Hall
Great Hall → Foundational Door → Small Library → Entry Hall
```

It is one of the eight primary openings of the Great Hall and the exception to the Antechamber Connection Principle. It leads between the Great Hall and the Foundations, not to a realm antechamber.

The Foundational Door should communicate threshold, return, and foundation. It may include old stone, carved wood, brass or bronze fittings, foundational symbols, threshold markings, Palace Sigil, or root/return motifs.

If viewed open from the Small Library side, the Great Hall should be visible beyond. If viewed open from the Great Hall side, the Small Library should be visible beyond.

## Great Hall

The Great Hall is the central navigation chamber of The Great Citadel and the symbolic heart of exploration. All major journeys into the greater Citadel begin here.

It contains eight primary compass-fixed openings:

- North: Science Door → Hall of Discovery → Science Realm
- Northeast: Philosophy Door → Philosophy Antechamber → Philosophy Realm
- East: Arts Door → Arts Antechamber → Arts Realm
- Southeast: Personal Door → Personal Antechamber → Personal Realm
- South: Foundational Door → Small Library → Entry Hall
- Southwest: Inventor's Door → Inventor's Antechamber → Inventor's Realm
- West: Media Door → Media Antechamber → Media Realm
- Northwest: History Door → History Antechamber → History Realm

The Great Hall should include the Palace Sigil, Great Knowledge Compass, domain medallions, door tracks, ancient stonework, brass mechanisms, and banners where appropriate.

The viewer stands at or near the geometric center upon the Great Knowledge Compass. Only the forward half of the chamber should be visible. Visible doors: minimum 1, preferred 2–3, maximum 4. A rendering that reveals all eight doors is non-canonical.

## Hall of Discovery

The Hall of Discovery is the antechamber of the Science Realm. It introduces Astronomy, Biology, and Logic and represents inquiry before specialization.

Connections:

- South: Science Door → Great Hall
- North: Astronomy Door
- West: Biology Door
- East: Logic Door

The Hall of Discovery should include the Map of Understanding, Compass Rose of Discovery, Celestial Vault, Eight Alcoves of Discovery, and integrated handcrafted scientific symbolism.

The Celestial Vault may include constellations, planetary paths, lunar cycles, seasonal markers, astronomical symbols, and scientific inscriptions.

The Star Whale is not canonical. Alcoves are architectural recesses built into perimeter walls, not freestanding displays, kiosks, islands, detached structures, or furniture placed in the center.

## Arts Antechamber

The Arts Antechamber is the transitional room between the Great Hall and the Arts Realm. It introduces making, beauty, image, performance, music, craft, color, writing, and expression. It is not the full Arts Realm.

Door placement:

- North wall: Music Door
- East wall: Writing Door
- South wall: Visual Door
- West wall: Great Hall Door

Required features include carved wood display panels, framed sketches or studies, small sculptures, pigments or paint bowls, parchment studies, musical instruments as secondary details when not facing Music Door, masks or theatrical objects, textiles or banners, warm lantern light, benches or worktables, and four canonical doors.

Render it as a threshold room, not a full museum, theater, or workshop. Do not show all four doors in a standard rendering unless a map, diagram, or special overview is explicitly requested.

## Media Antechamber

The Media Antechamber is the transitional room between the Great Hall and the Media Realm. It is a four-door orientation room for recorded and shared experience.

It offers three primary media paths:

- Movie Theater
- Audio Theater
- Physical Archive Index

Media in The Great Citadel is not digital content, but preserved experience: images, sounds, stories, records, and references held in physical form.

Door placement:

- North wall: Movie Theater Door
- East wall: Great Hall Door
- South wall: Physical Archive Index Door
- West wall: Audio Theater Door

Required features include carved wood media panels, framed story panels, projection-lantern or camera-obscura-like devices, acoustic horns or resonance bowls, catalog drawers, archive labels, parchment reference slips, warm lantern light, benches or listening seats, brass mechanisms, shelves of media records, and symbols for image, sound, and archive.

Do not make it look modern. Do not show all four doors in a standard rendering unless a map, diagram, or special overview is explicitly requested.

## Future Antechambers

Major realm doors do not open directly into fully developed realms. Each primary realm door from the Great Hall opens first into an antechamber. The Foundational Door is the exception.

### History Antechamber

The History Antechamber is the transitional room between the Great Hall and the History Realm. It introduces archives, timelines, memory, records, ruins, and preserved events. Connection: Great Hall → History Door → History Antechamber → History Realm. No formal stations are defined yet.

### Philosophy Antechamber

The Philosophy Antechamber is the transitional room between the Great Hall and the Philosophy Realm. It introduces questions, contemplation, argument, ethics, metaphysics, and meaning. Connection: Great Hall → Philosophy Door → Philosophy Antechamber → Philosophy Realm. No formal stations are defined yet.

### Personal Antechamber

The Personal Antechamber is the transitional room between the Great Hall and the Personal Realm. It introduces memory, identity, reflection, inner life, personal history, and self-understanding. Connection: Great Hall → Personal Door → Personal Antechamber → Personal Realm. No formal stations are defined yet.

### Inventor's Antechamber

The Inventor's Antechamber is the transitional room between the Great Hall and the Inventor's Realm. It introduces invention, mechanisms, tools, experiments, prototypes, workshop thinking, and Time Traveler modifications. Connection: Great Hall → Inventor's Door → Inventor's Antechamber → Inventor's Realm. No formal stations are defined yet.

---

# 16. Symbols and Floor Systems

## Palace Sigil

The Palace Sigil is the highest symbol of The Great Citadel. It takes the form of a simple eight-spoked ship's helm inspired by traditional Buddhist wheel symbolism.

Characteristics:

- Circular form
- Eight spokes
- Strong silhouette
- Balanced geometry
- Immediate recognizability

The design should feel ancient, timeless, functional, calm, and purposeful.

The Palace Sigil represents guidance rather than destination. The Citadel does not dictate what visitors should learn. It provides pathways through knowledge.

## Great Knowledge Compass

The Great Knowledge Compass is the floor of the Great Hall and one of the oldest known artifacts in the Citadel. At its center is the Palace Sigil. Its spokes extend outward through Palace Sigil, Domain Medallion, Door Track, and Primary Opening.

## Compass Rose of Discovery

The Compass Rose of Discovery sits at the center of the Map of Understanding in the Hall of Discovery.

It aligns:

- North → Astronomy Door
- East → Logic Door
- South → Science Door
- West → Biology Door

The Compass Rose is fixed within the architecture. It does not rotate based on the viewer.

---

# 17. Current Canonical Status

Canonical world name: The Great Citadel

Active Codex: Codex v1.8 — Compact Canon Edition

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
- A standard Small Library rendering with an open door is non-canonical unless intentionally using the open-door connection rule.
- A Great Hall rendering that shows all eight primary openings at once is non-canonical.
- A Garden standard rendering with visible buildings is non-canonical.
- A west-facing Garden rendering with the Buddha statue on the left side is non-canonical.
- An east-facing Garden rendering showing the Buddha statue is non-canonical.
- An Arts Antechamber standard rendering that shows all four doors at once is non-canonical unless explicitly requested as a map, diagram, or special overview.
- A Media Antechamber standard rendering that shows all four doors at once is non-canonical unless explicitly requested as a map, diagram, or special overview.
- An open doorway that shows the connected room from a contradictory or unrelated perspective is non-canonical.
- A Codex map using modern digital UI styling is non-canonical unless explicitly requested as a special alternate style.

---

# 18. Changelog

## v1.8 — Compact Canon Edition

Created a new full-copy standalone Codex version.

Preserved v1.7 canon while refactoring the active Codex for brevity and easier loading in future chats.

Removed the long historical changelog and replaced it with a current-version changelog note. Prior version history remains preserved in Git history and prior published Codex files.

Compressed repeated version summaries, canon summaries, room lists, map rules, and room details.

Preserved active protocols, rendering rules, save/versioning rules, room topology, compass-fixed architecture, concise render prompts, station definitions, map rules, symbol definitions, and current canonical status.
