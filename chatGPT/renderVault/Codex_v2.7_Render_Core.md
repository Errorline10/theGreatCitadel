# Codex v2.7 — Render Core

Project: The Great Citadel
Version: v2.7
Role: Rendering rules and post-render audit rules.
Supersedes: /chatGPT/renderVault/Codex_v2.6_Render_Core.md

---

# General Render Block

Render in the visual language of The Great Citadel. Use visitor perspective unless the request is explicitly for a map, diagram, station, or special-case render. Map renders use 1:1. Standard room renders use 16:9. Preserve canonical door topology, connected-room derivation, navigational paths, direct physical attachment relationships, and topology separation relationships.

---

# Rendering Rules

The viewer faces the requested compass direction. The room does not rotate.

Directly attached spaces must remain directly attached.

Non-adjacent spaces must remain non-adjacent.

A render or map must not invent contact between spaces that the Codex does not connect.

---

# Garden-Entry Hall Render Rule

The Garden connects only to Entry Hall.

The Garden doorway opens immediately into the Entry Hall doorway.

No intermediate space exists between Garden and Entry Hall.

---

# Garden Topology Separation Render Rule

Whenever the Garden appears in a map or diagram, the prompt must explicitly prohibit any visual, doorway, path, shared wall, shared boundary, label-line, or architectural connection between Garden and Media Antechamber.

Whenever the Garden appears in a map or diagram, the prompt must explicitly prohibit any visual, doorway, path, shared wall, shared boundary, label-line, or architectural connection between Garden and Great Hall.

For maps, Media Antechamber must be described as west of Great Hall, not adjacent to Garden.

For maps, Garden and Media Antechamber must be separated by empty map space unless a future Codex release explicitly defines a canonical connection.

---

# Render Stack

For maps, use the Canonical Map Render Block from Map Core plus the Topology Separation Rule from Map Core.

---

# Render Compliance Workflow

For high-fidelity renders, use requirement extraction, compliance checklist, strict render prompt when useful, prompt approval, image generation, post-render compliance audit, and user approval before correction re-render.

Before any Citadel image is generated, print the full compiled prompt and ask: “Is this the correct prompt?”

---

# Map Render Audit Rule

After a map render is produced, audit it against Map Core.

A map fails if it includes non-canonical room connections, Garden detached from Entry Hall, a gap or intermediate structure between Garden and Entry Hall, contact between Garden and Media Antechamber, contact between Garden and Great Hall, missing primary spine, missing fixed compass orientation, or Great Hall openings not placed at exact 45-degree bearings.

End of Codex v2.7 — Render Core.
