# People Index Bootstrap

Project: The Great Citadel
Vault: People Index
Version: v1.0
Role: Bootstrap instructions for maintaining the Citadel People Index in a dedicated ChatGPT window.

---

# Purpose

The People Index is a personal memory aid for names, faces, relationship context, conversation history, and important details about people the user intentionally adds.

Canonical model:

Face -> Context -> History

The system should help answer:

- Who is this person?
- Where do I know them from?
- What did we last talk about?
- What should I remember about them?
- Who are they connected to?

---

# Active Repository Paths

- /peopleIndex/PeopleIndex_Bootstrap.md
- /peopleIndex/people-index.json
- /peopleIndex/images/

---

# Source of Truth Rule

The JSON file at `/peopleIndex/people-index.json` is the source of truth for all People Index records.

Do not treat chat memory, assumptions, or unsaved discussion as canonical until the JSON file has been updated.

---

# Privacy and Consent Rules

1. Only store people the user intentionally adds.
2. Do not scrape or compile private personal data.
3. Do not use people-search/public-record aggregation as a source.
4. Public organization information may be added only when the user provides or approves the source.
5. Do not invent personal details.
6. Prefer user-entered facts over inferred facts.
7. Track source, confidence, and last verified date for important facts.
8. Sensitive or highly personal facts should be stored only when clearly useful and intentionally provided by the user.

---

# Required Person Record Fields

Each person should use a stable unique id and may include:

- id
- displayName
- firstName
- middleName
- lastName
- preferredName
- pronunciation
- photo
- photoStatus
- relationshipCategory
- organization
- role
- howIKnowThem
- memoryHooks
- importantNotes
- conversationHistory
- relatedPeople
- tags
- sources
- confidence
- lastVerified
- createdAt
- updatedAt

---

# Photo Handling Rules

1. Store images in `/peopleIndex/images/`.
2. Reference images using relative paths such as `images/firstname-lastname.jpg`.
3. Use simple lowercase filenames with hyphens.
4. If duplicate names exist, include context such as organization or role.
5. If no photo exists, use `photoStatus: "missing-photo"`.
6. If only a default avatar exists, use `photoStatus: "default-avatar"`.

---

# Discovery Model

People should be discoverable by:

- Face
- Name
- Organization
- Relationship category
- Tags
- Recent interaction
- Shared project
- Location or context
- Related people
- Missing or incomplete fields

---

# Citadel Representation

The People Index maps to the Citadel as the Embassy Archive.

Main areas:

- Portrait Gallery
- Recent Encounters Table
- Unknown Faces Wall
- Relationship Map Room
- Name & Face Practice Station
- Important Dates Board
- Unfinished Profiles Shelf

---

# Update Protocol

When the user asks to add or update a person:

1. Capture the provided facts.
2. Do not invent missing facts.
3. Create or update the person record in `people-index.json`.
4. Preserve existing information unless the user clearly replaces it.
5. Update `updatedAt` and `lastVerified` where appropriate.
6. Keep the JSON valid and consistently formatted.
7. Summarize what changed after saving.

---

# Save Command Rule

When the user says "save this" in a People Index chat, update `/peopleIndex/people-index.json` with the facts currently agreed upon.

If the update is conceptual rather than about a specific person, ask whether it belongs in the People Index bootstrap, gameplay vault, or another Citadel vault.

---

# Non-Canonical Working Notes

A chat may discuss possible structures, fields, and features. These are not canonical until saved into the appropriate GitHub file.
