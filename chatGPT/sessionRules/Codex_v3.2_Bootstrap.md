# Codex v3.2 — Bootstrap

Project: The Great Citadel
Version: v3.2
Role: Bootstrap, manifest, initialization order, protocol activation, runtime Codex binding, prompt approval, save rules, exterior loading, reference-image handling, render workflow enforcement, and 360 panorama compass normalization.
Supersedes: /chatGPT/sessionRules/Codex_v3.1_Bootstrap.md

---

# Required Release Manifest

A complete v3.2 Codex release contains these required files:

1. /chatGPT/sessionRules/Codex_v3.2_Bootstrap.md
2. /chatGPT/codexVault/Codex_v3.2_Canon_Core.md
3. /chatGPT/roomVault/Codex_v3.2_Room_Index.md
4. /chatGPT/roomVault/Codex_v3.2_Room_Render_Definitions.md
5. /chatGPT/mapVault/Codex_v3.2_Map_Core.md
6. /chatGPT/renderVault/Codex_v3.2_Render_Core.md
7. /chatGPT/renderVault/Codex_v3.2_Render_Continuity_Rules.md
8. /chatGPT/referenceVault/Codex_v3.2_Image_Reference_Index.md
9. /chatGPT/exteriorVault/Codex_v3.2_Exterior_Index.md

---

# Repository Structure Rule

Bootstrap files belong in /chatGPT/sessionRules/. Canon Core files belong in /chatGPT/codexVault/. Room Index and Room Render Definition files belong in /chatGPT/roomVault/. Map Core files belong in /chatGPT/mapVault/. Render Core and Render Continuity files belong in /chatGPT/renderVault/. Image Reference Index files belong in /chatGPT/referenceVault/. Exterior Index files belong in /chatGPT/exteriorVault/. Reference images belong in /chatGPT/referenceVault/images/.

---

# Initialization Order

1. Load Bootstrap.
2. Load Canon Core.
3. Load Room Index.
4. Load Room Render Definitions.
5. Load Map Core.
6. Load Render Core.
7. Load Render Continuity Rules.
8. Load Image Reference Index.
9. Load Exterior Index.
10. Confirm all files say Version: v3.2.
11. Activate all rules, protocols, definitions, checklists, and canonical constraints.
12. Bind future Citadel requests to the active Codex registry.
13. Report initialization status.

---

# Runtime Codex Binding Rule

All user requests related to The Great Citadel must be interpreted through the active Codex file set. Do not answer, render, map, diagram, revise, or audit Citadel content from generic fantasy assumptions when an active Codex release is loaded.

---

# Mandatory Codex Compilation Rule

Any Citadel render, map, diagram, room view, exterior view, station view, audit, revision, canon update, reference-image request, 360 panorama, blueprint, or door render must be compiled into a Codex-grounded execution prompt before any generation tool is called.

For 360 panorama requests, use Render Continuity Rules as the controlling source for compass normalization.

---

# Prompt Approval Gate

Before any Citadel image is generated, print the full compiled image prompt in chat and ask: “Is this the correct prompt?” Do not call the image-generation tool until the user approves the prompt.

---

# Citadel Render Request Intercept Rule

Any user request that would generate a Citadel image must be intercepted before image generation.

Trigger phrases include, but are not limited to: render, generate, create image, create panorama, create 360, draw, visualize, blueprint, map, exterior view, station view, and door render.

When a Citadel render request is detected, do not immediately generate an image. Instead: determine render type, load applicable Codex rules, compile the render prompt, display the compiled prompt, display the applicable pre-render compliance checklist, ask “Is this the correct prompt?”, and wait for explicit user approval.

Only after approval may image generation occur.

After generation, run the post-render compliance audit, produce a compliance percentage, produce findings, produce correction recommendations, and produce the recommended GitHub save path when applicable.

This rule overrides default direct-render behavior for Citadel content.

---

# Image Reference Handling Rule

Image reference entries may be used as descriptive continuity metadata. GitHub image paths are optional continuity references, not mandatory context inputs. Do not block a render solely because a reference image path cannot be fetched, unless the user explicitly requests that an actual image reference file be used as input.

Reference image files must still be verified before they are claimed as retrieved or used as actual image inputs.

---

# Source of Truth Rule

The active v3.2 file set is the source of truth for The Great Citadel.

Render Continuity Rules governs 360 references, 360 panorama compass normalization, blueprints, exterior references, door renders, continuity lookups, and visual-reference priority.

Exterior Index governs the Outside of the Citadel, exterior stations, exterior structure, exterior compliance, bridge, landing platform, and exterior render defaults.

---

# Save the Codex to GitHub Rule

When the user says save the Codex to GitHub, publish every required file in the active release manifest for the next version. A GitHub Codex save is incomplete unless all required files are created successfully. Every GitHub Codex save must also update the root README.md in the same save workflow.

---

# Version Matching Rule

All files in a published release must share the same version number. The README active release reference must match the latest published ChatGPT Codex release after each successful GitHub save.

---

# Missing File Handling

If a required file cannot be loaded, report the missing file and do not claim full initialization.

---

# v3.2 Change Summary

Codex v3.2 strengthens render workflow enforcement. It adds explicit render request interception, connected-room view derivation, post-render compliance audit reporting, no-overlay/no-text rendering, central viewer placement, canonical door count preservation, and descriptive-only image reference handling unless an actual reference image is explicitly requested.

End of Codex v3.2 — Bootstrap.