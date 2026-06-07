# Codex v2.3 — Chat Initialization Protocols

## The Great Citadel

Status: Current canonical protocol document
Version: v2.3
Role: Chat setup, initialization, save rules, versioning, and render workflow protocols
Companion file: /chatGPT/codexVault/Codex_v2.3_Canon_Render_Rooms.md
Supersedes: /MAIN/Codex_v2.2_Render_Compliance_Edition.md

---

# Split Codex Architecture

Beginning with v2.3, the Codex is published as a matched pair:

/chatGPT/sessionRules/Codex_vX.Y_Chat_Initialization_Protocols.md
/chatGPT/codexVault/Codex_vX.Y_Canon_Render_Rooms.md

Both files must share the same version number. A published Codex version is incomplete unless both files exist.

The /MAIN folder is retained for legacy monolithic Codex versions. New split Codex releases save to /chatGPT/sessionRules/ and /chatGPT/codexVault/ unless explicitly requested otherwise.

---

# New Chat Initialization

1. Load the latest protocol file from /chatGPT/sessionRules/.
2. Initialize chat setup rules.
3. Load the matching canon file from /chatGPT/codexVault/.
4. Confirm both files share the same version number.
5. Treat the matched pair as the active Codex.

Do not rely on non-project memory for Codex details when the active Codex is available.

---

# Source of Truth Rules

The active matched Codex pair is the source of truth for The Great Citadel.

Local Codex edits may be made during a chat, may overwrite prior local wording, do not require a version bump, and do not automatically save to GitHub.

GitHub Codex saves require explicit user request, version increment, and successful publication of both matched files.

Phrases like update the Codex, add this to the Codex, or treat this as canon mean local update only unless GitHub save is explicitly requested.

---

# Save the Codex to GitHub Rule

When the user says save the Codex to GitHub, publish both files for the next version:

/chatGPT/sessionRules/Codex_vX.Y_Chat_Initialization_Protocols.md
/chatGPT/codexVault/Codex_vX.Y_Canon_Render_Rooms.md

A GitHub Codex save is incomplete unless both files are created successfully.

Do not save only one file unless the user explicitly asks for a repair or partial save.

---

# Rendering Workflow Rules

For standard renders, use this stack from the Canon file:

General Render Block + Room Concise Image Render Prompt + Canonical Visual Specification + User overrides + Non-canonical exclusions.

For high-fidelity renders, use requirement extraction, compliance checklist, strict render prompt when useful, image generation, post-render compliance audit, and user approval before any correction re-render.

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

# Startup Checklist

1. Identify active Codex source.
2. Load latest protocol file.
3. Load matching canon file.
4. Confirm version match.
5. Load active protocols.
6. Load rendering workflow.
7. Load canon summary and room index.
8. Use checklist-based rendering when fidelity matters.
9. Audit renders after generation.
10. Ask before any correction re-render.

---

# v2.3 Change Summary

Codex v2.3 introduces the split Codex architecture.

Protocol file location: /chatGPT/sessionRules/
Canon file location: /chatGPT/codexVault/
Both files share the same version.
Save the Codex to GitHub now means saving both files.
/MAIN remains as legacy storage for monolithic versions.

End of Codex v2.3 — Chat Initialization Protocols.
