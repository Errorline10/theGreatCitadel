# Codex v2.5 — Render Core

Project: The Great Citadel
Version: v2.5
Role: Rendering rules, render prompts, compliance workflow, and post-render audit rules.
Supersedes: Rendering portions of /chatGPT/codexVault/Codex_v2.4_Canon_Render_Rooms.md

---

# General Render Block

Render in the visual language of The Great Citadel. Use visitor perspective unless the request is explicitly for a map, diagram, station, or special-case render. Use ancient, warm, lived-in, human-scaled Citadel architecture. Use wood-softened stone, practical detail, coherent compass-fixed architecture, and physically plausible spatial continuity. Default standard room renders use 16:9 horizontal format. The viewer rotates; the room does not. Use only the requested room, requested facing direction, and canonically appropriate visible features. Avoid non-canonical additions. Preserve canonical door topology, open-door connected-room derivation, navigational paths, and visible stations where applicable.

---

# Rendering Rules

Standard room renderings place the viewer inside the room, normally at or near the geometric center unless a room-specific rule, station rule, or user request overrides this.

The viewer faces the requested compass direction. The room does not rotate.

Every room can be rendered facing North, Northeast, East, Southeast, South, Southwest, West, or Northwest unless otherwise specified.

Standard room renderings show only the forward hemisphere unless the user asks for a map, diagram, overview, or special reference view.

Doors, stations, statues, major room features, and compass-based architecture remain fixed to canonical locations.

If an open doorway is visible, the connected room or space should be visible beyond it when canonically known, preserving spatial and directional continuity.

Connected rooms visible through open doors must be derived from their Codex definitions and must not be generic fantasy substitutions.

Canonical circulation paths and navigational routes take precedence over furniture and decoration.

Standard room renders use 16:9. Map renders use 1:1.

---

# Render Stack

For standard room renders, use:

General Render Block + Room Concise Image Render Prompt + Canonical Visual Specification + User overrides + Non-canonical exclusions.

For maps, use the Canonical Map Render Block from Map Core.

---

# Render Compliance Workflow

For high-fidelity renders, use:

1. Requirement extraction.
2. Compliance checklist.
3. Strict render prompt when useful.
4. Image generation.
5. Post-render compliance audit.
6. User approval before any correction re-render.

---

# User Approval Before Re-Render

When a render fails its compliance audit, do not automatically request another image.

Instead:

1. Complete the audit.
2. List failures.
3. Give an overall compliance assessment.
4. Recommend corrections.
5. Ask: Would you like to try again?

Only request another image after the user approves.

---

# Post-Render Audit Rule

After a render is produced, compare it against the active Codex requirements and identify:

- compliant elements
- missing required elements
- non-canonical additions
- topology failures
- connected-room derivation failures
- navigational-path failures
- station-visibility failures
- symbolic or architectural identity failures

Do not assume a render is canonical merely because it is visually attractive.

---

# Entry Hall North Render Checklist

A north-facing Entry Hall render is compliant only if:

- It shows a narrow, human-scaled north-south passage.
- The North Door is primary and open by default.
- Small Library is visible and recognizable beyond.
- West Garden Door is visible on the left wall.
- South Door is not visible.
- Exactly three canonical doors exist.
- Central path is clear.
- Side tables, coats, bags, lanterns, plants or vines, wood, stone, and lived-in details are present.
- The room is not grand, hub-like, cathedral-like, palace-like, or ceremonial.

---

# Great Hall North Render Checklist

A north-facing Great Hall render is compliant only if:

- Viewer is inside Great Hall, near center, on Great Knowledge Compass.
- Facing north.
- Science Door is centered or near-centered.
- History is left if visible.
- Philosophy is right if visible.
- No more than 4 visible doors; 2-3 preferred.
- Full set of eight openings is not shown.
- South Foundational Door is not visible.
- Great Knowledge Compass is partially visible.
- Palace Sigil reads as eight-spoked helm or wheel.
- If Science Door is open, Hall of Discovery is recognizable.

---

# Non-Canonical Render Mistakes

Avoid: extra doors, generic connected-room substitutions, blocked circulation paths, wrong compass orientation, rooms rotating for convenience, all-eight-door standard Great Hall render, cathedral nave for Great Hall, palace foyer for Entry Hall, modern digital UI maps unless requested, and maps that connect rooms only because they share a bearing.

End of Codex v2.5 — Render Core.
