# Codex v3.1 — Render Core

Project: The Great Citadel
Version: v3.1
Role: Rendering rules, prompt compilation, image-generation approval gate, exterior render workflow, 360 panorama normalization reference, and post-render audit rules.
Supersedes: /chatGPT/renderVault/Codex_v3.0_Render_Core.md

---

# General Render Block

Render in the visual language of The Great Citadel. Use visitor perspective unless the request is explicitly for a map, diagram, station, 360 panorama, blueprint, door render, exterior overview, or special-case render. Map renders use 1:1. Standard room renders use 16:9. Exterior overview renders use 16:9 unless otherwise specified. 360 equirectangular room and exterior references use 2:1 and must follow the 360 Panorama Compass Normalization Rule from Render Continuity Rules.

---

# Rendering Rules

The viewer faces the requested compass direction. The room or exterior structure does not rotate.

Directly attached spaces must remain directly attached.

Non-adjacent spaces must remain non-adjacent.

A render, map, blueprint, 360 panorama, door render, or exterior render must not invent contact between spaces that the Codex does not connect.

When approved visual reference images exist, they may guide appearance and continuity but may not override topology, compass bearings, door count, door placement, exterior structural rules, direct adjacency, non-adjacency, or 360 compass normalization.

---

# Render Stack

For maps, use Map Core.

For standard room renders, use Room Index, Room Render Definitions, Render Core, Render Continuity Rules, and Image Reference Index when available.

For exterior renders, use Exterior Index, Map Core, Render Core, Render Continuity Rules, and Image Reference Index when available.

For 360 panoramas, use Render Continuity Rules as the controlling source for compass normalization.

---

# Render Compliance Workflow

For high-fidelity renders, use requirement extraction, image-reference lookup, reference retrieval verification, compliance checklist, strict render prompt when useful, prompt approval, image generation, post-render compliance audit, and user approval before correction re-render.

Before any Citadel image is generated, print the full compiled prompt and ask: “Is this the correct prompt?”

---

# Exterior Render Audit Rule

An exterior render fails if it omits the rocky mountain peak, omits distant mountains, makes the Citadel city-sized instead of medium-sized, omits the main north dome, omits the eight smaller domes, shows detached structures, shows hallways or connector corridors between exterior masses, omits the south Entry Hall exterior mass, detaches the Garden from the Entry Hall exterior mass, places the Garden anywhere except west of Entry Hall, omits the bridge, hides either end of the bridge, places the bridge anywhere except southwest, omits the landing platform, places the landing platform anywhere except southwest of the Citadel, creates multiple landing platforms, or turns the landing platform into a large airport.

---

# 360 Render Audit Rule

After a 360 room or exterior reference is produced, audit it against Room Index, Exterior Index when applicable, Room Render Definitions, Map Core, and Render Continuity Rules.

A 360 reference fails if it changes canonical topology, places doors or features on wrong compass bearings, introduces non-canonical exits, contradicts direct adjacency, contradicts non-adjacency, omits required major identity features, or violates the 360 Panorama Compass Normalization Rule.

---

# Door Render Audit Rule

A door render fails if it shows the wrong destination room, suggests an intermediate corridor where none exists, invents extra doors or passageways, contradicts destination-room visual canon, or weakens direct doorway continuity.

End of Codex v3.1 — Render Core.
