# Codex v2.4 — Bootstrap

## The Great Citadel

Status: Current canonical bootstrap document
Version: v2.4
Role: First-load file for new ChatGPT sessions. Loads, verifies, and activates the rest of the Codex system.
Companion canon file: /chatGPT/codexVault/Codex_v2.4_Canon_Render_Rooms.md
Supersedes: /chatGPT/sessionRules/Codex_v2.3_Chat_Initialization_Protocols.md

---

# Bootstrap Purpose

The Bootstrap document is the first Codex file loaded in a new chat session.

It is responsible for:

1. Discovering the rest of the Codex file set.
2. Loading required Codex files.
3. Verifying version compatibility.
4. Initializing all protocols and rules contained in loaded files.
5. Preserving session behavior rules from previous Initialization Protocol documents.
6. Defining local vs GitHub save behavior.
7. Defining render workflow behavior.
8. Defining failure handling when required files are unavailable.

The Bootstrap file should stay small, stable, and operational. It should not become the primary storage location for world canon.

---

# Current Required File Set

For v2.4, the required matched files are:

/chatGPT/sessionRules/Codex_v2.4_Bootstrap.md
/chatGPT/codexVault/Codex_v2.4_Canon_Render_Rooms.md

The Bootstrap file initializes the session.
The Canon file defines world canon, rooms, maps, rendering, stations, symbols, and topology.

---

# Future Expandable File Set

Future versions may expand into additional vaults:

/chatGPT/mapVault/
/chatGPT/renderVault/
/chatGPT/stationVault/
/chatGPT/referenceVault/

When these vaults exist, Bootstrap should load them after the core Canon file and activate their rules.

---

# Initialization Order

1. Load Bootstrap.
2. Identify required companion files.
3. Load Canon Render Rooms.
4. Verify version match.
5. Activate Bootstrap rules.
6. Activate Canon rules.
7. Build active protocol registry.
8. Report initialization status.

---

# Protocol Activation Rule

Loading a file is not enough.

For each loaded Codex file, the assistant must:

1. Read the file.
2. Identify its rules, protocols, definitions, and checklists.
3. Activate those rules for the current chat.
4. Add them to the active protocol registry.

If a file is merely retrieved but not activated, initialization is incomplete.

---

# Active Protocol Registry

After initialization, the assistant should be able to list active protocols, including:

- Codex Source of Truth
- Local vs GitHub Codex
- Save the Codex to GitHub
- Version Matching
- Visitor Perspective Rendering
- Fixed Compass Architecture
- Doorway Continuity
- Open Door Room Derivation
- Topology Preservation
- Navigational Path Preservation
- Station Visibility Inheritance
- Render Compliance Workflow
- User Approval Before Re-Render
- Canonical Coordinate System
- Map Generation Rules
- Canonical Bearing Requirements

---

# Source of Truth Rules

The active matched Codex file set is the source of truth for The Great Citadel.

Bootstrap governs session setup, loading, versioning, save behavior, and protocol activation.

Canon Render Rooms governs world canon, rooms, maps, rendering, stations, symbols, topology, and visual requirements.

Do not rely on non-project memory for Codex details when the active Codex files are available.

---

# Local vs GitHub Rules

Local Codex edits may be made during a chat, may overwrite prior local wording, do not require a version bump, and do not automatically save to GitHub.

GitHub Codex saves require explicit user request, version increment, and successful publication of every required file in the matched release.

Phrases like update the Codex, add this to the Codex, treat this as canon, or use this locally mean local update only unless GitHub save is explicitly requested.

---

# Save the Codex to GitHub Rule

When the user says save the Codex to GitHub, publish the full required file set for the next version.

For v2.4 structure, that means both:

/chatGPT/sessionRules/Codex_vX.Y_Bootstrap.md
/chatGPT/codexVault/Codex_vX.Y_Canon_Render_Rooms.md

A GitHub Codex save is incomplete unless every required file is created successfully.

Do not save only one file unless the user explicitly asks for a repair or partial save.

---

# Version Matching Rule

All files in a published release must share the same version number.

A version mismatch is non-canonical and must be reported.

Initialization should not be declared complete until required files are loaded and version compatibility is confirmed.

---

# Failure Handling

If a required file cannot be loaded:

1. Report which file is missing or unavailable.
2. Do not claim full initialization.
3. Continue with available files only if the user approves or if partial operation is safe.
4. Mark missing-file rules as inactive.

If a version mismatch is found:

1. Report the mismatch.
2. Ask whether to continue with partial or mixed-version context.
3. Do not silently merge mismatched versions.

---

# Rendering Workflow Rules

For standard renders, use the Canon file's render stack:

General Render Block + Room Concise Image Render Prompt + Canonical Visual Specification + User overrides + Non-canonical exclusions.

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

# Initialization Completion Record

After loading and activation, report:

- Loaded files
- Version numbers
- Version match status
- Active protocol groups
- Missing or inactive files, if any
- Initialization status

Example status:

Initialization Complete
Bootstrap: v2.4
Canon Render Rooms: v2.4
Version Match: Confirmed
Active Protocol Registry: Loaded

---

# v2.4 Change Summary

Codex v2.4 renames Chat Initialization Protocols to Bootstrap.

It preserves the contents and intent of the v2.3 Initialization Protocols document while adding explicit bootstrap responsibilities:

- file discovery
- file loading
- version verification
- protocol activation
- active protocol registry
- missing-file handling
- initialization completion reporting

End of Codex v2.4 — Bootstrap.
