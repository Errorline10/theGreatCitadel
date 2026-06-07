# Codex v2.5 — Bootstrap

Project: The Great Citadel
Version: v2.5
Role: First-load bootstrap, file manifest, initialization order, protocol activation, save rules.
Supersedes: /chatGPT/sessionRules/Codex_v2.4_Bootstrap.md

---

# Required Release Manifest

A complete v2.5 Codex release contains these required files:

1. /chatGPT/sessionRules/Codex_v2.5_Bootstrap.md
2. /chatGPT/codexVault/Codex_v2.5_Canon_Core.md
3. /chatGPT/codexVault/Codex_v2.5_Room_Index.md
4. /chatGPT/mapVault/Codex_v2.5_Map_Core.md
5. /chatGPT/renderVault/Codex_v2.5_Render_Core.md

Optional future files:

- /chatGPT/codexVault/Codex_v2.5_Symbol_Index.md
- /chatGPT/stationVault/Codex_v2.5_Station_Index.md
- /chatGPT/referenceVault/Codex_v2.5_Reference_Index.md

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
10. Report initialization status.

---

# Protocol Activation Rule

Loading a file is not enough.

For each loaded file, identify its rules, protocols, definitions, checklists, and canonical constraints. Activate them in the current chat and include them in the active protocol registry.

If a file is retrieved but not activated, initialization is incomplete.

---

# Source of Truth Rule

The active v2.5 file set is the source of truth for The Great Citadel.

Bootstrap governs setup, loading, versioning, save behavior, and activation.

Canon Core governs world identity and global canon.

Room Index governs room definitions and room connections.

Map Core governs coordinates, bearings, topology, and map rendering.

Render Core governs rendering workflows, render prompts, compliance checklists, and post-render audits.

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

# v2.5 Change Summary

Codex v2.5 splits the previous Bootstrap + Canon pair into a multi-file vault architecture:

- Bootstrap
- Canon Core
- Room Index
- Map Core
- Render Core

End of Codex v2.5 — Bootstrap.
