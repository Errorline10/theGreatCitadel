# The Codex v2.2 — Render Compliance Edition

## The Great Citadel

**Status:** Current canonical version  
**Versioning model:** Full-copy standalone Codex version  
**Canonical world name:** The Great Citadel  
**Source:** GitHub MAIN  
**Repository:** Errorline10/theGreatCitadel  
**Branch:** main  
**Supersedes:** The Codex v2.1 — Render Compliance Edition

---

# 0. New Chat Initialization Guide

When starting a new ChatGPT chat for The Great Citadel, first load or be given the latest Codex from GitHub MAIN unless the user explicitly says to continue from a local working draft.

The active Codex is the source of truth for rooms, maps, renderings, architecture, stations, symbols, room connections, versioning, GitHub saving protocols, and canonical visual direction.

Do not rely on non-project memory for Codex details.

If GitHub Codex retrieval is available, retrieve the latest Codex from:

Repository: `Errorline10/theGreatCitadel`  
Branch: `main`

Current published Codex:

**The Codex v2.2 — Render Compliance Edition**

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

When high-fidelity canon compliance is important, use the Codex Compliance Render Workflow before and after image generation.

When the user asks to update the Codex, update the local working Codex unless they explicitly asks to save to GitHub.

When the user asks to save to GitHub, increment the version and save a complete standalone Codex.

If the user asks what is canon, answer from the Codex.

If the user asks for a room render, preserve visitor perspective, compass-fixed architecture, canonical door locations, room-specific topology, known connected spaces, stations, navigational paths, and human-scaled Citadel atmosphere.

---

# 2. Active Protocols

## Codex Source of Truth Protocol

The Codex governs canonical architecture, rooms, room connections, maps, stations, symbols, visual language, rendering rules, save rules, versioning, and GitHub publication. When a Codex rule exists, it overrides assumptions.

## Codex as Specification Protocol

For rendering, the Codex should be treated as a specification document rather than a loose thematic guide.

The assistant should construct images from explicit canonical requirements rather than generic genre inference.

When ambiguity exists, prefer:

1. The written Codex.
2. The room's Canonical Visual Specification.
3. The compliance checklist.
4. Established canonical visual references.
5. The narrowest interpretation consistent with canon.

Generic fantasy assumptions should be minimized.

## Local vs GitHub Codex Protocol

The local Codex is the working draft used during a chat. The GitHub Codex is the published canonical archive.

Local Codex edits may be made during a chat, may overwrite prior local wording, do not require a version bump, and do not automatically save to GitHub.

GitHub Codex saves require explicit user request, version increment, preservation of previous history through Git, and a complete standalone Codex copy.

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

## Open Door Room Derivation Protocol

When an open doorway reveals a connected room, the visible space beyond the threshold must be derived from the Codex definition of the connected room. The assistant shall not invent the appearance of the connected room from generic fantasy assumptions.

The connected room visible through the doorway must be constructed using:

1. The General Render Block.
2. The connected room's Concise Image Render Prompt.
3. Any canonical room details defined elsewhere in the Codex.
4. Applicable room-specific rendering rules.

The connected room should display the visual identity, architecture, atmosphere, furnishings, symbols, compass-fixed features, and canonical layout elements defined for that room.

An open doorway should function as a partial render of the connected room.

## Topology Preservation Rule

When a connected room is visible through an open doorway, the visible portion of that room must preserve the connected room's canonical door layout, compass orientation, navigational structure, and room topology.

Canonical architectural elements take precedence over decorative elements.

A canonical doorway, opening, threshold, passage, or navigational feature may not be replaced, blocked, hidden, or visually contradicted by shelves, furniture, statues, displays, decorations, storage, architectural embellishments, or other room contents.

When rendering a connected room through an open doorway, first place the canonical doors and navigational structure defined by the Codex and then populate the remaining visible space with the room's furnishings and decorative features.

## Navigational Path Preservation Protocol

The Great Citadel is fundamentally a navigable architectural space. Rooms, halls, thresholds, antechambers, and gardens exist to connect destinations through coherent pathways.

When rendering any room, canonical circulation paths and navigational routes take precedence over furniture, decorations, displays, storage, decorative objects, or atmospheric details.

A visitor should be able to visually understand how movement through the room occurs.

Primary paths between canonical doors, openings, thresholds, stations, and major destinations should remain recognizable and unobstructed.

Furniture and decorative elements may enrich a room but should generally be arranged around navigational routes rather than within them.

## Station Visibility Inheritance Protocol

When an open doorway reveals a connected room, any canonical station located within the visible portion of that room should also be considered during rendering.

Stations are part of the canonical identity of a room and should not disappear simply because the room is being viewed from an adjacent space.

When constructing a doorway view, the assistant should:

1. Derive the connected room from its canonical room definition.
2. Preserve topology and navigational structure.
3. Determine whether any defined stations fall within the visible field of view.
4. Render those stations as secondary but recognizable features.

Stations should remain subordinate to the primary room composition unless the user explicitly requests a station render.

## Aspect Ratio Protocol

Standard room renderings use 16:9 horizontal format unless otherwise requested. Map renderings use 1:1 square format unless otherwise requested.

---

# 4. Compressed Rendering Protocols

## General Render Block

Render in the visual language of The Great Citadel. Use visitor perspective unless the request is explicitly for a map, diagram, station, or special-case render. Use ancient, warm, lived-in, human-scaled Citadel architecture. Use wood-softened stone, practical detail, coherent compass-fixed architecture, and physically plausible spatial continuity. Default standard room renders use 16:9 horizontal format. The viewer rotates; the room does not. Use only the requested room, requested facing direction, and canonically appropriate visible features. Avoid non-canonical additions. Preserve canonical door topology, open-door connected-room derivation, navigational paths, and visible stations where applicable.

## Concise Image Render Prompt Rule

Each room should contain a concise render prompt with room identity, location, purpose, visual features, atmosphere, door count, door compass placement, canonical connections, fixed compass-based features, stations where relevant, navigational topology, and major non-canonical exclusions.

## Render Prompt Compression Protocol

For standard renders, build prompts from:

1. General Render Block.
2. Room Concise Image Render Prompt.
3. Explicit user overrides.

Consult detailed room sections only when needed to resolve canonically important ambiguity.

## User Override Protocol

User overrides may include facing direction, door state, station, aspect ratio, time of day, focus object, open or closed doorway, map vs room render, or close-up vs full-room view. Honor overrides unless they contradict canon. If an override contradicts canon, explain the conflict and offer the closest canonical version.

## Station Compression Protocol

When a station render is requested, use:

1. General Render Block.
2. Concise Station Render Prompt.
3. User overrides.

---

# 5. Render Compliance Protocols

## Pre-Render Requirement Extraction Protocol

Before any render is generated, the assistant should first extract the exact Codex requirements relevant to the requested image.

This requirement extraction should identify, where applicable:

- room name
- viewer position
- facing direction
- visible doors
- hidden doors
- canonical connections
- connected-room visibility rules
- required architectural features
- required furnishings or stations
- required floor symbols
- required wall symbols
- required atmosphere
- aspect ratio
- non-canonical exclusions

The assistant should not proceed as though a room is merely a themed inspiration. It should first translate the Codex into a structured render specification.

## Strict Prompt Disclosure Protocol

When requested by the user, or when high fidelity is important, the assistant should provide the exact strict render prompt it intends to use before image generation.

This prompt should be based only on:

1. The General Render Block.
2. The room's Concise Image Render Prompt.
3. The room's Canonical Visual Specification.
4. Explicit user overrides.
5. Applicable non-canonical exclusions.

The strict prompt should minimize ambiguity and reduce generic fantasy substitutions.

## Render Compliance Checklist Protocol

Before rendering, the assistant should be able to list the specific compliance targets for the image.

A compliance checklist may include:

- required viewpoint
- required visible doors
- prohibited visible doors
- required connected-room identity
- required symbols
- required stations if visible
- required navigational paths
- required atmosphere
- required exclusions

This checklist acts as the immediate standard against which the final image should be judged.

## Post-Render Compliance Audit Protocol

After a render is produced, the assistant should compare the result against the active Codex requirements and identify:

- compliant elements
- partially compliant elements
- missing required elements
- non-canonical additions
- topology failures
- connected-room derivation failures
- navigational-path failures
- station-visibility failures
- symbolic or architectural identity failures

The assistant should not assume a render is canonical merely because it appears visually attractive or approximately correct.

## Correction Iteration Protocol

If a render is not sufficiently Codex compliant, the assistant should perform a correction pass only after user approval.

A correction pass should:

1. Preserve correct elements from the previous render where possible.
2. Explicitly list the failures to be corrected.
3. Ask whether the user wants to try again.
4. Re-render using those corrections as direct constraints only after user approval.
5. Re-audit the result.

Recommended workflow:

```text
Requirement Extraction
→ Strict Prompt
→ Render
→ Compliance Audit
→ Ask: Would you like to "try again"?
→ Correction Render, only if approved
→ Re-Audit
```

The assistant should prefer iterative correction over repeated vague regeneration, but must not automatically spend another image-generation request without user approval.

## User Approval Before Re-Render Protocol

When a render fails its compliance audit, the assistant shall not automatically request a correction render from the image-generation system.

Instead, the assistant shall:

1. Complete the compliance audit.
2. List all identified compliance failures.
3. Provide an overall compliance assessment.
4. Explain the recommended corrections.
5. Ask the user whether they wish to attempt another render.

The preferred wording is:

```text
Would you like to "try again"?
```

Only after receiving user approval should the assistant initiate a new image-generation request.

This protocol applies even when the assistant believes a correction render would improve compliance.

The purpose of this protocol is to preserve image-generation quota, allow the user to review failures first, permit manual Codex updates before rerendering, and ensure rerendering remains user-directed.

This protocol overrides any workflow that would automatically proceed to a correction render.

## Canonical Visual Reference Protocol

When a render is approved by the user as sufficiently canonical, it may be designated as a canonical visual reference for that room, station, or view.

Canonical visual references may be used in future renders to improve consistency of layout, camera framing, scale, material language, door placement, furnishing placement, and visual identity.

A canonical visual reference does not override the written Codex, but it becomes a secondary fidelity anchor for future renders.

## Non-Canonical Exclusion Expansion Protocol

Each room or station should define not only what must appear, but also what must not appear. Non-canonical exclusions should be treated as active constraints, not optional notes.

Examples of exclusions may include extra doors, missing canonical doors, furniture blocking circulation paths, cathedral-like scale where not appropriate, generic connected-room substitutions, modern objects, invented symbols, invented architectural levels, incorrect station placement, and contradictory connected-room views.

Negative constraints are as important as positive constraints in maintaining canon.

---

# 6. Startup Checklist

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
11. For visible open doors, derive the connected room from the connected room's Codex entry.
12. Preserve topology, navigational path, and visible stations in doorway views.
13. For high-fidelity renders, extract exact room requirements before rendering.
14. Use a compliance checklist when canon precision matters.
15. Use a strict prompt when ambiguity could cause drift.
16. Audit renders against the Codex after generation.
17. If needed, use correction iteration rather than vague rerendering.
18. Preserve user-approved reference renders as canonical visual anchors when designated.
19. Before any correction re-render, ask whether the user wants to try again.

---

# 7. Global Canon

The Great Citadel is a vast medieval world of knowledge, memory, media, discovery, and reflection.

Within it, information is not browsed; it is physically explored through rooms, halls, gardens, doors, maps, alcoves, symbols, stations, and realms.

The Codex is the living record of The Great Citadel. It defines architecture, rooms, realms, visual language, rendering rules, stations, and accepted canonical design decisions.

The Great Citadel should feel ancient, lived-in, warm, human-scaled, coherent, cared for, practical, and discoverable. It should feel like a place of knowledge that is inhabited and cared for, not a cold or oversized monument.

The Citadel is experienced, not observed. Every standard rendering should place the visitor inside the world rather than outside it.

The Citadel is navigated through legible paths. Furniture, decorative objects, and atmospheric details must support rather than override canonical movement through the architecture.

---

# 8. Current Canon Summary

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

# 9. Room Index

## Rooms and Antechambers

1. Entry Hall
2. Garden
3. Small Library
4. Foundational Door
5. Great Hall
6. Hall of Discovery
7. Media Antechamber
8. History Antechamber
9. Philosophy Antechamber
10. Arts Antechamber
11. Personal Antechamber
12. Inventor's Antechamber

## Defined Stations

1. Small Library — Instruction Manual Station
2. Garden — Buddha Statue Station

---

# 10. Room Concise Render Prompt Index

## Entry Hall — Concise Image Render Prompt

The Great Citadel Entry Hall, 16:9 horizontal visitor-perspective render. Viewer standing near the center of the Entry Hall facing the requested compass direction. The Entry Hall is the southernmost entrance threshold of the Citadel and is a narrow north-south welcoming passage that is noticeably longer than it is wide. It contains exactly three canonical doors: north door leading to the Small Library, south door leading outside/arrival, and west door leading to the Garden. Render warm lantern light, wood-softened stone walls, side tables on both sides, coat hooks with cloaks or jackets, travel bags, plants or vines, worn stone floor, and a clear navigational path through the hall.

North-facing Entry Hall render requirements: the North Door must be centered or near-centered and should be open by default; the Small Library must be clearly visible beyond the North Door with spatial continuity; the West Door must be visible on the left wall of the image because west is to the viewer's left when facing north; the West Door should visibly read as a secondary side doorway leading toward the Garden; the South Door is behind the viewer and should not be visible in a standard north-facing render. Cozy, ancient, lived-in, practical, human-scaled arrival space; not grand, not ceremonial, not a hub, not cathedral-like, not palace-like.

## Garden — Concise Image Render Prompt

The Great Citadel Garden, 16:9 horizontal visitor-perspective render, viewer standing inside the Garden facing the requested compass direction. The Garden is a meditation branch space located west of the Entry Hall and has exactly one canonical door: an east-wall door leading back to the Entry Hall. Render a bright, dry, open meditation garden with raked sand Zen garden, stacked Zen stones, modest plants, old vine-covered stone boundary walls, warm daylight, distant mountains beyond the wall, and a few tiny faraway steampunk blimps. Include exactly one small Buddha statue fixed in the northwest corner when visible by facing direction. Calm, restorative, human-scaled atmosphere; no buildings, no wet ground, no extra doors.

## Small Library — Concise Image Render Prompt

The Great Citadel Small Library, 16:9 horizontal visitor-perspective render, compact warm human-scaled study room. The Small Library is located north of the Entry Hall and south of the Foundational Door / Great Hall connection, and has exactly two canonical doors: south door to the Entry Hall and north door onward toward the Foundational Door and Great Hall. Preserve a clear north-south navigational path between the two doors. Render wood-softened stone architecture, shelves of reference books, maps, lamps, writing tools, lecterns, side or corner reading tables, introductory collections, and the Instruction Manual and Guest Book in the northeast corner when visible. The Instruction Manual and Guest Book should be a recognizable station feature when its corner is visible, but it should remain subordinate unless a station render is requested. Quiet, preparatory, welcoming scholarly atmosphere; one primary door visible in standard rendering, no extra exits, not grand, not a hub. Furnishings may not block or replace the south door, north door, or central circulation path.

## Foundational Door — Concise Image Render Prompt

The Great Citadel Foundational Door, 16:9 horizontal visitor-perspective render, ancient threshold between the Foundations and the Great Hall. The Foundational Door is located north of the Small Library and south of the Great Hall and connects Small Library → Foundational Door → Great Hall. Render old stone framing, carved wood door structure, brass or bronze fittings, threshold markings, foundational symbols, and Palace Sigil or root-and-return motifs where appropriate. If open, show the connected side beyond the threshold with clear spatial continuity and derived-room identity. Warm, ancient, meaningful transition space; not a realm door and not an antechamber entrance.

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

# 11. Canonical Visual Specification Standard

Each room and station should include a Canonical Visual Specification section to reduce ambiguity in rendering.

The Canonical Visual Specification should define, where possible:

- standard viewer position
- standard camera height
- standard framing
- standard facing orientation
- visible doors by facing direction
- hidden doors by facing direction
- primary focal architecture
- required floor features
- required wall features
- required station visibility
- connected-room reveal rules
- navigational path requirements
- required props or furnishings
- forbidden props or furnishings
- scale and proportion guidance
- non-canonical exclusions

This specification is intended to make render requests more deterministic and less interpretive.

---

# 12. Map Rendering Standards

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

# 13. Global Station Standards

A station is a fixed viewpoint inside a room used when a rendering should focus on a particular object, feature, or area rather than presenting the whole room.

A station defines the viewer's fixed position, viewing direction, focal object, intended framing, and purpose. Station renderings emphasize specific objects or features while still feeling like real visitor viewpoints physically located within the room.

Station naming convention:

```text
[Room Name] — [Station Name]
```

Stations may also appear as secondary visible features in doorway views when they fall within the visible portion of the connected room. In doorway views, stations must remain subordinate unless explicitly requested.

---

# 14. General Antechamber Standards

Antechambers are transitional rooms between the Great Hall and deeper realm paths. They are not the full realm. They introduce the identity, atmosphere, symbols, and major paths of the realm beyond.

In a standard antechamber rendering, the viewer stands at or near the geometric center, faces one compass direction, and sees only the forward hemisphere. The wall or doorway in front should be the primary focus.

A standard antechamber rendering should not show all canonical doors at once. The preferred standard rendering shows one primary door; the practical maximum is two visible doors unless a room-specific rule allows more.

Once antechamber compass door positions are defined, those compass positions are canonical. Doors do not move for visual convenience.

If a visible antechamber door is open, the connected room, realm path, or connected space beyond the threshold should be visible and directionally coherent. The connected view must follow Open Door Room Derivation, Topology Preservation, Navigational Path Preservation, and Station Visibility Inheritance Protocols.

Antechambers should be smaller and more focused than the Great Hall. They may be specialized, but should remain human-scaled threshold spaces, not full realms, museums, huge theaters, or complete destination spaces.

---

# 15. Global Map and Connection Rules

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

# 16. Room Section Template

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
### Canonical Visual Specification
### Open Door Display Rules
### Stations
### Concise Image Render Prompt
### Compliance Checklist
### Non-Canonical Mistakes to Avoid
```

---

# 17. Codex Compliance Render Workflow

When the user requests a room render and fidelity matters, the assistant should follow this workflow:

1. Identify the active Codex source.
2. Extract the exact room requirements.
3. Produce a compliance checklist.
4. Produce a strict render prompt if requested or useful.
5. Generate the image.
6. Audit the image against the checklist.
7. If the render fails or is only partially compliant, list failures and ask the user: `Would you like to "try again"?`
8. Only generate a correction render after the user approves another attempt.
9. Preserve approved renders as canonical visual references when designated by the user.

This workflow is the preferred method for high-fidelity canonical rendering.

---

# 18. Room Details

## Entry Hall

### Purpose

The Entry Hall is the southernmost entrance and first threshold space of The Great Citadel. It welcomes the visitor and guides them inward.

### Connections

The Entry Hall has exactly three canonical doors:

- North Door → Small Library
- South Door → Outside / Arrival
- West Door → Garden

### Door Rules

The Entry Hall is a narrow welcoming passage, not a hub. It should feel longer than wide, cozy, ancient, lived-in, cared for, practical, safe, and inviting.

### Required Features

Required features include side tables, coat hooks, cloaks or jackets, travel bags, warm lantern light, wood-softened stone architecture, plants/vines/moss where appropriate, a worn stone floor, and a clear forward path.

### Standard Rendering Rules

The standard Entry Hall rendering usually looks north toward the Small Library. All eight compass-facing renderings are valid if requested.

### Canonical Visual Specification

For a north-facing Entry Hall render:

- Viewer stands near the center of the Entry Hall.
- Viewer faces north.
- North Door is centered or near-centered ahead.
- North Door is open by default.
- Small Library is visible beyond the North Door and must read as a compact study room.
- West Door is visible on the left wall because west is left when facing north.
- West Door should read as a secondary side doorway leading to the Garden.
- South Door is behind the viewer and should not be visible.
- The room must read as a narrow north-south passage, longer than wide.
- A clear circulation path must run from the viewer toward the North Door.
- Side tables, coats, travel bags, lanterns, plants or vines, and worn stone floor should support the path without blocking it.
- The Entry Hall must not become a grand hall, cathedral nave, palace foyer, ceremonial chamber, or central hub.

### Open Door Display Rules

- North open: show the Small Library beyond from the same northward-facing direction. The visible Small Library must derive from the Small Library Codex definition, preserve its south-to-north topology, show the northward onward door when visible, maintain the central navigational path, and include the Instruction Manual Station as a secondary recognizable feature if the northeast corner is visible.
- South open: show the exterior arrival side.
- West open: show the Garden with open sky, raked sand, Zen stones, modest plants, meditation atmosphere, and the Garden's Codex-defined features where visible.

### Stations

No formal Entry Hall stations are defined yet.

### Compliance Checklist

A north-facing Entry Hall render is compliant only if:

- It shows the viewer inside a narrow, human-scaled north-south passage.
- The North Door is the centered or near-centered primary focal doorway.
- The North Door is open by default.
- The Small Library is visible beyond and recognizable as the Small Library, not a generic room.
- The West Garden Door is visible on the left wall.
- The South Door is not visible.
- Exactly three canonical doors exist in the room, even if not all are visible.
- The central path remains clear.
- Side tables, coats, bags, lanterns, plants/vines, wood, stone, and lived-in details are present.
- The room is not grand, hub-like, cathedral-like, palace-like, or ceremonial.

### Non-Canonical Mistakes to Avoid

Broad ceremonial chamber, grand scale, missing human welcome details, more than three doors, Garden door anywhere except west, hub-like layout, open north door without Small Library visible beyond, missing visible west-wall Garden door in a north-facing render, connected Small Library rendered as a generic library, bookshelf replacing the Small Library's north door, table blocking the Small Library circulation path, missing visible station when the station's corner is visible.

## Garden

### Purpose

The Garden is a meditation branch space connected to the Entry Hall. It is a calm, restorative side space where a visitor may step away from the main Foundation path, sit quietly, breathe, reflect, and regain inner balance.

### Connections

```text
Entry Hall West Door → Garden East Door → Garden
```

### Door Rules

The Garden has exactly one canonical door: the east-wall door back to the Entry Hall. No additional Garden doors are canonical.

### Required Features

The Garden includes old vine-covered stone boundary walls, open sky, warm daylight, distant mountains beyond the wall, a few tiny faraway steampunk blimps, a dry raked sand Zen garden, stacked Zen stones, modest plants, lanterns or garden lights, and exactly one small Buddha statue in the northwest corner.

### Material and Atmosphere

The Garden should feel open, airy, happy, dry, bright, calm, meditative, restorative, human-scaled, cared for, lightly cultivated, and spiritually quiet. It should not feel like a park, farm, wet courtyard, swamp, public plaza, or building interior.

### Standard Rendering Rules

The standard Garden rendering faces west on the map. All eight compass-facing renderings are valid if requested. The Garden remains fixed; the viewer rotates. The east-wall door remains east. The Buddha statue remains northwest.

### Canonical Visual Specification

- Exactly one east-wall door returns to the Entry Hall.
- The garden is outdoors or open-sky, never a building interior.
- It is dry, bright, and meditative.
- The raked sand and stacked stones are core identity features.
- Distant mountains and tiny steampunk blimps may be visible beyond the boundary wall.
- The single Buddha statue remains in the northwest corner and must not move for composition.

### Open Door Display Rules

If the Garden east-wall door is visible and open, the Entry Hall should be visible beyond the threshold with spatial continuity and derived from the Entry Hall Codex definition.

### Stations

Garden — Buddha Statue Station. The viewer stands close in front of the northwest-corner Buddha statue, facing it at eye level. The statue fills most of the image; surrounding Garden appears only as secondary context.

### Compliance Checklist

A Garden render is compliant only if:

- It has exactly one canonical door on the east wall.
- It reads as an open, dry meditation garden.
- Raked sand and Zen stones are visible.
- The Buddha statue appears only when the northwest corner is visible.
- The Buddha statue is small and singular.
- No buildings, wet ground, extra doors, or park-like public plaza elements dominate.

### Non-Canonical Mistakes to Avoid

Buildings, wet ground, extra doors, missing Zen garden or stones, more than one Buddha, oversized Buddha, Buddha in wrong corner, Buddha on left side in west view, Buddha visible in east view, dominant blimps.

## Small Library

### Purpose

The Small Library is the final preparatory room before entering the Great Hall. It represents understanding before exploration and is a compact, warm, human-scaled study room.

### Connections

```text
Entry Hall → Small Library → Foundational Door → Great Hall
```

### Door Rules

The Small Library has exactly two canonical doors:

- South Door → Entry Hall
- North Door → Foundational Door / Great Hall

The layout is linear north-south. No additional primary doors are canonical. A clear north-south navigational path should remain visible and unobstructed between the south and north doors.

### Required Features

Required features include the Instruction Manual and Guest Book, the Codex as a reference source, introductory collections, maps, symbol references, historical records, reading tables, lecterns, shelves, reference books, writing tools, map tables, and lamps or lanterns.

### Material and Atmosphere

The Small Library should feel compact, warm, quiet, focused, preparatory, lived-in, welcoming, and studious. Wood should strongly soften the room.

### Standard Rendering Rules

The large prominent display book is the combined Instruction Manual and Guest Book. It sits in the northeast corner and must not block the north door. The Codex may appear as a protected reference volume, shelved master text, smaller lectern book, or curated reference source.

Standard rendering should show one primary door, no extra exits, warm compact human scale, a clear navigation path, and the Instruction Manual and Guest Book in the northeast corner when visible.

### Canonical Visual Specification

- The room is compact and human-scaled.
- The room is linear north-south.
- The south and north doors must remain architecturally present and unobstructed.
- Shelves and reading tables may line the room but may not block the center path.
- The Instruction Manual and Guest Book occupy the northeast corner as a recognizable station feature when visible.
- The Instruction Manual and Guest Book are not the Codex.
- The room should not appear as a large grand library, hub, or multi-exit archive.

### Open Door Display Rules

- North open: show onward connection toward the Foundational Door and Great Hall.
- South open: show the Entry Hall.
- All open-door views must preserve spatial continuity, connected-room derivation, topology, navigational path, and station visibility rules.

### Stations

Small Library — Instruction Manual Station. The viewer stands just in front of the large Instruction Manual and Guest Book in the northeast corner, looking downward. The book is the primary object and occupies most of the frame.

### Compliance Checklist

A Small Library render is compliant only if:

- It remains compact, warm, and human-scaled.
- It has exactly two canonical doors.
- The north-south path remains clear.
- Shelves, tables, lecterns, maps, writing tools, and lamps support the study atmosphere.
- The Instruction Manual and Guest Book appear in the northeast corner when visible.
- Furnishings do not replace or block canonical doors.

### Non-Canonical Mistakes to Avoid

Extra exits, hub-like room, display book in center, book blocking north door, treating display book as Codex, grand or monumental scale, station rendered as full-room overview, reading table blocking the north-south path, shelves replacing a canonical door.

## Foundational Door

### Purpose

The Foundational Door connects the Small Library to the Great Hall. It is one of the eight primary openings of the Great Hall and the exception to the Antechamber Connection Principle. It leads between the Great Hall and the Foundations, not to a realm antechamber.

### Connections

```text
Small Library → Foundational Door → Great Hall
Great Hall → Foundational Door → Small Library → Entry Hall
```

### Door Rules

The Foundational Door is located north of the Small Library and south of the Great Hall.

### Required Features

The Foundational Door should communicate threshold, return, and foundation. It may include old stone, carved wood, brass or bronze fittings, foundational symbols, threshold markings, Palace Sigil, or root/return motifs.

### Canonical Visual Specification

- The Foundational Door is a threshold, not a realm door.
- It should visually connect foundation, return, and arrival.
- It should preserve continuity between the Small Library and Great Hall.
- It may show root-and-return motifs or Palace Sigil references.
- It should never become a separate antechamber, realm door, or unrelated ceremonial gate.

### Open Door Display Rules

If viewed open from the Small Library side, the Great Hall should be visible beyond. If viewed open from the Great Hall side, the Small Library should be visible beyond. Connected-room visibility must follow Open Door Room Derivation, Topology Preservation, Navigational Path Preservation, and Station Visibility Inheritance Protocols.

### Non-Canonical Mistakes to Avoid

Treating the Foundational Door as a realm entrance, adding an unrelated antechamber between Small Library and Great Hall, losing the foundation/return identity, or showing a generic fantasy doorway without connected-room continuity.

## Great Hall

### Purpose

The Great Hall is the central navigation chamber of The Great Citadel and the symbolic heart of exploration. All major journeys into the greater Citadel begin here.

### Connections

It contains eight primary compass-fixed openings:

- North: Science Door → Hall of Discovery → Science Realm
- Northeast: Philosophy Door → Philosophy Antechamber → Philosophy Realm
- East: Arts Door → Arts Antechamber → Arts Realm
- Southeast: Personal Door → Personal Antechamber → Personal Realm
- South: Foundational Door → Small Library → Entry Hall
- Southwest: Inventor's Door → Inventor's Antechamber → Inventor's Realm
- West: Media Door → Media Antechamber → Media Realm
- Northwest: History Door → History Antechamber → History Realm

### Door Rules

The eight openings are fixed by compass and do not move for composition. The Foundational Door is the south opening and leads back to the Small Library rather than to an antechamber.

### Required Features

The Great Hall should include the Palace Sigil, Great Knowledge Compass, domain medallions, door tracks, ancient stonework, brass mechanisms, and banners where appropriate.

### Standard Rendering Rules

The viewer stands at or near the geometric center upon the Great Knowledge Compass. Only the forward half of the chamber should be visible. Visible doors: minimum 1, preferred 2–3, maximum 4. A rendering that reveals all eight doors is non-canonical.

### Canonical Visual Specification

For a north-facing Great Hall render:

- Viewer stands at or near the geometric center of the Great Hall, upon the Great Knowledge Compass.
- Viewer faces north.
- The North Science Door is centered or near-centered ahead and is the primary focal doorway.
- The Northwest History Door may appear to the left side of the forward view.
- The Northeast Philosophy Door may appear to the right side of the forward view.
- The visible doors should be 1 to 3 by default and never more than 4.
- The South Foundational Door is behind the viewer and should not be visible in a standard north-facing render.
- The East Arts Door, Southeast Personal Door, Southwest Inventor's Door, and West Media Door should not all appear in a north-facing standard render.
- The Great Knowledge Compass should be partially visible beneath or around the viewer's viewpoint, not shown as a full overhead map.
- The Palace Sigil should appear as a simple eight-spoked ship's helm inspired by Buddhist wheel symbolism, located at the center of the Great Knowledge Compass.
- Domain medallions and door tracks should communicate a compass-fixed navigation system.
- If the Science Door is open, the visible space beyond must derive from the Hall of Discovery definition: Map of Understanding, Compass Rose of Discovery, Celestial Vault, integrated wall alcoves, warm stone, wood, brass, parchment, and recognizable astronomy/biology/logic cues where visible.
- The Great Hall must feel ancient, coherent, warm, navigable, human-scaled enough for a visitor to occupy, and central without becoming a generic cathedral, throne room, palace lobby, museum rotunda, or all-door panorama.

### Open Door Display Rules

If a visible Great Hall doorway is open, the connected space beyond must be derived from its connected room or antechamber definition.

For the north-facing Science Door:

- The Hall of Discovery must be visible when the Science Door is open.
- The visible Hall of Discovery should contain recognizable science antechamber identity.
- The Hall of Discovery should not be replaced by a generic observatory, library, laboratory, or fantasy room.
- Hall of Discovery topology should be preserved where visible.

### Stations

No formal Great Hall stations are defined yet.

### Compliance Checklist

A north-facing Great Hall render is compliant only if:

- The viewer is inside the Great Hall, near the geometric center, on the Great Knowledge Compass.
- The image faces north.
- The Science Door is the centered or near-centered primary doorway.
- The History Door is left-side if visible.
- The Philosophy Door is right-side if visible.
- No more than 4 doors are visible; 2–3 is preferred.
- The full set of eight openings is not shown.
- The South Foundational Door is not visible in a standard north-facing render.
- The Great Knowledge Compass is partially visible.
- The Palace Sigil reads as an eight-spoked helm/wheel, not generic compass art.
- Domain medallions and door tracks support the navigation system.
- If the Science Door is open, the connected Hall of Discovery is recognizable.
- No unrelated symbolic doors, invented labels, extra levels, cathedral nave, throne-room elements, or generic fantasy hub substitutions dominate.

### Non-Canonical Mistakes to Avoid

Showing all eight doors, placing the wrong door at north, making Science not the focal direction in a north-facing view, showing Foundational Door in front of the viewer, replacing the Hall of Discovery with a generic room, using a generic compass rose instead of the Palace Sigil / Great Knowledge Compass system, adding extra doors, creating a cathedral nave, throne room, museum rotunda, palace lobby, or overhead map-like view, and using invented symbols that obscure domain identity.

## Hall of Discovery

### Purpose

The Hall of Discovery is the antechamber of the Science Realm. It introduces Astronomy, Biology, and Logic and represents inquiry before specialization.

### Connections

- South: Science Door → Great Hall
- North: Astronomy Door
- West: Biology Door
- East: Logic Door

### Required Features

The Hall of Discovery should include the Map of Understanding, Compass Rose of Discovery, Celestial Vault, Eight Alcoves of Discovery, and integrated handcrafted scientific symbolism.

The Celestial Vault may include constellations, planetary paths, lunar cycles, seasonal markers, astronomical symbols, and scientific inscriptions.

### Canonical Visual Specification

- The Hall of Discovery is a science antechamber, not the full Science Realm.
- It should preserve its four-door compass topology.
- The Map of Understanding and Compass Rose of Discovery should anchor the room.
- The Celestial Vault is overhead.
- Alcoves are integrated into walls and must not become freestanding kiosks.
- Astronomy, Biology, and Logic cues may appear where appropriate.

### Non-Canonical Mistakes to Avoid

The Star Whale is not canonical. Alcoves are architectural recesses built into perimeter walls, not freestanding displays, kiosks, islands, detached structures, or furniture placed in the center.

## Arts Antechamber

### Purpose

The Arts Antechamber is the transitional room between the Great Hall and the Arts Realm. It introduces making, beauty, image, performance, music, craft, color, writing, and expression. It is not the full Arts Realm.

### Door Rules

- North wall: Music Door
- East wall: Writing Door
- South wall: Visual Door
- West wall: Great Hall Door

### Required Features

Required features include carved wood display panels, framed sketches or studies, small sculptures, pigments or paint bowls, parchment studies, musical instruments as secondary details when not facing Music Door, masks or theatrical objects, textiles or banners, warm lantern light, benches or worktables, and four canonical doors.

### Canonical Visual Specification

- The Arts Antechamber is a warm human-scaled threshold room.
- It introduces the Arts Realm without becoming the full realm.
- The primary visible door should match the facing direction.
- Do not show all four doors in a standard rendering unless a map, diagram, or special overview is explicitly requested.

### Non-Canonical Mistakes to Avoid

Do not render it as a full museum, theater, or workshop. Do not show all four doors in a standard rendering unless a map, diagram, or special overview is explicitly requested.

## Media Antechamber

### Purpose

The Media Antechamber is the transitional room between the Great Hall and the Media Realm. It is a four-door orientation room for recorded and shared experience.

It offers three primary media paths:

- Movie Theater
- Audio Theater
- Physical Archive Index

Media in The Great Citadel is not digital content, but preserved experience: images, sounds, stories, records, and references held in physical form.

### Door Rules

- North wall: Movie Theater Door
- East wall: Great Hall Door
- South wall: Physical Archive Index Door
- West wall: Audio Theater Door

### Required Features

Required features include carved wood media panels, framed story panels, projection-lantern or camera-obscura-like devices, acoustic horns or resonance bowls, catalog drawers, archive labels, parchment reference slips, warm lantern light, benches or listening seats, brass mechanisms, shelves of media records, and symbols for image, sound, and archive.

### Canonical Visual Specification

- The Media Antechamber is ancient, handcrafted, archival, and physical.
- It is not digital and should not use screens.
- The primary visible door should match the facing direction.
- Do not show all four doors in a standard rendering unless a map, diagram, or special overview is explicitly requested.

### Non-Canonical Mistakes to Avoid

Do not make it look modern. Do not show all four doors in a standard rendering unless a map, diagram, or special overview is explicitly requested. No televisions, digital screens, neon, or modern media-center elements.

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

# 19. Symbols and Floor Systems

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

# 20. Current Canonical Status

Canonical world name: The Great Citadel

Active Codex: Codex v2.2 — Render Compliance Edition

Current rooms and antechambers:

1. Entry Hall
2. Garden
3. Small Library
4. Foundational Door
5. Great Hall
6. Hall of Discovery
7. Media Antechamber
8. History Antechamber
9. Philosophy Antechamber
10. Arts Antechamber
11. Personal Antechamber
12. Inventor's Antechamber

Current defined stations:

1. Small Library — Instruction Manual Station
2. Garden — Buddha Statue Station

Rejected or non-canonical concepts:

- The Star Whale is not canonical.
- A standard Small Library rendering with an open door is non-canonical unless intentionally using the open-door connection rule.
- A Great Hall rendering that shows all eight primary openings at once is non-canonical.
- A Garden standard rendering with visible buildings is non-canonical.
- A west-facing Garden rendering with the Buddha statue on the left side is non-canonical.
- An east-facing Garden rendering showing the Buddha statue is non-canonical.
- An Arts Antechamber standard rendering that shows all four doors at once is non-canonical unless explicitly requested as a map, diagram, or special overview.
- A Media Antechamber standard rendering that shows all four doors at once is non-canonical unless explicitly requested as a map, diagram, or special overview.
- An open doorway that shows the connected room from a contradictory or unrelated perspective is non-canonical.
- An open doorway that shows a generic connected room instead of the connected room's Codex-derived identity is non-canonical.
- An open-door view that violates connected-room topology is non-canonical.
- Furniture or decorations blocking canonical navigational paths is non-canonical.
- A visible station disappearing from a doorway view when its canonical location is visible is non-canonical.
- A station dominating a doorway view when the user did not request a station render is non-canonical.
- A Codex map using modern digital UI styling is non-canonical unless explicitly requested as a special alternate style.
- A render that ignores its compliance checklist is non-canonical.
- A high-fidelity render produced without requirement extraction is procedurally incomplete.
- A render that uses generic fantasy inference over explicit Codex specification is non-canonical.
- A correction re-render requested without user approval after a failed audit is procedurally non-canonical.

---

# 21. v2.2 Change Summary

Codex v2.2 incorporates render-compliance workflow refinements discovered through Entry Hall and Great Hall render testing, plus user-approval control before correction re-renders.

Changes from v2.1:

1. Adds Codex as Specification Protocol.
2. Adds Pre-Render Requirement Extraction Protocol.
3. Adds Strict Prompt Disclosure Protocol.
4. Adds Render Compliance Checklist Protocol.
5. Adds Post-Render Compliance Audit Protocol.
6. Adds Correction Iteration Protocol.
7. Adds User Approval Before Re-Render Protocol.
8. Adds Canonical Visual Reference Protocol.
9. Adds Non-Canonical Exclusion Expansion Protocol.
10. Adds Canonical Visual Specification Standard.
11. Expands the Room Section Template to include Canonical Visual Specification and Compliance Checklist.
12. Adds Codex Compliance Render Workflow.
13. Adds Startup Checklist items 13–19 for high-fidelity rendering and user-approved rerendering.
14. Adds detailed Canonical Visual Specification and Compliance Checklist sections for the Entry Hall, Garden, Small Library, Foundational Door, Great Hall, Hall of Discovery, Arts Antechamber, and Media Antechamber.
15. Strengthens north-facing Great Hall requirements: Science Door centered, History left when visible, Philosophy right when visible, Foundational Door hidden behind viewer, no all-door panorama, and open Science Door must derive from Hall of Discovery.
16. Clarifies that user-approved renders may become canonical visual references but do not override written Codex.
17. Clarifies that negative constraints are active canon constraints, not optional notes.
18. Requires explicit user approval before any correction image-generation request after a failed compliance audit.

End of Codex v2.2 — Render Compliance Edition.
