# Codex v3.0 — Bootstrap

Project: The Great Citadel
Version: v3.0
Role: Bootstrap, manifest, initialization order, protocol activation, runtime Codex binding, prompt approval, save rules, exterior loading, and reference-image retrieval.
Supersedes: /chatGPT/sessionRules/Codex_v2.9_Bootstrap.md

---

# Required Release Manifest

A complete v3.0 Codex release contains these required files:

1. /chatGPT/sessionRules/Codex_v3.0_Bootstrap.md
2. /chatGPT/codexVault/Codex_v3.0_Canon_Core.md
3. /chatGPT/roomVault/Codex_v3.0_Room_Index.md
4. /chatGPT/roomVault/Codex_v3.0_Room_Render_Definitions.md
5. /chatGPT/mapVault/Codex_v3.0_Map_Core.md
6. /chatGPT/renderVault/Codex_v3.0_Render_Core.md
7. /chatGPT/renderVault/Codex_v3.0_Render_Continuity_Rules.md
8. /chatGPT/referenceVault/Codex_v3.0_Image_Reference_Index.md
9. /chatGPT/exteriorVault/Codex_v3.0_Exterior_Index.md

---

# Repository Structure Rule

Bootstrap files belong in /chatGPT/sessionRules/.
Canon Core files belong in /chatGPT/codexVault/.
Room Index and Room Render Definition files belong in /chatGPT/roomVault/.
Map Core files belong in /chatGPT/mapVault/.
Render Core and Render Continuity files belong in /chatGPT/renderVault/.
Image Reference Index files belong in /chatGPT/referenceVault/.
Exterior Index files belong in /chatGPT/exteriorVault/.
Reference images belong in /chatGPT/referenceVault/images/.

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
10. Confirm all files say Version: v3.0.
11. Activate all rules, protocols, definitions, checklists, and canonical constraints.
12. Bind future Citadel requests to the active Codex registry.
13. Report initialization status.

---

# Protocol Activation Rule

Loading a file is not enough. Each loaded file's rules, protocols, definitions, checklists, and canonical constraints must be activated in the current chat.

If a required file is retrieved but not activated, initialization is incomplete.

---

# Runtime Codex Binding Rule

All user requests related to The Great Citadel must be interpreted through the active Codex file set. Do not answer, render, map, diagram, revise, or audit Citadel content from generic fantasy assumptions when an active Codex release is loaded.

---

# Mandatory Codex Compilation Rule

Any Citadel render, map, diagram, room view, exterior view, station view, audit, revision, canon update, reference-image request, 360 panorama, blueprint, or door render must be compiled into a Codex-grounded execution prompt before any generation tool is called.

For exterior render requests, use Exterior Index, Render Core, Render Continuity Rules, Map Core, and Image Reference Index as controlling sources.

---

# Prompt Approval Gate

Before any Citadel image is generated, print the full compiled image prompt in chat and ask:

“Is this the correct prompt?”

Do not call the image-generation tool until the user approves the prompt.

---

# Image Reference Retrieval Gate

When a render request may benefit from visual continuity references, consult /chatGPT/referenceVault/Codex_v3.0_Image_Reference_Index.md.

A listed image path is metadata only. Verify retrieval of any required reference image from GitHub by exact repository path before claiming it is available as a reference.

Do not assume an image exists because it appears in an index.

---

# Source of Truth Rule

The active v3.0 file set is the source of truth for The Great Citadel.

Exterior Index governs the Outside of the Citadel, exterior stations, exterior structure, exterior compliance, bridge, landing platform, and exterior render defaults.

---

# Save the Codex to GitHub Rule

When the user says save the Codex to GitHub, publish every required file in the active release manifest for the next version.

A GitHub Codex save is incomplete unless all required files are created successfully.

Every GitHub Codex save must also update the root README.md in the same save workflow.

The README update must include the new active version number, the new bootstrap file path, and the recommended bootstrap prompt updated to reference the new version.

---

# Version Matching Rule

All files in a published release must share the same version number.

The README active release reference must match the latest published ChatGPT Codex release after each successful GitHub save.

---

# Missing File Handling

If a required file cannot be loaded, report the missing file and do not claim full initialization.

---

# v3.0 Change Summary

Codex v3.0 adds the Exterior Layer as a required canonical module, including Outside of the Citadel, exterior stations, unified exterior structure rules, southwest bridge and landing platform rules, and exterior image-reference paths.

End of Codex v3.0 — Bootstrap.
