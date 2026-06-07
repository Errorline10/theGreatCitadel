# Codex v3.2 — Room Render Definitions

Project: The Great Citadel
Version: v3.2
Role: Room descriptions, room visual identity, room render specifications, station definitions, compliance checklists, connected-room view derivation, viewer placement, and non-canonical render mistake lists.
Supersedes: /chatGPT/roomVault/Codex_v3.1_Room_Render_Definitions.md
Source lineage: /chatGPT/codexVault/Codex_v2.4_Canon_Render_Rooms.md

---

# General Room Render Rule

Render in the visual language of The Great Citadel. Use visitor perspective unless the request is explicitly for a map, diagram, station, 360 panorama, blueprint, door render, exterior overview, or special-case render. Use ancient, warm, lived-in, human-scaled Citadel architecture. Default standard room renders use 16:9 horizontal format. The viewer rotates; the room does not. Preserve canonical door topology, open-door connected-room derivation, navigational paths, direct physical attachment relationships, topology separation relationships, and visible stations where applicable.

Standard room renderings show only the forward hemisphere unless the user asks for a map, diagram, overview, 360 panorama, blueprint, door render, exterior overview, or special reference view.

All 360 room panoramas must follow the 360 Panorama Compass Normalization Rule in Render Continuity Rules.

---

# Viewer Position and Orientation Rule

Unless explicitly overridden by the user, all Citadel renders use the Default Observation Position.

The viewer stands at the true geometric center of the room or location.

The viewer faces canonical North.

For standard room renders, the camera is positioned at the center of the room and faces North by default. If the user requests another direction, only the viewer rotates. The room does not rotate.

For 360 panorama renders, the panorama capture point must be located at the true geometric center of the room. The camera position remains fixed at the room center. Only the panorama view rotates around the fixed position.

The room center must not be shifted to hide, emphasize, enlarge, or reduce the apparent importance of a doorway, station, feature, room connection, or compass bearing unless explicitly requested by the user.

The user may explicitly request another observation point. When an override is requested, the prompt compiler must describe the custom observation position before generation.

---

# Connected Room View Derivation Rule

When a render contains an open canonical doorway and the destination room is visible, the render compiler must derive the visible portion of the destination room from the destination room's canonical Room Render Definition, Room Index, and applicable Codex rules.

The compiled render prompt must not use generic phrases such as: "the open door reveals the next room," "a glimpse of the connected room," "the room beyond," or "another chamber beyond the doorway."

Instead, the prompt must include a concise canonical description of what is visible through the doorway.

Connected-room descriptions must be derived from the destination room's canonical definition rather than invented ad hoc.

The destination room remains secondary to the source room unless the request explicitly focuses on the doorway view.

This rule applies to standard room renders, door renders, station renders, exterior-to-interior doorway views, interior-to-exterior doorway views, and 360 panoramas when doorways are visible.

The rule does not override topology, compass orientation, adjacency rules, door count limits, or destination room canon.

---

# No Overlay / No Text Rule

No rendered Citadel image may include overlays, labels, arrows, compass markings, UI elements, captions, signs added for explanation, or words placed on top of the image unless the user explicitly asks for them.

This applies to standard room renders, 360 panoramas, maps, blueprints, door renders, exterior renders, station renders, and reference images.

For 360 images, compass normalization must be handled by composition and prompt rules only, not by visible text, arrows, labels, compass graphics, or overlay elements.

In-world signs that are part of the canonical room may appear only when they are natural architectural details and not explanatory overlays.

---

# Entry Hall

Purpose: The Entry Hall is the southernmost entrance and first threshold space of The Great Citadel. It welcomes the visitor and guides them inward.

Connections: North Door -> Small Library; South Door -> Outside / Arrival; West Door -> Garden.

The Entry Hall is a narrow welcoming passage, not a hub. It should feel longer than wide, cozy, ancient, lived-in, cared for, practical, safe, and inviting.

Required features: side tables, coat hooks, cloaks or jackets, travel bags, warm lantern light, wood-softened stone architecture, plants/vines/moss where appropriate, worn stone floor, and a clear forward path.

North-facing visual specification: Viewer stands at the true geometric center facing north. North Door is centered or near-centered ahead and open by default. Small Library is visible beyond the North Door and must read as a compact study room. West Door is visible on the left wall because west is left when facing north. West Door reads as a secondary doorway to the Garden. South Door is behind the viewer and not visible.

Open North Door derivation: visible bookshelves, reading tables, lecterns, maps, writing tools, lantern-lit study areas, introductory collections, historical records, and scholarly materials from the Small Library.

Open West Door derivation: visible vine-covered stone boundary walls, warm daylight, raked sand, stacked Zen stones, modest plants, lanterns or garden lights, and calm meditative Garden atmosphere.

---

# Garden

Purpose: The Garden is a meditation branch space connected to the Entry Hall.

Connection: Entry Hall West Door -> Garden East Door -> Garden.

Exactly one canonical door: east-wall door back to the Entry Hall.

Required features: old vine-covered stone boundary walls, open sky, warm daylight, distant mountains, a few tiny faraway steampunk blimps, dry raked sand Zen garden, stacked Zen stones, modest plants, lanterns or garden lights, and exactly one small Buddha statue in the northwest corner.

The Garden should feel open, airy, happy, dry, bright, calm, meditative, restorative, human-scaled, cared for, lightly cultivated, and spiritually quiet.

Buddha visibility rules: one Buddha only, fixed in northwest corner. In a west-facing render it should appear on the right side when visible. In an east-facing render it should not be visible under the Forward Hemisphere Rule. In a 360 panorama or exterior overview, it may be visible because the full room or exterior location is intentionally captured.

Station: Garden — Buddha Statue Station. Viewer stands close in front of the northwest-corner Buddha statue, facing it at eye level. Statue fills most of the image; surrounding Garden is secondary context.

---

# Small Library

Purpose: The Small Library is the final preparatory room before entering the Great Hall.

Connection: Entry Hall -> Small Library -> Foundational Door -> Great Hall.

Exactly two canonical doors: South Door -> Entry Hall. North Door -> Foundational Door / Great Hall.

Required features: Instruction Manual and Guest Book, Codex as reference source, introductory collections, maps, symbol references, historical records, reading tables, lecterns, shelves, reference books, writing tools, map tables, and lamps or lanterns.

Station: Small Library — Instruction Manual Station.

---

# Great Hall

Purpose: The Great Hall is the central navigation chamber of The Great Citadel and symbolic heart of exploration.

Eight primary compass-fixed openings: North Science Door; Northeast Philosophy Door; East Arts Door; Southeast Personal Door; South Foundational Door; Southwest Inventor's Door; West Media Door; Northwest History Door.

Required features: Palace Sigil, Great Knowledge Compass, domain medallions, door tracks, ancient stonework, brass mechanisms, and banners where appropriate.

Viewer stands at the true geometric center upon the Great Knowledge Compass. Only the forward half of the chamber should be visible in standard non-360 renders. Visible doors: minimum 1, preferred 2-3, maximum 4. A standard rendering that reveals all eight doors is non-canonical unless explicitly requested as a 360 panorama or special reference asset.

---

# Hall of Discovery

The Hall of Discovery is the antechamber of the Science Realm.

Connections: South Science Door -> Great Hall; North Astronomy Door; West Biology Door; East Logic Door.

Required features: Map of Understanding, Compass Rose of Discovery, Celestial Vault, Eight Alcoves of Discovery, and integrated handcrafted scientific symbolism.

Default viewer position: true geometric center of the room.

Default viewer orientation: facing canonical North.

Standard north-facing render: Astronomy Door is centered ahead. Biology Door may appear on the left wall. Logic Door may appear on the right wall. Science Door is behind the viewer and should not be visible unless the view is wide enough to show side/rear context or the request is a 360 panorama.

360 panorama render: capture point must be true geometric center. All four canonical doors must appear on correct compass bearings. No extra door, passage, arch, balcony exit, hidden opening, service corridor, stair exit, or implied navigable opening may appear.

Hall of Discovery door details:

North Astronomy Door: decorated with celestial motifs, brass star maps, constellation patterns, astrolabe details, and observation symbolism. The open doorway reveals astronomical instruments, observation materials, star charts, telescopic or sky-study themes, and dark blue celestial lighting accents.

West Biology Door: decorated with botanical and life-study motifs, carved leaves, roots, animals, anatomical and living-system symbols. The open doorway reveals botanical study tables, natural-study collections, biological illustrations, specimens, modest greenery, and observation tools.

East Logic Door: decorated with geometric and symbolic patterns, mathematical diagrams, ordered visual structures, and reasoning motifs. The open doorway reveals analytical workspaces, structured diagrams, symbolic boards, careful shelves, and a calm ordered study environment.

South Science Door: the main return doorway to the Great Hall. The open doorway reveals part of the Great Hall: portions of the Great Knowledge Compass, ancient stone architecture, brass mechanisms, banners, domain medallions, and the central navigation character of the Citadel.

---

End of Codex v3.2 — Room Render Definitions.