# The Codex

Repository archive for **The Codex of The Great Citadel**.

## ChatGPT Bootstrap

ChatGPT users should bootstrap the active Codex release before making Citadel requests.

Repository:
`Errorline10/theGreatCitadel`

Bootstrap file:
`chatGPT/sessionRules/Codex_v2.9_Bootstrap.md`

Recommended bootstrap prompt:

```text
Bootstrap The Great Citadel Codex from GitHub.

Use the GitHub connector only. Do not use web browsing, memory, assumptions, or prior chat context as proof that files were loaded.

Repository:
Errorline10/theGreatCitadel

Load this bootstrap file first:
chatGPT/sessionRules/Codex_v2.9_Bootstrap.md

Then follow the bootstrap manifest exactly. Fetch every required file by exact GitHub path.

After fetching, verify:
1. Each required file was actually retrieved.
2. Each file says Version: v2.9.
3. The Room Index is loaded from roomVault, not codexVault.
4. Room Render Definitions are loaded from roomVault.
5. Render Continuity Rules are loaded from renderVault.
6. Image Reference Index is loaded from referenceVault.
7. All rules, protocols, definitions, checklists, canonical constraints, render continuity rules, and image reference retrieval rules are activated.
8. Future Citadel requests are bound to the active v2.9 Codex.

Do not claim loaded, initialized, or activated unless the GitHub connector successfully fetched the files.

If any required file cannot be fetched, report the missing path and state that initialization is incomplete.

After loading, report initialization status and list the active file paths.
```

---

This repository stores complete standalone Codex versions. Each version is a full copy of the Codex at that point in time, not a patch file.

## Current ChatGPT Codex Release

- Version: `v2.9`
- Bootstrap: `chatGPT/sessionRules/Codex_v2.9_Bootstrap.md`
- Required release manifest is defined in the active bootstrap file.

## Versioning Rules

- Every Codex version is a complete artifact.
- No version depends on another version to be understood.
- Branches may be used for experimental work.
- Only approved full copies are promoted into the MAIN archive.
- When a new Codex version is saved to GitHub, the README must be updated in the same save workflow.
- The README bootstrap file path, recommended bootstrap prompt, and Current ChatGPT Codex Release section must all reference the new version number.
- A GitHub Codex save is incomplete if the required Codex files are published but the README still points to the previous active ChatGPT Codex release.

## Current World Name

The canonical world name is **The Living Mind Palace**.

`theGreatCitadel` is the repository name only and is not currently the canonical world name.