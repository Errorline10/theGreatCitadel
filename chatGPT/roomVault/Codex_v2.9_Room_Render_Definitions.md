# Codex v2.9 — Room Render Definitions

Project: The Great Citadel
Version: v2.9
Role: Room descriptions, room visual identity, room render specifications, station definitions, compliance checklists, and non-canonical render mistake lists.
Supersedes: /chatGPT/roomVault/Codex_v2.8_Room_Render_Definitions.md
Source lineage: /chatGPT/codexVault/Codex_v2.4_Canon_Render_Rooms.md

---

# Integration Rule

This file restores room-level visual canon and render blocks that existed in the v2.4 source lineage and supplements the v2.9 modular structure.

This file supplements, but does not override, active v2.9 topology, direct-adjacency, non-adjacency, Garden separation, map, prompt approval, runtime binding, or image-reference retrieval rules.

Where this file adds room visual identity, required features, station definitions, facing-direction guidance, compliance checks, or non-canonical mistake lists without conflicting with v2.9, those details are active room-render canon.

---

# General Room Render Rule

Render in the visual language of The Great Citadel. Use visitor perspective unless the request is explicitly for a map, diagram, station, 360 panorama, blueprint, door render, or special-case render. Use ancient, warm, lived-in, human-scaled Citadel architecture. Use wood-softened stone, practical detail, coherent compass-fixed architecture, and physically plausible spatial continuity. Default standard room renders use 16:9 horizontal format. The viewer rotates; the room does not. Use only the requested room, requested facing direction, and canonically appropriate visible features. Avoid non-canonical additions. Preserve canonical door topology, open-door connected-room derivation, navigational paths, direct physical attachment relationships, topology separation relationships, and visible stations where applicable.

Standard room renderings place the viewer inside the room, normally at or near the geometric center unless a room-specific rule, station rule, reference image, or user request overrides this.

The viewer faces the requested compass direction. The room does not rotate.

Every room can be rendered facing North, Northeast, East, Southeast, South, Southwest, West, or Northwest unless otherwise specified.

Standard room renderings show only the forward hemisphere unless the user asks for a map, diagram, overview, 360 panorama, blueprint, door render, or special reference view.

Doors, stations, statues, major room features, and compass-based architecture remain fixed to canonical locations.

If an open doorway is visible, the connected room or space should be visible beyond it when canonically known, preserving spatial and directional continuity. When a door-render reference exists, use it as the preferred visual source for the framed view beyond the doorway.

Connected rooms visible through open doors must be derived from their Codex definitions and must not be generic fantasy substitutions.

Canonical circulation paths and navigational routes take precedence over furniture and decoration.

Standard room renders use 16:9. Map renders use 1:1. 360 room references use 2:1 equirectangular format.

---

# Entry Hall

Purpose: The Entry Hall is the southernmost entrance and first threshold space of The Great Citadel. It welcomes the visitor and guides them inward.

Connections:

North Door -> Small Library
South Door -> Outside / Arrival
West Door -> Garden

The Entry Hall is a narrow welcoming passage, not a hub. It should feel longer than wide, cozy, ancient, lived-in, cared for, practical, safe, and inviting.

Required features: side tables, coat hooks, cloaks or jackets, travel bags, warm lantern light, wood-softened stone architecture, plants/vines/moss where appropriate, worn stone floor, and a clear forward path.

North-facing visual specification:

Viewer stands near the center facing north. North Door is centered or near-centered ahead and open by default. Small Library is visible beyond the North Door and must read as a compact study room. West Door is visible on the left wall because west is left when facing north. West Door reads as a secondary doorway to the Garden. South Door is behind the viewer and not visible.

Compliance checklist:

- Narrow, human-scaled north-south passage.
- North Door primary and open by default.
- Small Library visible and recognizable beyond.
- West Garden Door visible on left wall.
- South Door not visible.
- Exactly three canonical doors exist.
- Central path clear.
- Side tables, coats, bags, lanterns, plants/vines, wood, stone, and lived-in details present.
- Not grand, hub-like, cathedral-like, palace-like, or ceremonial.

Non-canonical mistakes: broad ceremonial chamber, grand scale, more than three doors, Garden door anywhere except west, hub-like layout, open north door without Small Library visible, missing west-wall Garden door in a north-facing render, generic library beyond, furniture blocking circulation.

---

# Garden

Purpose: The Garden is a meditation branch space connected to the Entry Hall.

Connection: Entry Hall West Door -> Garden East Door -> Garden.

Exactly one canonical door: east-wall door back to the Entry Hall.

Required features: old vine-covered stone boundary walls, open sky, warm daylight, distant mountains, a few tiny faraway steampunk blimps, dry raked sand Zen garden, stacked Zen stones, modest plants, lanterns or garden lights, and exactly one small Buddha statue in the northwest corner.

The Garden should feel open, airy, happy, dry, bright, calm, meditative, restorative, human-scaled, cared for, lightly cultivated, and spiritually quiet.

Buddha visibility rules: one Buddha only, fixed in northwest corner. In a west-facing render it should appear on the right side when visible. In an east-facing render it should not be visible under the Forward Hemisphere Rule. In a 360 panorama it may be visible because the full room is intentionally captured.

Station: Garden — Buddha Statue Station. Viewer stands close in front of the northwest-corner Buddha statue, facing it at eye level. Statue fills most of the image; surrounding Garden is secondary context.

Non-canonical mistakes: buildings, wet ground, extra doors, missing Zen garden or stones, more than one Buddha, oversized Buddha, Buddha in wrong corner, dominant blimps.

---

# Small Library

Purpose: The Small Library is the final preparatory room before entering the Great Hall.

Connection: Entry Hall -> Small Library -> Foundational Door -> Great Hall.

Exactly two canonical doors:

South Door -> Entry Hall
North Door -> Foundational Door / Great Hall

The layout is linear north-south. A clear north-south navigational path must remain visible and unobstructed.

Required features: Instruction Manual and Guest Book, Codex as reference source, introductory collections, maps, symbol references, historical records, reading tables, lecterns, shelves, reference books, writing tools, map tables, and lamps or lanterns.

The large prominent display book is the combined Instruction Manual and Guest Book. It sits in the northeast corner and must not block the north door. The Codex may appear as a protected reference volume, shelved master text, smaller lectern book, or curated reference source.

Station: Small Library — Instruction Manual Station. Viewer stands just in front of the large Instruction Manual and Guest Book in the northeast corner, looking downward. The book is the primary object and occupies most of the frame.

Non-canonical mistakes: extra exits, hub-like room, display book in center, book blocking north door, treating display book as Codex, grand scale, reading table blocking path, shelves replacing a canonical door.

---

# Foundational Door

The Foundational Door connects the Small Library to the Great Hall.

Connection:

Small Library -> Foundational Door -> Great Hall
Great Hall -> Foundational Door -> Small Library -> Entry Hall

It is one of the eight primary openings of the Great Hall and the exception to the Antechamber Connection Principle. It leads between the Great Hall and the Foundations, not to a realm antechamber.

It should communicate threshold, return, and foundation. It may include old stone, carved wood, brass or bronze fittings, foundational symbols, threshold markings, Palace Sigil, or root/return motifs.

Open views must preserve connected-room continuity.

---

# Great Hall

Purpose: The Great Hall is the central navigation chamber of The Great Citadel and symbolic heart of exploration.

Eight primary compass-fixed openings:

North: Science Door -> Hall of Discovery -> Science Realm
Northeast: Philosophy Door -> Philosophy Antechamber -> Philosophy Realm
East: Arts Door -> Arts Antechamber -> Arts Realm
Southeast: Personal Door -> Personal Antechamber -> Personal Realm
South: Foundational Door -> Small Library -> Entry Hall
Southwest: Inventor's Door -> Inventor's Antechamber -> Inventor's Realm
West: Media Door -> Media Antechamber -> Media Realm
Northwest: History Door -> History Antechamber -> History Realm

Required features: Palace Sigil, Great Knowledge Compass, domain medallions, door tracks, ancient stonework, brass mechanisms, and banners where appropriate.

Viewer stands at or near the geometric center upon the Great Knowledge Compass. Only the forward half of the chamber should be visible. Visible doors: minimum 1, preferred 2-3, maximum 4. A rendering that reveals all eight doors is non-canonical unless explicitly requested as a 360 panorama or special reference asset.

North-facing visual specification:

Viewer stands at or near the geometric center upon the Great Knowledge Compass and faces north. The North Science Door is centered or near-centered ahead and is the primary focal doorway. The Northwest History Door may appear to the left side. The Northeast Philosophy Door may appear to the right side. The South Foundational Door is behind the viewer and not visible. The Great Knowledge Compass is partially visible, not a full overhead map. The Palace Sigil should read as a simple eight-spoked ship's helm or wheel.

If the Science Door is open, the visible space beyond must derive from the Hall of Discovery definition.

Compliance checklist:

- Viewer inside Great Hall, near center, on Great Knowledge Compass.
- Facing direction honored.
- Primary facing-direction door centered or near-centered when one exists.
- No more than 4 visible doors in standard room renders; 2-3 preferred.
- Full set of eight openings not shown in standard room renders.
- Opposite-direction door not visible in standard room renders.
- Great Knowledge Compass partially visible.
- Palace Sigil reads as eight-spoked helm/wheel.
- Open doors show connected rooms only when canonically connected.

Non-canonical mistakes: showing all eight doors in standard renders, wrong door at requested facing direction, generic room beyond open doors, generic compass rose, extra doors, cathedral nave, throne room, museum rotunda, palace lobby, overhead map view, invented symbols that obscure domain identity.

---

# Hall of Discovery

The Hall of Discovery is the antechamber of the Science Realm.

Connections:

South: Science Door -> Great Hall
North: Astronomy Door
West: Biology Door
East: Logic Door

Required features: Map of Understanding, Compass Rose of Discovery, Celestial Vault, Eight Alcoves of Discovery, and integrated handcrafted scientific symbolism.

The Celestial Vault may include constellations, planetary paths, lunar cycles, seasonal markers, astronomical symbols, and scientific inscriptions.

The Star Whale is not canonical. Alcoves are architectural recesses built into perimeter walls, not freestanding kiosks, islands, or center furniture.

---

# Active Stations

1. Small Library — Instruction Manual Station
2. Garden — Buddha Statue Station

End of Codex v2.9 — Room Render Definitions.
