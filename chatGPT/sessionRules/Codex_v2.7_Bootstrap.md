# Codex v2.7 — Bootstrap

Project: The Great Citadel
Version: v2.7
Role: First-load bootstrap, file manifest, initialization order, protocol activation, runtime Codex binding, prompt approval, file save rules.
Supersedes: /chatGPT/sessionRules/Codex_v2.6_Bootstrap.md

---

# Required Release Manifest

A complete v2.7 Codex release contains these required files:

1. /chatGPT/sessionRules/Codex_v2.7_Bootstrap.md
2. /chatGPT/codexVault/Codex_v2.7_Canon_Core.md
3. /chatGPT/codexVault/Codex_v2.7_Room_Index.md
4. /chatGPT/mapVault/Codex_v2.7_Map_Core.md
5. /chatGPT/renderVault/Codex_v2.7_Render_Core.md

Optional future files:

- /chatGPT/codexVault/Codex_v2.7_Symbol_Index.md
- /chatGPT/stationVault/Codex_v2.7_Station_Index.md
- /chatGPT/referenceVault/Codex_v2.7_Reference_Index.md

---

# Initialization Order

1. Load Bootstrap.
2. Load Canon Core.
3. Load Room Index.
4. Load Map Core.
5. Load Render Core.
6. Load optional Symbol, Station, and Reference files when present.
7. Confirm version compatibility across all loaded files.
8. Activate all rules and protocols from the loaded files.
9. Build the active protocol registry.
10. Bind future Citadel requests to the active Codex registry so that all render, map, diagram, canon, room, and save requests automatically use the loaded files as source-of-truth context.
11. Report initialization status.

---

# Protocol Activation Rule

Loading a file is not enough.

For each loaded file, identify its rules, protocols, definitions, checklists, and canonical constraints. Activate them in the current chat and include them in the active protocol registry.

If a file is retrieved but not activated, initialization is incomplete.

---

# Runtime Codex Binding Rule

After initialization, all user requests related to The Great Citadel must be interpreted through the active Codex file set.

The assistant must not answer, render, map, diagram, revise, or audit Citadel content from generic fantasy assumptions when an active Codex release is loaded.

Short user requests must be expanded through the active Codex before execution.

Examples:

- “render a map of the citadel” means: use Bootstrap, Canon Core, Room Index, Map Core, and Render Core to generate a canonical Citadel map.
- “render the Entry Hall facing north” means: use Canon Core, Room Index, Map Core orientation rules, Render Core render stack, and the Entry Hall North Render Checklist.
- “show the Great Hall” means: preserve Great Hall compass geometry, visible-door limits, forward-hemisphere rule, and all relevant room canon.

The assistant must derive the effective prompt from the active Codex rules before calling any image, map, diagram, or document-generation tool.

If the request is underspecified, the assistant should apply the Codex defaults rather than inventing new architecture.

---

# Mandatory Codex Compilation Rule

After initialization, any user request involving The Great Citadel must be compiled into a Codex-grounded execution prompt before any tool is called.

This applies to render requests, map requests, diagram requests, room views, station views, audits, revisions, and canon updates.

The assistant must not send a vague user phrase directly to an image, document, map, or generation tool.

Before execution, the assistant must derive the prompt from:

1. Bootstrap
2. Canon Core
3. Room Index
4. Map Core
5. Render Core
6. Any active optional index files

For map requests, the assistant must use the Canonical Map Render Block and Great Citadel Master Map Prompt from Map Core as the controlling source.

For room render requests, the assistant must use the Render Stack from Render Core as the controlling source.

If the generated tool prompt cannot be traced back to active Codex rules, the request is not ready for execution.

---

# Prompt Approval Gate

Before any Citadel image is generated, the assistant must print the full compiled image prompt in chat and ask:

“Is this the correct prompt?”

The assistant must not call the image-generation tool until the user approves the prompt.

This applies to all Citadel renders, maps, diagrams, room views, station views, and visual revisions.

If the user requests changes, revise the compiled prompt and ask for approval again before generation.

---

# Pre-Generation Compliance Gate

Before calling any image-generation tool for Citadel content, the assistant must verify that the execution prompt includes the relevant Codex constraints.

For maps, the prompt must include:

- 1:1 square format
- parchment-map styling unless otherwise requested
- north at top
- fixed compass orientation
- primary spine
- Garden west of Entry Hall
- Garden directly attached to the west side of Entry Hall
- Garden connected only to Entry Hall
- no visual, doorway, path, wall, or shared-boundary connection between Garden and Media Antechamber
- no visual, doorway, path, wall, or shared-boundary connection between Garden and Great Hall
- Great Hall central hub
- eight Great Hall openings at exact 45-degree intervals
- canonical labels only
- no shortcut connections
- no invented districts, gates, rings, or kingdoms

If these requirements are missing, the assistant must revise the execution prompt before generating.

---

# Generic Fantasy Map Prohibition

For Citadel map renders, the assistant must not generate or request:

- concentric city rings
- royal spires
- military districts
- merchant quarters
- sovereign courts
- invented numbered location indexes
- invented gates
- invented roads
- invented waterfalls, cliffs, cities, kingdoms, or political geography
- non-canonical labels
- decorative symmetry that overrides topology

A valid Citadel map must show the known canonical topology only:

Outside -> Entry Hall -> Small Library -> Foundational Door -> Great Hall -> Hall of Discovery

Garden west of Entry Hall and directly attached to the Entry Hall west wall.

Garden must connect only to Entry Hall.

Garden must not share any visual, doorway, path, wall, corridor, or boundary connection with Media Antechamber or Great Hall.

Great Hall as central compass hub with eight fixed openings:

N Science Door / Hall of Discovery
NE Philosophy Antechamber
E Arts Antechamber
SE Personal Antechamber
S Foundational Door
SW Inventor's Antechamber
W Media Antechamber
NW History Antechamber

No non-canonical room connections may be added.

---

# Topology Preservation Priority

Physical attachment relationships explicitly defined in Room Index are mandatory topology constraints.

Image generation, map generation, diagrams, and future room additions may not weaken, reinterpret, abstract, or replace direct-adjacency relationships with corridors, bridges, tunnels, or detached structures.

Direct adjacency must be preserved exactly.

Non-adjacency must also be preserved exactly. When two rooms are not canonically connected, image generation, map generation, diagrams, and future room additions may not invent any doorway, corridor, path, wall contact, shared boundary, bridge, tunnel, label-line connection, or architectural relationship between them.

---

# Source of Truth Rule

The active v2.7 file set is the source of truth for The Great Citadel.

Bootstrap governs setup, loading, versioning, save behavior, activation, runtime binding, compilation, and approval gates.

Canon Core governs world identity and global canon.

Room Index governs room definitions and room connections.

Map Core governs coordinates, bearings, topology, map rendering, and topology separation requirements.

Render Core governs rendering workflows, render prompts, compliance checklists, and post-render audits.

When a user request refers to “the Citadel,” “a room,” “a map,” “a render,” “the Codex,” or any named Citadel location, the active v2.7 file set must be treated as mandatory source context, not optional reference material.

---

# Save the Codex to GitHub Rule

When the user says save the Codex to GitHub, publish every required file in the active release manifest for the next version.

A GitHub Codex save is incomplete unless all required files are created successfully.

Do not save only one file unless the user explicitly asks for a repair or partial save.

---

# Version Matching Rule

All files in a published release must share the same version number.

A version mismatch is non-canonical and must be reported.

Initialization is not complete until required files are loaded and version compatibility is confirmed.

---

# Local vs GitHub Rule

Local Codex edits may be made during a chat and do not require a version bump.

GitHub saves require explicit user request, version increment, and successful publication of all required files.

---

# Missing File Handling

If a required file cannot be loaded, report the missing file and do not claim full initialization.

If an optional file is missing, continue initialization and mark that file group inactive.

---

# v2.7 Change Summary

Codex v2.7 strengthens topology separation and map-generation discipline.

Major changes:

- Preserves all v2.6 runtime binding, prompt compilation, approval gate, and map discipline rules.
- Adds explicit non-adjacency preservation for rooms that are not canonically connected.
- Adds topology separation rules to prevent invented Garden connections.
- Requires map prompts to forbid Garden-to-Media and Garden-to-Great-Hall visual or architectural connections.
- Adds stricter pre-generation compliance checks for map topology separation.

End of Codex v2.7 — Bootstrap.
