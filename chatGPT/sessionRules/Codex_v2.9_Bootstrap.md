# Codex v2.9 — Bootstrap

Project: The Great Citadel
Version: v2.9
Role: First-load bootstrap, file manifest, initialization order, protocol activation, runtime Codex binding, prompt approval, file save rules, reference-image retrieval, and release file structure.
Supersedes: /chatGPT/sessionRules/Codex_v2.8_Bootstrap.md

---

# Required Release Manifest

A complete v2.9 Codex release contains these required files:

1. /chatGPT/sessionRules/Codex_v2.9_Bootstrap.md
2. /chatGPT/codexVault/Codex_v2.9_Canon_Core.md
3. /chatGPT/roomVault/Codex_v2.9_Room_Index.md
4. /chatGPT/roomVault/Codex_v2.9_Room_Render_Definitions.md
5. /chatGPT/mapVault/Codex_v2.9_Map_Core.md
6. /chatGPT/renderVault/Codex_v2.9_Render_Core.md
7. /chatGPT/renderVault/Codex_v2.9_Render_Continuity_Rules.md
8. /chatGPT/referenceVault/Codex_v2.9_Image_Reference_Index.md

Optional future files:

- /chatGPT/codexVault/Codex_v2.9_Symbol_Index.md
- /chatGPT/stationVault/Codex_v2.9_Station_Index.md
- /chatGPT/referenceVault/Codex_v2.9_Reference_Index.md

---

# Repository Structure Rule

Bootstrap files belong in /chatGPT/sessionRules/.

Canon Core files belong in /chatGPT/codexVault/.

Room Index and Room Render Definition files belong in /chatGPT/roomVault/.

Map Core files belong in /chatGPT/mapVault/.

Render Core and Render Continuity files belong in /chatGPT/renderVault/.

Image Reference Index files belong in /chatGPT/referenceVault/.

Reference images belong in /chatGPT/referenceVault/images/.

The Room Index must not be stored in codexVault for v2.9 and later releases unless a future release explicitly changes the repository structure.

---

# Initialization Order

1. Load Bootstrap.
2. Load Canon Core.
3. Load Room Index from roomVault.
4. Load Room Render Definitions from roomVault.
5. Load Map Core.
6. Load Render Core.
7. Load Render Continuity Rules.
8. Load Image Reference Index.
9. Load optional Symbol, Station, and Reference files when present.
10. Confirm version compatibility across all loaded files.
11. Activate all rules, protocols, definitions, checklists, and canonical constraints from all loaded files.
12. Build the active protocol registry.
13. Bind future Citadel requests to the active Codex registry so all render, map, diagram, canon, room, image-reference, and save requests automatically use the loaded files as source-of-truth context.
14. Report initialization status.

---

# Protocol Activation Rule

Loading a file is not enough.

For each loaded file, identify its rules, protocols, definitions, checklists, and canonical constraints. Activate them in the current chat and include them in the active protocol registry.

If a required file is retrieved but not activated, initialization is incomplete.

---

# Runtime Codex Binding Rule

After initialization, all user requests related to The Great Citadel must be interpreted through the active Codex file set.

The assistant must not answer, render, map, diagram, revise, or audit Citadel content from generic fantasy assumptions when an active Codex release is loaded.

Short user requests must be expanded through the active Codex before execution.

If the request is underspecified, the assistant should apply Codex defaults rather than inventing new architecture.

---

# Mandatory Codex Compilation Rule

After initialization, any user request involving The Great Citadel must be compiled into a Codex-grounded execution prompt before any generation tool is called.

This applies to render requests, map requests, diagram requests, room views, station views, audits, revisions, canon updates, reference-image requests, 360 panorama requests, blueprint requests, and door-render requests.

For map requests, use the Canonical Map Render Block and Great Citadel Master Map Prompt from Map Core as the controlling source.

For room render requests, use Render Core, Room Render Definitions, Render Continuity Rules, and Image Reference Index as controlling sources when applicable.

If the generated tool prompt cannot be traced back to active Codex rules, the request is not ready for execution.

---

# Prompt Approval Gate

Before any Citadel image is generated, the assistant must print the full compiled image prompt in chat and ask:

“Is this the correct prompt?”

The assistant must not call the image-generation tool until the user approves the prompt.

This applies to all Citadel renders, maps, diagrams, room views, station views, visual revisions, 360 panoramas, room blueprints, and door renders.

---

# Image Reference Retrieval Gate

When a render request may benefit from visual continuity references, the assistant must consult /chatGPT/referenceVault/Codex_v2.9_Image_Reference_Index.md.

A listed image path is metadata only. The assistant must verify retrieval of any required reference image from GitHub by exact repository path before claiming it is available as a reference.

If a required reference image cannot be fetched, report the missing path and continue only if the render can proceed under text-only Codex rules.

Do not assume an image exists because it appears in an index.

---

# Source of Truth Rule

The active v2.9 file set is the source of truth for The Great Citadel.

Bootstrap governs setup, loading, versioning, save behavior, activation, runtime binding, compilation, approval gates, release file structure, and reference-image retrieval.

Canon Core governs world identity and global canon.

Room Index governs room definitions and room connections.

Room Render Definitions governs room visual identity, station views, render features, compliance checks, and non-canonical visual mistakes.

Map Core governs coordinates, bearings, topology, map rendering, and topology separation requirements.

Render Core governs rendering workflows, render prompts, compliance checklists, and post-render audits.

Render Continuity Rules governs 360 references, blueprints, door renders, continuity lookups, and visual-reference priority.

Image Reference Index governs approved reference image paths and statuses.

---

# Save the Codex to GitHub Rule

When the user says save the Codex to GitHub, publish every required file in the active release manifest for the next version.

A GitHub Codex save is incomplete unless all required files are created successfully.

Do not save only one file unless the user explicitly asks for a repair or partial save.

GitHub saves require explicit user request, version increment, and successful publication of all required files.

Every GitHub Codex save must also update the root README.md in the same save workflow.

The README update must include the new active version number, the new bootstrap file path, and the recommended bootstrap prompt updated to reference the new version.

A GitHub Codex save is incomplete if README.md still points to the previous active ChatGPT Codex release after the new release files are published.

---

# Version Matching Rule

All files in a published release must share the same version number.

A version mismatch is non-canonical and must be reported.

Initialization is not complete until required files are loaded and version compatibility is confirmed.

The README active release reference must match the latest published ChatGPT Codex release after each successful GitHub save.

---

# Missing File Handling

If a required file cannot be loaded, report the missing file and do not claim full initialization.

If an optional file is missing, continue initialization and mark that file group inactive.

---

# v2.9 Change Summary

Codex v2.9 preserves v2.8 topology and modular structure while adding visual continuity infrastructure.

Major changes:

- Adds Room Render Definitions as a required file.
- Restores room-level visual canon and render blocks from the v2.4 source lineage.
- Adds Render Continuity Rules.
- Adds Image Reference Index.
- Defines 360 room reference images.
- Defines room blueprint reference images.
- Defines door-render continuity images.
- Defines GitHub image retrieval and verification rules.
- Requires README.md active release references to be updated during future GitHub Codex saves.
- Preserves v2.8 Garden direct-adjacency and topology-separation discipline.

End of Codex v2.9 — Bootstrap.
