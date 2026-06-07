# Codex v3.2 — Render Core

Project: The Great Citadel
Version: v3.2
Role: Rendering rules, prompt compilation, render request interception, image-generation approval gate, exterior render workflow, 360 panorama workflow, post-render audit rules, and compliance reporting.
Supersedes: /chatGPT/renderVault/Codex_v3.1_Render_Core.md

---

# General Render Block

Render in the visual language of The Great Citadel. Use visitor perspective unless the request is explicitly for a map, diagram, station, 360 panorama, blueprint, door render, exterior overview, or special-case render. Map renders use 1:1. Standard room renders use 16:9. Exterior overview renders use 16:9 unless otherwise specified. 360 equirectangular room and exterior references use 2:1 and must follow the 360 Panorama Compass Normalization Rule from Render Continuity Rules.

---

# Rendering Rules

The viewer faces the requested compass direction. If no direction is requested, the viewer faces canonical North.

The default viewer position is the true geometric center of the room or defined station location.

The room or exterior structure does not rotate.

Directly attached spaces must remain directly attached.

Non-adjacent spaces must remain non-adjacent.

A render, map, blueprint, 360 panorama, door render, or exterior render must not invent contact between spaces that the Codex does not connect.

When approved visual reference images exist, they may guide appearance and continuity but may not override topology, compass bearings, door count, door placement, exterior structural rules, direct adjacency, non-adjacency, or 360 compass normalization.

Image reference entries may be used as descriptive continuity metadata. Actual image files are not required context inputs unless the user explicitly asks to use a fetched image reference.

---

# Citadel Render Request Intercept Rule

Any user request that would generate a Citadel image must be intercepted before image generation.

Trigger phrases include, but are not limited to: render, generate, create image, create panorama, create 360, draw, visualize, blueprint, map, exterior view, station view, and door render.

When a Citadel render request is detected, the assistant must not immediately generate an image.

Instead it must:

1. Determine render type.
2. Load applicable Codex rules.
3. Compile the render prompt.
4. Display the compiled prompt.
5. Display the applicable pre-render compliance checklist.
6. Ask: “Is this the correct prompt?”
7. Wait for explicit user approval.

Only after approval may image generation occur.

After generation:

1. Run the post-render compliance audit.
2. Produce compliance percentage.
3. Produce findings.
4. Produce correction recommendations.
5. Produce recommended GitHub save path if applicable.

This rule overrides default direct-render behavior for Citadel content.

---

# Render Workflow Enforcement Rule

Every Citadel render request must complete the full Codex render workflow before image generation.

Applies to standard room renders, 360 panoramas, exterior renders, maps, blueprints, door renders, station renders, and reference images.

Required sequence:

1. Compile Codex-grounded prompt.
2. Display the compiled prompt.
3. Display the relevant pre-render compliance checklist.
4. Ask: “Is this the correct prompt?”
5. Wait for user approval.
6. Generate image only after approval.
7. Perform post-render compliance audit.
8. Report compliance percentage.
9. List findings and corrections.
10. Print recommended GitHub save path when applicable.

No Citadel image generation should bypass this workflow.

---

# 360 Render Workflow Inclusion Rule

All pre-render and post-render rules apply fully to 360 image generation.

Every 360 render must follow prompt compilation before generation, connected-room view derivation for visible open doors, prompt approval before image generation, fixed 360 compass normalization, post-render compliance audit, compliance percentage report, pass/fail finding list, and recommended GitHub save path when the image is a continuity candidate.

360 renders are not exempt from the standard Citadel render workflow.

---

# Pre-Render Checklist Requirement

Before image generation, the assistant must display a checklist covering the relevant render type.

For all renders, include: render type, source room/location, viewer position, viewer facing direction, aspect ratio, canonical door count, visible canonical doors, connected-room derivations, topology constraints, no-overlay/no-text requirements, and post-render audit requirement.

For 360 renders, additionally include: true geometric center capture point, center North, right quarter East, left quarter West, far-left/far-right South seam, no visible compass labels or arrows, and no extra navigable openings.

---

# Render Stack

For maps, use Map Core.

For standard room renders, use Room Index, Room Render Definitions, Render Core, Render Continuity Rules, and Image Reference Index when available.

For exterior renders, use Exterior Index, Map Core, Render Core, Render Continuity Rules, and Image Reference Index when available.

For 360 panoramas, use Render Continuity Rules as the controlling source for compass normalization, plus all pre-render and post-render workflow rules.

---

# Render Compliance Workflow

For high-fidelity renders, use requirement extraction, image-reference metadata lookup, compliance checklist, strict render prompt when useful, prompt approval, image generation, post-render compliance audit, and user approval before correction re-render.

Before any Citadel image is generated, print the full compiled prompt and ask: “Is this the correct prompt?”

---

# Post-Render Compliance Audit Rule

After every Citadel image generation, perform a compliance audit against the active Codex before concluding the render workflow.

The audit must compare the generated image against Canon Core, Room Index, Room Render Definitions, Map Core, Render Core, Render Continuity Rules, and Exterior Index when applicable.

The audit must identify canonical elements correctly represented, missing required elements, incorrect elements, ambiguous elements, potential topology violations, door count violations, overlay/text violations, and compass-orientation violations.

Produce an estimated compliance score expressed as a percentage.

Compliance scale:

100% = Fully compliant.
90–99% = Minor visual deviations only.
75–89% = Moderate deviations requiring correction.
Below 75% = Significant canonical violations.

The compliance report must include compliance percentage, pass/fail status, findings list, and recommended corrections.

If the image is intended as a future continuity reference, display the exact GitHub save path that should be used.

The save-path recommendation does not create, upload, or modify GitHub content. It is a suggested destination only until the user explicitly requests a GitHub save operation.

---

# Exterior Render Audit Rule

An exterior render fails if it omits the rocky mountain peak, omits distant mountains, makes the Citadel city-sized instead of medium-sized, omits the main north dome, omits the eight smaller domes, shows detached structures, shows hallways or connector corridors between exterior masses, omits the south Entry Hall exterior mass, detaches the Garden from the Entry Hall exterior mass, places the Garden anywhere except west of Entry Hall, omits the bridge, hides either end of the bridge, places the bridge anywhere except southwest, omits the landing platform, places the landing platform anywhere except southwest of the Citadel, creates multiple landing platforms, or turns the landing platform into a large airport.

---

# 360 Render Audit Rule

After a 360 room or exterior reference is produced, audit it against Room Index, Exterior Index when applicable, Room Render Definitions, Map Core, and Render Continuity Rules.

A 360 reference fails if it changes canonical topology, places doors or features on wrong compass bearings, introduces non-canonical exits, contradicts direct adjacency, contradicts non-adjacency, omits required major identity features, violates canonical door count, includes overlay text or labels without explicit request, or violates the 360 Panorama Compass Normalization Rule.

---

# Door Render Audit Rule

A door render fails if it shows the wrong destination room, suggests an intermediate corridor where none exists, invents extra doors or passageways, contradicts destination-room visual canon, or weakens direct doorway continuity.

End of Codex v3.2 — Render Core.