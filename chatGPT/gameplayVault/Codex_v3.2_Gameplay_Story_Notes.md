# Codex v3.2 — Gameplay Story Notes

Project: The Great Citadel
Version: v3.2
Role: Gameplay story, player-facing notes, item concepts, quest structure, plotline development, and unfolding game narrative.
Status: Auxiliary Codex support file. This file supplements the active Codex but is not part of the required v3.2 bootstrap manifest unless promoted in a future Codex release.

---

# Purpose

This file stores story and gameplay notes for the game experience that unfolds inside The Great Citadel.

It is intended to track:

- player journey
- plotline development
- gameplay loops
- quests
- puzzles
- collectible items
- inventory objects
- room-based discoveries
- station interactions
- unlockable paths
- narrative reveals
- character or guide notes
- world-state changes
- canon-sensitive gameplay ideas
- access objects
- protected knowledge areas
- inventory UI rules
- real-world content mappings

---

# Source-of-Truth Relationship

This file supplements the active Codex.

It must not override:

- Canon Core
- Room Index
- Room Render Definitions
- Map Core
- Render Core
- Render Continuity Rules
- Image Reference Index
- Exterior Index

If gameplay notes conflict with canonical topology, room definitions, compass orientation, door counts, render rules, exterior rules, or reference-image rules, the active Codex files control.

---

# Foundational Gameplay Premise

The Great Citadel is a gamified version of a personal web space.

The Citadel is not merely a fantasy environment. It is a living interface to real-world knowledge, media, memories, projects, archives, references, and personal content.

The world layer is fictional and exploratory. The knowledge layer may be real.

Examples:

- A book in a library may contain the complete text of a real-world book.
- A historical archive may contain real historical documents.
- A media room may contain actual films, music, podcasts, or videos.
- A map room may contain real maps and geographic information.
- A project room may contain real project documentation.
- A personal room may contain journals, notes, photographs, and memories.
- An invention room may contain real designs, prototypes, code repositories, and engineering notes.

The player explores information as place.

---

# Knowledge Object Principle

Every object in the Citadel belongs to one of two broad categories.

## Decorative Objects

Decorative objects support atmosphere, worldbuilding, and visual identity.

Examples:

- lanterns
- furniture
- stonework
- banners
- architectural details

## Knowledge Objects

Knowledge Objects expose, represent, or lead to real content.

Examples:

- books
- maps
- journals
- paintings
- diagrams
- globes
- displays
- archives
- terminals
- exhibits
- models

Knowledge Objects may reveal actual information rather than fictional placeholder content.

The Citadel transforms information retrieval into exploration.

---

# Gameplay Design Notes

## Player Role

To be defined.

## Core Gameplay Loop

Possible loop structure:

1. Enter a room.
2. Observe canonical stations and room features.
3. Discover notes, symbols, items, or memory fragments.
4. Interact with Knowledge Objects.
5. Solve a room-appropriate interaction or puzzle.
6. Unlock understanding, lore, access, or inventory objects.
7. Return to the Great Hall or move deeper into the Citadel.

---

# Protected Knowledge System

Certain locations within the Citadel represent protected real-world resources.

Protected resources may correspond to:

- password-protected websites
- private documents
- restricted project areas
- member-only content
- personal archives
- administrative tools
- encrypted notes
- protected databases
- authenticated APIs

The Citadel should not expose raw credentials directly through exploration.

Instead, access is represented through gameplay mechanics.

---

# Puzzle-Gated Access

Protected areas may be represented by:

- locked doors
- safes
- puzzle boxes
- mechanical locks
- combination devices
- encrypted archives
- hidden mechanisms
- challenge rooms

Completing a puzzle or challenge may produce an Access Object.

Example flow:

1. Player discovers a locked safe.
2. Player solves a code, cipher, or mechanism.
3. Safe opens.
4. Player obtains an Access Object such as a key.
5. Object is added to inventory.
6. Object can be used elsewhere to access protected rooms or protected data.

---

# Access Objects

Access Objects are gameplay representations of real-world access credentials.

They may represent:

- API access tokens
- OAuth tokens
- session tokens
- temporary credentials
- signed URLs
- authorization grants
- service connections
- membership credentials
- private archive permissions

In the Citadel, these appear as physical or symbolic objects.

Examples:

- keys
- spectacles
- seals
- badges
- sigils
- tokens
- permits
- artifacts

The player experiences authentication as inventory and exploration rather than as raw technical login flows.

---

# Ephemeral Access Object State Model

Because Access Objects can represent real-world API access tokens, they may time out or become invalid.

Every time-limited Access Object should support visual states.

## Active

Fully functional.

Visual language:

- pristine
- bright
- intact
- polished
- clear
- energized

Examples:

- clear Spectacles of Insight
- polished brass key
- glowing seal
- pristine token

## Expiring

Approaching timeout.

Visual language:

- fading glow
- slight tarnish
- faint cracks
- discoloration
- reduced energy
- subtle instability

Examples:

- spectacles develop hairline lens cracks
- key begins to rust
- seal starts fading

## Expired

Access no longer valid.

Visual language:

- cracked
- cloudy
- rusted
- bent
- damaged
- inert

Examples:

- spectacles have cracked or clouded lenses
- key is rusty or no longer fits
- seal is dull and inert

## Revoked

Access intentionally removed.

Visual language:

- shattered
- blackened
- broken in half
- transformed into a relic

The object may remain in inventory as historical evidence but cannot be used.

---

# Access Object Renewal

Expired Access Objects may sometimes be refreshed.

In-world renewal examples:

- recharge station
- authentication shrine
- registrar desk
- credential forge
- archivist station

Real-world equivalents:

- token refresh
- reauthentication
- OAuth renewal
- new session grant
- permission re-approval

---

# Spectacles of Insight

## Item Type

Access Object / Perception Artifact

## Purpose

The Spectacles of Insight alter how the player perceives information inside the Citadel.

When worn, the player can see information that is otherwise hidden, obscured, encoded, encrypted, forgotten, symbolic, or incomprehensible.

The underlying object does not change.

The player's perception changes.

## Core Principle

Keys unlock locations.

Spectacles reveal understanding.

The Spectacles reveal meaning rather than granting physical access.

## Example: Encoded Journal

Without Spectacles:

- The player sees cipher text.

With Spectacles equipped:

- The same journal section is displayed as plaintext.

## Example: Hidden Notes

Without Spectacles:

- A page appears blank or ordinary.

With Spectacles:

- Hidden writing appears between existing lines of text.

## Example: Real-World Content Mapping

A historical document may display:

Normal view:

- original manuscript

Spectacles view:

- modern transcription
- commentary
- cross references
- definitions

## Spectacles State Visualization

Active:

- clear lenses
- polished frame
- visible clarity or subtle glow

Expiring:

- faint lens cracks
- fading glow
- minor frame tarnish

Expired:

- cracked lenses
- cloudy glass
- damaged hinges or frame
- no glow

Revoked:

- shattered or blackened lenses
- broken frame

---

# Inventory Overlay System

Access Objects and other held items are displayed in a persistent bottom-screen inventory section.

## Overlay Rule

The inventory appears as a screen overlay.

It is positioned along the bottom edge of the player view.

The overlay is a gameplay UI layer and is not part of the rendered Citadel world.

Standard room renders should avoid UI overlays unless the user explicitly asks for gameplay UI or inventory display.

Gameplay UI renders may include overlays by request.

## Inventory Tile Rule

Each inventory object is displayed as a 1:1 square icon or tile.

Each tile visually represents one object.

Item tiles should be clear enough to show state changes.

Examples:

- Spectacles icon tile
- Key icon tile
- Seal icon tile
- Token icon tile
- Badge icon tile

## Item Tile Contents

Each item tile may show:

- object image
- active / expiring / expired / revoked visual state
- small durability or status indicator
- optional selected highlight
- optional cooldown / timeout effect
- optional unavailable state

## Aspect Ratio Rule

All inventory item visuals use a 1:1 square aspect ratio.

---

# Inventory Icon Prompt Rules

Inventory icons should be object-only presentations unless otherwise requested.

Preferred qualities:

- 1:1 square aspect ratio per icon
- centered object composition
- neutral or transparent background
- no hands
- no character
- no environment unless requested
- consistent camera angle across state variants
- same object design across state variants
- readable at small UI size

## Spectacles Physical Construction Constraint

The Spectacles of Insight must be constructed like a physically believable pair of round spectacles.

Requirements:

- exactly two lenses
- exactly one bridge connecting the lenses
- exactly one temple arm on the left side
- exactly one temple arm on the right side
- exactly two hinges total
- no duplicate arms
- no secondary arms
- no extra folding mechanisms
- no mirrored hinge assemblies
- no overlapping frame structures
- no additional eyewear components

The object should read as one pair of spectacles, not multiple overlapping spectacles or spectacles with duplicated arms.

## Spectacles Inventory Icon Quality Control

Reject and regenerate if any of the following occur:

- more than two lenses
- more than one arm per side
- duplicate hinges
- impossible frame geometry
- merged or overlapping spectacles
- asymmetrical duplication artifacts
- extra eyewear pieces attached to the frame

---

# Story Notes

## Premise

The Great Citadel is a gamified personal knowledge space where real-world content is explored through rooms, objects, stations, puzzles, and inventory systems.

## Opening Sequence

To be defined.

## Major Plotline

To be defined.

## Themes

Possible themes:

- memory
- discovery
- knowledge
- reflection
- identity
- media
- invention
- history
- philosophy
- personal growth
- permission and access
- hidden meaning
- private knowledge

---

# Items

## Item Registry

| Item Name | Location | Purpose | Status | Notes |
|---|---|---|---|---|
| Instruction Manual | Small Library | Orientation / tutorial object | Planned | Associated with the Instruction Manual Station. |
| Guest Book | Small Library | Player record / first interaction | Planned | May be combined with the Instruction Manual display. |
| Codex Reference Volume | Small Library | Lore/reference object | Planned | Must not be confused with the Instruction Manual / Guest Book. |
| Spectacles of Insight | To be defined | Perception artifact / Access Object | Planned | Reveals encoded, hidden, translated, or interpreted information. |
| Archive Key | To be defined | Protected-room access object | Planned | Represents access to protected rooms or protected data. |

---

# Quest and Plotline Registry

| Quest / Plotline | Starting Location | Required Items | Unlocks | Status | Notes |
|---|---|---|---|---|---|
| First Entry | Entry Hall | None | Small Library orientation | Planned | Introduces the Citadel as a lived-in place. |
| Orientation | Small Library | Instruction Manual / Guest Book | Foundational Door path | Planned | Teaches the player how the Citadel is navigated. |
| Protected Archive Access | To be defined | Puzzle solution / Access Object | Protected room or data access | Planned | Represents password-protected or token-gated content. |
| Hidden Meaning | To be defined | Spectacles of Insight | Plaintext or interpreted content | Planned | Allows ciphered or obscured information to be understood. |

---

# Room Gameplay Notes

## Entry Hall

To be defined.

Possible gameplay function:

- arrival
- first threshold
- safe starting space
- introduction to movement and doors

## Small Library

Known gameplay-relevant station:

- Small Library — Instruction Manual Station

Possible gameplay function:

- tutorial
- orientation
- player registration through Guest Book
- first Codex reference interaction
- reading real-world books through in-world book objects

## Great Hall

To be defined.

Possible gameplay function:

- central navigation hub
- domain selection
- compass-based routing
- access-object routing to protected domains

## Hall of Discovery

To be defined.

Possible gameplay function:

- science/discovery introduction
- Map of Understanding interaction
- Compass Rose of Discovery puzzle
- Celestial Vault observation puzzle
- Eight Alcoves of Discovery progression
- encoded journal or cipher interactions revealed by Spectacles of Insight

---

# Plotline Timeline

## Act I — Arrival and Orientation

To be defined.

## Act II — Exploration and Discovery

To be defined.

## Act III — Integration and Revelation

To be defined.

---

# Open Questions

- Who is the player in the world?
- Is the Citadel abandoned, inhabited, or responsive?
- Is there a guide character or voice?
- Are items physical inventory, symbolic discoveries, or both?
- Are rooms unlocked linearly or through player choice?
- What is the win condition or narrative endpoint?
- Which real-world services or content stores map to Access Objects?
- How should expired Access Objects be renewed in-world?
- Which rooms contain protected content?
- Which rooms contain Spectacles-visible hidden content?

---

# Change Log

## v3.2 Auxiliary Update — Gameplay Systems

Added:

- Citadel as gamified personal web space
- Knowledge Object principle
- protected knowledge system
- puzzle-gated access
- Access Objects as API/token representations
- timeout and revocation states
- Spectacles of Insight perception mechanic
- bottom inventory overlay system
- 1:1 inventory tile rule
- Spectacles physical construction constraints

## v3.2 Initial Auxiliary File

Created as a gameplay/story support file for tracking game notes, items, plotlines, room interactions, and unfolding narrative content.

End of Codex v3.2 — Gameplay Story Notes.
