# Codex v3.0 — Render Core

Project: The Great Citadel
Version: v3.0
Role: Rendering rules, prompt compilation, image-generation approval gate, exterior render workflow, and post-render audit rules.
Supersedes: /chatGPT/renderVault/Codex_v2.9_Render_Core.md

---

# General Render Block

Render in the visual language of The Great Citadel. Use visitor perspective unless the request is explicitly for a map, diagram, station, 360 panorama, blueprint, door render, exterior overview, or special-case render. Map renders use 1:1. Standard room renders use 16:9. Exterior overview renders use 16:9 unless otherwise specified. 360 equirectangular room references use 2:1. Preserve canonical door topology, connected-room derivation, exterior topology, navigational paths, direct physical attachment relationships, topology separation relationships, and approved visual-reference continuity when available.

---

# Rendering Rules

The viewer faces the requested compass direction. The room or exterior structure does not rotate.

Directly attached spaces must remain directly attached.

Non-adjacent spaces must remain non-adjacent.

A render, map, blueprint, 360 panorama, door render, or exterior render must not invent contact between spaces that the Codex does not connect.

When approved visual reference images exist, they may guide appearance and continuity but may not override topology, compass bearings, door count, door placement, exterior structural rules, direct adjacency, or non-adjacency.

---

# Garden-Entry Hall Render Rule

The Garden connects only to Entry Hall.

The Garden doorway opens immediately into the Entry Hall doorway.

No intermediate space exists between Garden and Entry Hall.

---

# Garden Topology Separation Render Rule

Whenever the Garden appears in a map, diagram, blueprint, 360 panorama, room render, or exterior render, the prompt must explicitly prohibit any visual, doorway, path, shared wall, shared boundary, label-line, or architectural connection between Garden and Media Antechamber.

Whenever the Garden appears in a map, diagram, blueprint, 360 panorama, room render, or exterior render, the prompt must explicitly prohibit any visual, doorway, path, shared wall, shared boundary, label-line, or architectural connection between Garden and Great Hall.

---

# Render Stack

For maps, use the Canonical Map Render Block from Map Core plus the Topology Separation Rule from Map Core.

For standard room renders, use Room Index, Room Render Definitions, Render Core, Render Continuity Rules, and Image Reference Index when available.

For exterior renders, use Exterior Index, Map Core, Render Core, Render Continuity Rules, and Image Reference Index when available.

For 360 room references, use Room Index, Room Render Definitions, Map Core, Render Core, Render Continuity Rules, and Image Reference Index.

For door renders, use the source room definition, destination room definition, doorway topology, compass direction, and Render Continuity Rules.

---

# Render Compliance Workflow

For high-fidelity renders, use requirement extraction, image-reference lookup, reference retrieval verification, compliance checklist, strict render prompt when useful, prompt approval, image generation, post-render compliance audit, and user approval before correction re-render.

Before any Citadel image is generated, print the full compiled prompt and ask: “Is this the correct prompt?”

---

# Map Render Audit Rule

After a map render is produced, audit it against Map Core.

A map fails if it includes non-canonical room connections, Garden detached from Entry Hall, a gap or intermediate structure between Garden and Entry Hall, contact between Garden and Media Antechamber, contact between Garden and Great Hall, missing primary spine, missing fixed compass orientation, or Great Hall openings not placed at exact 45-degree bearings.

---

# Exterior Render Audit Rule

After an exterior render is produced, audit it against Exterior Index, Map Core, Render Core, and Image Reference Index.

An exterior render fails if it omits the rocky mountain peak, omits the distant mountains, makes the Citadel city-sized instead of medium-sized, omits the main north dome, omits the eight smaller domes, shows detached structures, shows hallways or connector corridors between exterior masses, omits the south Entry Hall exterior mass, detaches the Garden from the Entry Hall exterior mass, places the Garden anywhere except west of Entry Hall, omits the bridge, hides either end of the bridge, places the bridge anywhere except southwest, omits the landing platform, places the landing platform anywhere except southwest of the Citadel, creates multiple landing platforms, or turns the landing platform into a large airport.

---

# 360 Render Audit Rule

After a 360 room reference is produced, audit it against Room Index, Room Render Definitions, Map Core, and Render Continuity Rules.

A 360 room reference fails if it changes the room's canonical door count, places doors on wrong compass walls, introduces non-canonical exits, contradicts direct adjacency, contradicts non-adjacency, omits required major room identity features, or depicts visible connections to rooms that are not canonically connected.

---

# Door Render Audit Rule

After a door render is produced, audit it against the source room, destination room, doorway topology, and compass orientation.

A door render fails if it shows the wrong destination room, suggests an intermediate corridor where none exists, invents extra doors or passageways, contradicts destination-room visual canon, or weakens direct doorway continuity.

End of Codex v3.0 — Render Core.
