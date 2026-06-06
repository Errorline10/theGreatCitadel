# The Codex v1.5 — Rendering Continuity and Arts Antechamber Edition

## The Great Citadel

**Status:** Current canonical version  
**Versioning model:** Full-copy standalone Codex version  
**Canonical world name:** The Great Citadel  
**Source:** Supersedes Codex v1.4 — Garden Meditation Edition  

---

# 1. Global Canon

The Great Citadel is a vast medieval world of knowledge, memory, media, discovery, and reflection.

Within it, information is not browsed; it is physically explored through rooms, halls, gardens, doors, maps, alcoves, symbols, stations, and realms.

The Codex is the living record of The Great Citadel. It defines architecture, rooms, realms, visual language, rendering rules, stations, and accepted canonical design decisions.

The Great Citadel should feel ancient, lived-in, warm, human-scaled, and coherent. It should feel like a place of knowledge that is inhabited and cared for, not a cold or oversized monument.

---

# 2. Current Known Versions

## MAIN

### Codex v1.0 — Discovery Edition

Initial full-copy canonical Codex version. Included the Foundations, Great Hall, Palace Sigil, Science Realm, Hall of Discovery, Map of Understanding, Compass Rose of Discovery, Celestial Vault, Eight Alcoves of Discovery, and universal rendering standards.

### Codex v1.1 — Entry Hall Edition

Added Entry Hall as a formal foundational room between the Front Entry and Hallway.

### Codex v1.2 — Great Citadel Foundations Edition

Changed the canonical world name to The Great Citadel, revised the Foundations, retired Front Entry and Hallway as separate rooms, added antechamber rules, revised room look-and-feel, codified Great Hall banners, and added detailed Entry Hall and Small Library rules.

### Codex v1.3 — Station Rendering Edition

Reorganized the Codex for image rendering. Added global station standards, a room-section template, and the first formal station: Small Library — Instruction Manual Station.

### Codex v1.4 — Garden Meditation Edition

Preserved v1.3 and replaced the Garden theme with a refined meditation-garden identity.

Added the Garden as a west-facing, dry, bright, open-air Zen meditation garden connected to the Entry Hall side door. The Garden has one canonical east-wall door, no visible buildings in standard renderings, a raked sand Zen garden, stacked Zen stones, and a small Buddha statue.

### Codex v1.5 — Rendering Continuity and Arts Antechamber Edition

Preserves v1.4 and consolidates the recent local working updates.

Adds global 16:9 image-format rules, doorway display rules, doorway identification rules, directional-continuity rules, connected-room perspective rules, general antechamber standards, Entry Hall three-door layout, Garden Buddha statue placement and station, and a detailed Arts Antechamber compass layout.

---

# 3. Versioning System and Saving Protocol

Every Codex version is a complete standalone copy of the full document.

A version should include:

- All foundational rooms
- All defined realms
- All symbols
- All rendering rules
- All accepted amendments
- All current architectural standards
- A version number
- A version title
- A changelog section

No version depends on another version to be understood.

Branches may experiment, but only full Codex copies are promoted into the MAIN archive.

## Local and GitHub Save Protocol

Local Codex files are working drafts and may be overwritten during editing.

The Codex version number does not change for local-only edits.

The no-overwrite-history rule applies only when saving or publishing the Codex to GitHub.

When the user asks to save the Codex to GitHub, the Codex version number must increment, a changelog entry must be added, and the previous state must be preserved through Git history.

---

# 4. Global Room and Rendering Standards

## Image Format Rule

All standard room renderings, station renderings, and Codex visual references should be rendered in a 16:9 horizontal format unless a different format is explicitly requested.

The default image format for The Great Citadel is:

```text
16:9 landscape
```

This format supports:

- architectural room views
- visible door placement
- forward-facing perspective
- environmental storytelling
- doorway continuity into connected rooms
- station context when needed

Non-16:9 formats should only be used for special cases such as maps, diagrams, vertical object studies, icons, sigils, or explicitly requested alternate compositions.

## Visitor Perspective Principle

All rooms should be rendered from the perspective of a visitor physically present within the space.

The viewer should feel:

```text
I am standing in this room.
```

not:

```text
I am looking at a diagram of this room.
```

## Central Viewing Principle

When rendering a room from visitor perspective, the viewer should be positioned at or near the geometric center of the room unless a room-specific rule or station rule overrides this.

Only the viewing direction changes.

## Forward Hemisphere Rule

The viewer should only see the portion of the room in front of them.

Architecture behind the viewer remains unseen.

## Limited Door Rule

When practical:

- Minimum visible doors: 1
- Preferred visible doors: 2–4
- Maximum visible doors: 4

Visitors should never see the entirety of a room's navigation structure at once.

Room-specific standards may impose stricter limits.

## Doorway Display Rule

When a door is visible in a rendering and that door is open, the connected room or connected space beyond the threshold should be visibly shown.

An open doorway should not reveal an undefined void, a blank wall at implausible distance, or an unrelated scene when the connected destination is already canonically known.

The visible room or space beyond the threshold should include enough recognizable features for the viewer to identify the destination.

If the connected destination is not yet fully visually specified in the Codex, the open-door view should still show directionally and thematically appropriate cues consistent with the known connection.

## Doorway Identification Rule

When possible, one or more recognizable features of the connected destination should be visible through an open doorway.

Recognizable features may include:

- furniture
- bookshelves
- floor systems
- lighting character
- banners
- plants
- symbols
- room scale
- architectural identity

## Directional Continuity Through Doorways Rule

When a rendering shows a connected room through an open doorway, the visible room beyond the threshold should be presented from a direction consistent with the current viewer position and facing direction.

The connected room should feel like a natural continuation of the viewer's current line of sight.

The next room should not appear from an unrelated, opposite, or contradictory perspective.

If the current image is facing north, then the visible connected room beyond an open doorway should appear as it would be seen from that same northward-facing approach.

The doorway view should preserve spatial and directional continuity.

## Connected Room Perspective Rule

When an adjacent room is visible through an open door, the connected room should be rendered from the perspective created by the current room's viewpoint, doorway position, and facing direction.

This means:

- the next room should align with the current camera direction
- the threshold should feel spatially continuous
- the visible destination should appear as the next room in sequence
- the connected room should not be shown from its opposite canonical direction unless that would be physically correct from the current viewpoint

## Partial Floor Rule

Major floor features should normally be only partially visible.

Examples:

- Great Knowledge Compass
- Map of Understanding
- Future realm maps
- Navigation mosaics

The viewer should feel they are standing upon the artifact rather than observing it from above.

## Visible Ceiling Rule

Whenever a room contains a significant ceiling feature, that feature should be included when practical.

## No Omniscient Perspective Rule

Avoid:

- Bird's-eye views
- Floating camera angles
- Ceiling-level viewpoints
- Impossible perspectives

Exceptions:

- Maps
- Blueprints
- Architectural diagrams
- Codex reference illustrations
- Approved station views that require a focused downward angle while remaining physically plausible

## Discovery Rule

A visitor should not fully understand a room from a single image.

Every rendering should imply hidden details, unseen destinations, and future discoveries.

## Neighborhood Rule

When a door is visible, the surrounding architecture should communicate the nature of the destination beyond.

Examples:

- Biology Door → living plants and botanical collections
- Astronomy Door → planets, celestial globes, and star instruments
- Logic Door → geometry, mathematics, and pattern displays

## Continuity Rule — Revised

All rooms should feel as though they belong to the same civilization.

The Great Citadel should feel ancient, lived-in, warm, human-scaled, and coherent.

Rooms should avoid feeling overly vast, cold, empty, or monumental unless a specific room requires grandeur.

Common materials:

- Stone
- Timber
- Carved wood
- Brass
- Bronze
- Leather
- Parchment
- Water
- Living plants
- Vines
- Moss

Subtle Time Traveler modifications may appear throughout the Citadel.

## Cozy Human Scale Rule

Rooms should generally feel comfortable to occupy.

Even when the architecture is old, ceremonial, or important, most rooms should retain a smaller human scale.

Preferred qualities:

- Warmth
- Shelter
- Intimacy
- Readable proportions
- Places where a person could sit, study, rest, or reflect
- Wood details that soften the stone architecture
- Lanterns, hearth light, or warm indirect illumination where appropriate

The Citadel should feel like a place humans live, study, and return to, not only a monument to be observed.

## Wood Emphasis Rule

Rooms should make greater use of wood.

Wood may appear as:

- Beams
- Railings
- Doors
- Wall panels
- Shelves
- Tables
- Benches
- Ceiling ribs
- Carved screens
- Decorative trim
- Warm architectural framing

Stone remains foundational, but wood should add warmth, texture, and human presence.

## Plant and Vine Integration Rule

Plants, vines, moss, and living greenery may appear throughout the Citadel.

Some walls may include climbing vines, small plants, or signs of nature reclaiming the architecture.

Plant life should feel integrated, not random.

It may suggest:

- Age
- Care
- Memory
- Restoration
- Reflection
- The relationship between knowledge and living systems

Heavy plant growth should be strongest in gardens, biology-related spaces, older corridors, and rooms connected to reflection or restoration.

## Archaeology Principle

Every room should show evidence of age and history:

- Repairs
- Additions
- Modifications
- Patina
- Worn stone
- Updated mechanisms

Nothing should appear newly constructed.

## Room Identity Principle

Every major room should possess at least one defining architectural feature.

Examples:

| Room | Defining Feature |
|---|---|
| Great Hall | Great Knowledge Compass |
| Hall of Discovery | Map of Understanding and Celestial Vault |
| Small Library | Instruction Manual and Guest Book; Codex reference source |
| Garden | Raked sand Zen garden, stacked Zen stones, single northwest-corner Buddha statue |
| Entry Hall | Human-scaled welcome passage; side tables; coat/jacket hanging place |
| Arts Antechamber | Four-door creative orientation room: Music, Writing, Visual, Great Hall |

## Codex Principle

The Citadel is experienced, not observed.

Every rendering should place the visitor inside the world rather than outside it.

---

# 5. Global Station Standards

## Station Concept

A station is a fixed viewpoint inside a room.

A station is used when a rendering should focus on a particular object, feature, or area of a room rather than presenting the room as a general whole.

A station defines:

- The viewer's fixed position
- The viewing direction
- The focal object
- The intended framing
- The purpose of the view

## Purpose of Stations

Stations are used for focused renderings.

A station rendering is different from a standard room rendering.

A standard room rendering usually presents the room from its canonical viewing direction and emphasizes the room as a space.

A station rendering emphasizes a specific object or feature within the room.

## Station Rule

A station is a named fixed point within a room.

Each station should be tied to a specific room and a specific purpose.

A station may override the normal central-viewing rule when a focused object study is required.

However, the station should still feel like a real visitor viewpoint physically located within the room.

## Station Rendering Rule

When rendering from a station:

- The viewpoint should remain physically plausible
- The focal object should be clearly emphasized
- The framing should support the purpose of the station
- The surrounding room may appear, but only as supporting context
- The focal object may occupy most of the image if that is the purpose of the station

## Station Override Rule

A station may override the normal central-viewing rule when a focused object study is required.

However, it does not override the Citadel's broader rendering principles.

A station rendering should still feel like a real visitor perspective inside The Great Citadel.

## Station Naming Convention

Stations should be named by room and purpose.

Suggested format:

```text
[Room Name] — [Station Name]
```

Example:

```text
Small Library — Instruction Manual Station
```

---

# 6. General Antechamber Standards

## Purpose of Antechambers

Antechambers are transitional rooms between the Great Hall and deeper realm paths.

They are not the full realm.

They introduce the identity, atmosphere, symbols, and major paths of the realm beyond.

An antechamber should function as an orientation space, giving the visitor a first sense of the realm before they enter its deeper halls.

## Antechamber Observer Position Rule

In a standard antechamber rendering, the viewer stands at or near the geometric center of the antechamber.

The viewer should feel physically present inside the room.

The image should not use a floating, overhead, diagrammatic, or impossible viewpoint unless explicitly requested as a map or architectural plan.

## Antechamber Viewing Angle Rule

Each standard antechamber rendering must specify a facing direction.

The viewer faces one compass direction at a time.

The rendering should show the forward hemisphere of the room only.

The wall or doorway in front of the viewer should be the primary focus of the image.

The viewer should not see the entire antechamber at once in a standard rendering.

## Antechamber Door Visibility Rule

A standard antechamber rendering should not show all canonical doors at once.

The door on the wall being faced should usually be the primary visible door.

Adjacent doors may appear only if physically plausible within the forward hemisphere and if they do not turn the image into an overview.

The preferred standard rendering shows one primary door.

The practical maximum is two visible doors unless a room-specific rule allows more.

## Antechamber Compass Door Rule

Antechamber doors should be assigned to compass positions when the room layout is defined.

Once defined, those compass positions are canonical.

A door should not move to another wall for visual convenience.

If a rendering faces north, it should show the north-facing portion of the room.

If a rendering faces east, it should show the east-facing portion of the room.

If a rendering faces south, it should show the south-facing portion of the room.

If a rendering faces west, it should show the west-facing portion of the room.

## Antechamber Open Door Display Rule

If a visible antechamber door is open, the connected room, realm path, or connected space beyond the threshold should be visible.

The view beyond the open doorway should include recognizable features of the connected destination.

The visible destination should preserve directional continuity with the current viewer position and facing direction.

The open doorway should not reveal an unrelated scene, blank void, impossible angle, or destination viewed from the wrong perspective.

## Antechamber Directional Continuity Rule

When a connected room or path is visible through an open antechamber doorway, it should be rendered from the same directional line of sight as the current image.

The view beyond the doorway should feel like a natural continuation of the visitor's current gaze.

For example:

If the viewer stands in an antechamber facing north and the north door is open, the room or path beyond that north door should appear as it would be seen while looking north from the antechamber.

It should not appear as if the viewer has already entered the next room and turned around.

## Antechamber Scale Rule

Antechambers should be smaller and more focused than the Great Hall.

They may be richer or more specialized than the Foundation rooms, but they should remain human-scaled enough to feel like threshold spaces.

They should not feel like full realms, large public museums, huge theaters, or complete destination spaces.

## Antechamber Identity Rule

Each antechamber should clearly communicate the identity of its realm.

This identity may be shown through:

- door symbols
- banners
- materials
- lighting
- objects
- alcoves
- tools
- inscriptions
- furniture
- visible connected-room cues

The antechamber should suggest what lies beyond without fully revealing the deeper realm.

---

# 7. Global Map and Connection Rules

The Foundations are north-oriented.

```text
NORTH

Great Hall
    │
Foundational Door
    │
Small Library
    │
Entry Hall

SOUTH
```

Main Foundation path:

```text
Entry Hall → Small Library → Foundational Door → Great Hall
```

Garden branch:

```text
Entry Hall West Door → Garden East Door → Garden
```

Great Hall realm access:

| Direction | Opening | Connection |
|---|---|---|
| North | Science Door | Hall of Discovery → Science Realm |
| Northeast | Philosophy Door | Philosophy Antechamber → Philosophy Realm |
| East | Arts Door | Arts Antechamber → Arts Realm |
| Southeast | Personal Door | Personal Antechamber → Personal Realm |
| South | Foundational Door | Small Library → Entry Hall |
| Southwest | Inventor's Door | Inventor's Antechamber → Inventor's Realm |
| West | Media Door | Media Antechamber → Media Realm |
| Northwest | History Door | History Antechamber → History Realm |

---

# 8. Room Index

## Current Foundation Rooms

1. Entry Hall
2. Garden
3. Small Library
4. Foundational Door
5. Great Hall

## Current Defined Rooms and Antechambers

1. Entry Hall
2. Garden
3. Small Library
4. Great Hall
5. Hall of Discovery
6. Media Antechamber
7. History Antechamber
8. Philosophy Antechamber
9. Arts Antechamber
10. Personal Antechamber
11. Inventor's Antechamber

## Current Defined Stations

1. Small Library — Instruction Manual Station
2. Garden — Buddha Statue Station

## Retired as Separate Rooms

- Front Entry
- Hallway

Absorbed into:

- Entry Hall

---

# 9. Room Section Template

Each room section should use this rendering-oriented structure:

```text
## [Room Name]

### Purpose

### Connections

### Door Rules

### Viewing Directions

### Required Features

### Material and Atmosphere

### Standard Rendering Rules

### Open Door Display Rules

### Stations

### Non-Canonical Mistakes to Avoid
```

---

# 10. Entry Hall

## Purpose

The Entry Hall is the southernmost entrance and first threshold space of The Great Citadel.

It combines the former roles of Front Entry, Entry Hall, and Hallway into one canonical room.

It welcomes the visitor and guides them inward.

The Entry Hall should feel like the Citadel is personally receiving a new visitor.

## Connections

The Entry Hall has three canonical doors:

- North Door → Small Library
- South Door → Outside / Arrival
- West Door → Garden

Primary path:

```text
South Door → Entry Hall → North Door → Small Library
```

Garden branch:

```text
Entry Hall West Door → Garden East Door → Garden
```

## Door Rules

The Entry Hall has exactly three canonical doors:

1. North Door
2. South Door
3. West Door

No additional Entry Hall doors are canonical unless later defined.

The Entry Hall is not a hub.

It is a narrow welcoming passage with one side branch to the Garden.

## Viewing Directions

The standard Entry Hall rendering should usually look north along the main path toward the Small Library.

The viewer stands inside the Entry Hall.

The north door may be visible ahead.

The west door may be visible to the left side if composition allows.

The south door is normally behind the viewer in a north-facing render.

## Required Features

The Entry Hall should include:

- small tables on each side
- a place to hang a coat or jacket
- a clear forward path
- warm lantern light
- wood-softened stone architecture
- plants, vines, or moss where appropriate
- practical arrival details
- welcoming signs or inscriptions when appropriate

## Material and Atmosphere

The Entry Hall should feel:

- narrow
- warm
- cozy
- human-scaled
- ancient
- lived-in
- cared for
- welcoming
- safe
- practical
- inviting

It should feel like the first human-scaled threshold of The Great Citadel.

## Standard Rendering Rules

Render the Entry Hall as a narrow welcoming passage.

Do not render it as a broad ceremonial chamber.

It should feel longer than wide.

It should show a clear path inward toward the Small Library.

The room should include practical arrival details such as side tables, coat hooks, bags, lanterns, or small welcoming signs.

If the north door is open, the Small Library should be visible beyond it.

## Open Door Display Rules

If the north door is open, the Small Library should be visibly shown beyond the threshold.

The view through the north door should show the Small Library from the same northward-facing direction as the Entry Hall rendering.

The Small Library should appear as the viewer would encounter it when looking north from the Entry Hall into the Small Library.

It should not appear as if the viewer is already inside the Small Library looking back from another direction.

The view through the north door should include recognizable Small Library features such as:

- bookshelves
- warm study lighting
- reading furniture
- lecterns
- compact library atmosphere

If the south door is open, the exterior arrival side of the Citadel should be shown beyond the threshold.

The view through the south door should suggest arrival into The Great Citadel and may include:

- daylight
- entry threshold stone
- exterior approach
- welcoming transition into the Citadel

If the west door is open, the Garden should be visibly shown beyond the threshold.

The view through the west door should include recognizable Garden features such as:

- open sky
- raked sand Zen garden
- stacked Zen stones
- modest plants
- meditation atmosphere

## Stations

No formal Entry Hall stations are defined yet.

## Non-Canonical Mistakes to Avoid

- Rendering the Entry Hall as a broad ceremonial chamber
- Making it feel grand, vast, or open like the Great Hall
- Omitting the small human-scaled welcome qualities
- Omitting practical arrival features
- Adding more than three doors
- Placing the Garden door anywhere except the west side of the Entry Hall
- Making the Entry Hall feel like a hub
- Showing an open north door without the Small Library visible beyond it
- Showing the Small Library beyond the north door from the wrong perspective

---

# 11. Garden

## Purpose

The Garden is a branch space connected to the Entry Hall.

It is a meditation garden.

It serves as a calm, restorative side space where a visitor may step away from the main Foundation path, sit quietly, breathe, reflect, and regain inner balance before continuing deeper into the Citadel.

The Garden should feel peaceful, bright, welcoming, and spiritually quiet.

## Connections

The Garden connects to the Entry Hall through the Entry Hall west door and the Garden east door.

Connection:

```text
Entry Hall West Door → Garden East Door → Garden
```

The Garden does not interrupt the main Foundation path.

It is an optional branch space connected to the Entry Hall.

## Door Rules

The Garden has one canonical door.

The door is located on the east wall of the Garden.

This east-wall door connects directly back to the Entry Hall through the Entry Hall west door.

No additional Garden doors are canonical unless later defined.

## Viewing Directions

The standard Garden rendering faces west on the map.

The viewer stands inside the Garden and looks westward.

The Garden's east-wall door should not be the central subject of a standard west-facing Garden rendering.

The west-facing view should emphasize the Garden itself and its meditation features.

East-facing Garden renderings may be requested as alternate views. When facing east, the viewer looks toward the single east-wall Garden door.

## Required Features

The Garden should include:

- open sky
- warm daylight
- a meditation-garden atmosphere
- a raked sand Zen garden
- stacked Zen stones
- exactly one small Buddha statue in the northwest corner
- modest living plants
- vines or moss on old stone where appropriate
- lanterns or small garden lights
- old Citadel stone details
- a calm, happy, restorative atmosphere

## Material and Atmosphere

The Garden should feel:

- open
- airy
- happy
- dry
- bright
- calm
- meditative
- restorative
- human-scaled
- cared for
- lightly cultivated
- spiritually quiet

The Garden should strongly read as a meditation garden.

It should not feel like a park, a farm, a wet courtyard, or a public plaza.

## Buddha Statue Rule

There is only one Buddha statue in the Garden.

The Buddha statue is located in the northwest corner of the Garden.

It should support the meditation-garden identity of the space.

The statue should feel peaceful, modest, and integrated into the Garden.

It should not be monumental or oversized.

No additional Buddha statues are canonical.

## Zen Sand Garden Rule

The Garden should include a raked sand Zen garden.

The raked sand should be clearly visible and should contribute to the meditative atmosphere.

The Zen garden should feel intentional, ordered, calm, dry, and well cared for.

The raked sand patterns should reinforce stillness, attention, and contemplation.

## Zen Stone Rule

The Garden should include stacked Zen stones.

These should feel balanced, deliberate, and contemplative.

They should support the Garden's identity as a meditation space.

They should not become oversized monuments or dominate the entire composition.

## Building Visibility Rule

No buildings should be visible in a standard rendering of the Garden.

The rendering should remain inside the Garden space and should not show visible building facades, large architectural masses, or exterior structures as dominant visual elements.

The Garden should feel self-contained, open to the sky, and visually focused on its contemplative landscape.

The east-wall door connection to the Entry Hall may exist canonically, but it should not require visible buildings in the standard view.

## Dryness Rule

The Garden should not look wet.

It should not appear rainy, muddy, slick, waterlogged, swampy, or freshly soaked.

Moisture may exist only locally around an optional water feature, but the Garden as a whole should read as dry, comfortable, and pleasant to inhabit.

## Mountain View Rule

A distant mountain view may remain as a background feature.

It should not dominate the identity of the Garden.

No pathways should lead directly to the mountains.

The mountains serve as a distant reminder that the world is larger than the Citadel itself.

## Standard Rendering Rules

The standard Garden rendering faces west on the map.

The Garden should appear dry, bright, open, and welcoming.

It should strongly read as a meditation garden.

The raked sand Zen garden should be visible.

Stacked Zen stones should be visible.

The single small Buddha statue should be visible only if composition and direction allow, and it must be in the northwest corner.

No buildings should be visible.

The east-wall door to the Entry Hall should not become the primary subject of the standard west-facing Garden rendering.

No pathways should lead directly to the distant mountains.

## Open Door Display Rules

If the Garden's east-wall door is visible and open, the Entry Hall should be visibly shown beyond the threshold.

The Entry Hall should appear from the direction created by the Garden viewer position and the east-wall doorway.

The view through the east door should preserve directional continuity and should not show the Entry Hall from an unrelated angle.

The view through the east door should include recognizable Entry Hall features such as:

- narrow hallway-like proportions
- warm lantern light
- small side tables
- wood-softened stone architecture
- welcoming interior atmosphere

Because no buildings should be visible in a standard Garden rendering, this rule applies only when the east door itself is visible and open.

## Stations

### Garden — Buddha Statue Station

This station is a fixed viewpoint in the Garden.

It is positioned directly in front of the Buddha statue in the northwest corner of the Garden.

The viewer stands facing the Buddha statue from close range.

The Buddha statue should be shown at eye level.

The Buddha statue should fill most of the image.

The surrounding Garden may appear only as secondary context.

#### Purpose

This station is used to render the Buddha statue as the primary subject of the Garden.

It emphasizes:

- the meditative identity of the Garden
- the quiet spiritual focus of the northwest corner
- the calm and contemplative role of the Buddha statue

#### Framing Rule

From this station, the Buddha statue should be the dominant object in the image.

The viewpoint should be direct and eye-level.

The statue should occupy most of the frame.

The background may include small amounts of recognizable Garden context such as:

- raked sand
- Zen stones
- plants
- old stone surfaces
- warm daylight

However, the Garden itself is secondary to the Buddha statue.

#### Context Rule

There is only one Buddha statue in the Garden.

That statue is located in the northwest corner.

This station should preserve that placement.

The image should not turn into a broad full-Garden overview.

The image should remain a focused station rendering centered on the single Buddha statue.

## Non-Canonical Mistakes to Avoid

- Showing visible buildings in a standard Garden rendering
- Omitting the meditation identity
- Omitting the raked sand Zen garden
- Omitting the stacked Zen stones
- Omitting the Buddha statue when it should be visible
- Adding more than one Buddha statue
- Placing the Buddha statue anywhere other than the northwest corner
- Making the Buddha statue monumental or oversized
- Making the Garden feel wet, muddy, slick, swampy, or waterlogged
- Making the Garden gloomy or oppressive
- Turning it into a large park
- Turning it into a farm
- Turning it into a public plaza
- Adding extra Garden doors
- Placing the Garden door on any wall other than the east wall
- Making the east-wall door the main focus of the standard west-facing rendering

---

# 12. Small Library

## Purpose

The Small Library is the final preparatory room before entering the Great Hall.

It represents understanding before exploration.

It is a compact, warm, human-scaled study room.

## Connections

```text
Entry Hall → Small Library → Foundational Door → Great Hall
```

The Small Library connects:

- South Door → Entry Hall
- North Door → Foundational Door / Great Hall

## Door Rules

The Small Library has exactly two canonical doors:

1. North Door
2. South Door

The north door is located on the north wall.

The south door is located on the south wall.

Both canonical doors should normally be shut in standard renderings unless an open-door connection is intentionally being shown.

No additional primary doors are canonical.

The Small Library is not a branching room.

Its canonical layout is linear and north-south.

## Viewing Directions

The Small Library has exactly two canonical standard viewing directions:

1. Facing North
2. Facing South

Only one primary door should be visible at a time.

A north-facing rendering shows the north door.

A south-facing rendering shows the south door.

## Required Features

The Small Library contains:

- Instruction Manual and Guest Book
- The Codex as a reference source
- introductory collections
- maps
- symbol references
- historical records
- reading tables
- lecterns
- shelves
- reference books
- writing tools
- map tables
- lamps or lanterns

## Material and Atmosphere

The Small Library should feel:

- compact
- warm
- quiet
- human-scaled
- focused
- preparatory
- lived-in
- welcoming
- studious

Wood should strongly soften the room.

The room should feel ancient, practical, cared for, and inhabited.

## Standard Rendering Rules

A standard Small Library rendering should show:

- one primary door
- warm compact human scale
- no extra exits
- no full circulation diagram
- Instruction Manual and Guest Book in the northeast corner when visible
- north door unobstructed when facing north

The large prominent display book in the Small Library is not the Codex.

It is the combined Instruction Manual and Guest Book.

## Open Door Display Rules

If the north door is open, the onward connection toward the Foundational Door and Great Hall should be visibly shown beyond the threshold.

The onward view should preserve the same facing direction as the Small Library rendering.

If the viewer is facing north, the space beyond the north door should appear as a forward continuation toward the Foundational Door and Great Hall, not as a reversed or unrelated view.

The view through the north door should include enough recognizable features to indicate the forward connection, such as:

- the Foundational Door
- a threshold passage leading toward the Great Hall
- glimpses of larger Great Hall architecture
- partial view of the Great Hall beyond when appropriate

If the south door is open, the Entry Hall should be visibly shown beyond the threshold.

The Entry Hall should appear from the direction created by the Small Library viewer position and the open south door.

The view should preserve spatial continuity and should not show the Entry Hall from an unrelated angle.

The view through the south door should include recognizable Entry Hall features such as:

- narrow corridor-like proportions
- warm lantern light
- side tables
- welcoming threshold atmosphere

## Instruction Manual and Guest Book

The large prominent display book in the Small Library is not the Codex.

The large display book is a combined:

- Instruction Manual
- Guest Book

It serves as the visitor's practical introduction to The Great Citadel and as a record of arrival.

It may include:

- Welcoming guidance for new visitors
- Orientation notes
- How to use the Citadel
- Suggested starting points
- Simple rules of conduct
- Reflections or signatures from prior visitors

It should feel practical, welcoming, and modestly ceremonial.

It should help bridge the transition from arrival to exploration.

The large Instruction Manual and Guest Book should be placed in the northeast corner of the Small Library.

It must not block the north door.

It should feel important and welcoming, but it should not obstruct the room's linear north-south movement.

## The Codex in the Small Library

The Codex remains one of the important contents of the Small Library, but it is not the large display book used to greet visitors.

The Codex may appear as:

- A protected reference volume
- A shelved master text
- A smaller lectern book
- A curated reference source within the room

The large visible book used to greet the visitor is the Instruction Manual and Guest Book.

## Stations

### Small Library — Instruction Manual Station

This station is a fixed viewpoint in the Small Library.

It is positioned just in front of the large Instruction Manual and Guest Book in the northeast corner of the room.

The view should look downward toward the book.

The Instruction Manual and Guest Book should be the primary object in the image.

It should occupy most of the frame.

The surrounding room may appear only as secondary context.

#### Purpose

This station is used to render the Instruction Manual and Guest Book as the primary subject.

It emphasizes:

- The importance of the book
- Its welcoming role
- Its instructional function
- Its identity as a guest-facing object

#### Framing Rule

From this station, the image should focus mainly on the Instruction Manual and Guest Book.

The camera/viewpoint should be slightly above normal reading height and angled downward toward the book.

The book should dominate the image.

The room should remain readable as the Small Library, but the room itself is not the primary subject.

#### Context Rule

The northeast corner location should remain clear.

The station should preserve the rule that the Instruction Manual and Guest Book does not block the north door.

If the north door appears at all, it should remain secondary and unobstructed.

The image should not turn into a full-room overview.

#### Approved Reference

The approved reference for this station is the focused rendering in which the Instruction Manual and Guest Book fills most of the frame, the view looks down on the open book, and the surrounding Small Library appears only as contextual background.

## Non-Canonical Mistakes to Avoid

- Showing more than one primary door at once in a standard rendering
- Showing open doors unless intentionally using the open-door connection rule
- Adding extra exits
- Making the Small Library feel like a hub
- Placing the Instruction Manual and Guest Book in the center of the room
- Blocking the north door with the book
- Treating the large display book as the Codex
- Rendering the room as grand, vast, or monumental
- Rendering the Instruction Manual Station as a full-room overview

---

# 13. Foundational Door

## Purpose

The Foundational Door connects the Small Library to the Great Hall.

It is one of the eight primary openings of the Great Hall.

It leads back to the Foundations rather than to a realm antechamber.

## Connections

```text
Small Library → Foundational Door → Great Hall
```

```text
Great Hall → Foundational Door → Small Library → Entry Hall
```

## Door Rules

The Foundational Door is the exception to the Antechamber Connection Principle.

It does not lead to an antechamber.

It leads between the Great Hall and the Foundations.

## Viewing Directions

No special standalone viewing directions are currently defined for the Foundational Door.

It may be rendered from:

- the Small Library side
- the Great Hall side

## Required Features

The Foundational Door should communicate threshold, return, and foundation.

It may include:

- old stone
- carved wood
- brass or bronze fittings
- foundational symbols
- threshold markings
- Palace Sigil or root/return motifs where appropriate

## Material and Atmosphere

It should feel consistent with both the Great Hall and Foundations.

It should feel old, important, warm, and practical.

## Standard Rendering Rules

The Foundational Door should not be represented as a realm door.

It should not imply an antechamber beyond it.

It should indicate the transition between the intimate Foundations and the larger Great Hall.

## Open Door Display Rules

If the Foundational Door is viewed open from the Small Library side, the Great Hall should be visibly shown beyond the threshold.

The view beyond should include recognizable Great Hall features such as:

- larger spatial scale
- Great Hall stone architecture
- the Great Knowledge Compass
- Palace Sigil elements
- banners or realm-facing architectural cues where appropriate

If the Foundational Door is viewed open from the Great Hall side, the Small Library should be visibly shown beyond the threshold.

The view beyond should include recognizable Small Library features such as:

- compact scale
- bookshelves
- warm study lighting
- reading or reference furnishings

## Stations

No formal Foundational Door stations are defined yet.

## Non-Canonical Mistakes to Avoid

- Treating the Foundational Door as a realm door
- Showing it leading to an antechamber
- Disconnecting it from the Small Library
- Showing an open Foundational Door without recognizable connected space beyond it

---

# 14. Great Hall

## Purpose

The Great Hall is the central navigation chamber of The Great Citadel.

It is the symbolic and navigational heart of exploration.

All major journeys into the greater Citadel begin here.

## Connections

The Great Hall connects to:

- North: Science Door → Hall of Discovery → Science Realm
- Northeast: Philosophy Door → Philosophy Antechamber → Philosophy Realm
- East: Arts Door → Arts Antechamber → Arts Realm
- Southeast: Personal Door → Personal Antechamber → Personal Realm
- South: Foundational Door → Small Library → Entry Hall
- Southwest: Inventor's Door → Inventor's Antechamber → Inventor's Realm
- West: Media Door → Media Antechamber → Media Realm
- Northwest: History Door → History Antechamber → History Realm

## Door Rules

The Great Hall contains eight primary openings:

1. Media Door
2. Science Door
3. History Door
4. Philosophy Door
5. Arts Door
6. Personal Door
7. Inventor's Door
8. Foundational Door

Seven lead to major realms of knowledge through antechambers.

One leads to the Foundations.

## Viewing Directions

Every Great Hall rendering must specify a viewing direction.

Possible standard directions:

- Facing North
- Facing Northeast
- Facing East
- Facing Southeast
- Facing South
- Facing Southwest
- Facing West
- Facing Northwest

## Required Features

The Great Hall should include:

- Palace Sigil
- Great Knowledge Compass
- eight primary openings
- domain medallions
- door tracks
- ancient stonework
- brass mechanisms
- banners where appropriate

## Material and Atmosphere

The Great Hall should feel larger than the viewer.

It should emphasize:

- height
- stonework
- arches
- brass mechanisms
- the Palace Sigil
- the Great Knowledge Compass

It should feel ancient, massive, lived-in, warm, and inhabited.

## Standard Rendering Rules

The Great Hall is not a map.

The Great Hall is an architectural experience.

The viewer stands at or near the geometric center of the Great Hall.

The viewer stands upon the Great Knowledge Compass.

Only the forward half of the chamber should be visible.

Visible doors:

- Minimum: 1
- Preferred: 2–3
- Maximum: 4

A rendering that reveals all eight doors is non-canonical.

## Facing North Rendering Rule

When facing north, visible elements may include:

- Science Door at center
- Portions of History Door
- Portions of Philosophy Door
- Upper architecture
- Part of the Great Knowledge Compass
- Palace Sigil details
- Banners related to Science, History, or Philosophy

Not normally visible:

- Foundational Door
- Media Door
- Arts Door
- Inventor's Door
- Personal Door

## Open Door Display Rules

Any visible room or antechamber shown beyond an open Great Hall door should preserve the viewer's current facing direction.

The destination should appear as a continuation through that specific door, not as an independent view of the destination room from another angle.

For example, if the Great Hall is rendered facing north and the Science Door is open, the Hall of Discovery should appear as seen through the Science Door from the Great Hall, aligned with the viewer's northward line of sight.

If the Science Door is open, the Hall of Discovery should be visibly shown beyond the threshold.

Recognizable Hall of Discovery features may include:

- the Map of Understanding
- scientific architecture
- the Celestial Vault atmosphere
- inquiry-related visual cues

If the Philosophy Door is open, the Philosophy Antechamber should be visibly shown beyond the threshold.

The view should include thematically appropriate philosophical cues consistent with the destination.

If the Arts Door is open, the Arts Antechamber should be visibly shown beyond the threshold.

The view should include thematically appropriate artistic cues consistent with the destination.

If the Personal Door is open, the Personal Antechamber should be visibly shown beyond the threshold.

The view should include thematically appropriate personal or reflective cues consistent with the destination.

If the Foundational Door is open, the Small Library should be visibly shown beyond the threshold.

Recognizable Small Library features should be visible.

If the Inventor's Door is open, the Inventor's Antechamber should be visibly shown beyond the threshold.

The view should include thematically appropriate inventive or mechanical cues consistent with the destination.

If the Media Door is open, the Media Antechamber should be visibly shown beyond the threshold.

The view should include thematically appropriate storytelling or media-related cues consistent with the destination.

If the History Door is open, the History Antechamber should be visibly shown beyond the threshold.

The view should include thematically appropriate historical cues consistent with the destination.

## Banner Rules

Banners serve as architectural identity markers, not modern signs.

They should be aged, symbolic, physically attached to the architecture, and should use symbols more than text.

Banners in the Great Hall are memory-bearing architectural textiles.

They should help the visitor feel oriented inside The Great Citadel while preserving mystery, age, warmth, and discovery.

## Stations

No formal Great Hall stations are defined yet.

## Non-Canonical Mistakes to Avoid

- Rendering the Great Hall as a complete map
- Showing all eight doors at once
- Using a bird's-eye view for standard room renderings
- Showing the entire Great Knowledge Compass from normal standing perspective
- Using floating labels instead of integrated signs, inscriptions, or banners
- Showing an open door without the connected room or antechamber visible beyond it

---

# 15. Hall of Discovery

## Purpose

The Hall of Discovery is the antechamber of the Science Realm.

It introduces visitors to Astronomy, Biology, and Logic.

It represents inquiry before specialization.

## Connections

The Hall of Discovery connects to:

- South: Science Door → Great Hall
- North: Astronomy Door
- West: Biology Door
- East: Logic Door

## Door Rules

The Hall of Discovery has four primary doors:

```text
                NORTH

           Astronomy Door

Biology Door       Logic Door

            Science Door

                SOUTH
```

## Viewing Directions

No additional specialized Hall of Discovery viewing rules are currently defined beyond the global rendering standards.

The room may be rendered from visitor perspective facing any defined door direction.

## Required Features

The Hall of Discovery should include:

- Map of Understanding
- Compass Rose of Discovery
- Celestial Vault
- Eight Alcoves of Discovery

## Material and Atmosphere

The Hall of Discovery should feel:

- scientific
- elegant
- functional
- medieval
- timeless
- inquisitive
- orderly
- inspiring

It should introduce inquiry itself before specialization.

## Standard Rendering Rules

The floor contains the Map of Understanding.

The Map of Understanding represents scientific knowledge and its relationships.

The ceiling forms the Celestial Vault.

The Celestial Vault may include:

- constellations
- planetary paths
- lunar cycles
- seasonal markers
- astronomical symbols
- scientific inscriptions

All elements should appear handcrafted and integrated into the architecture.

## Open Door Display Rules

If the Science Door is open, the Great Hall should be visibly shown beyond the threshold.

Recognizable Great Hall features may include:

- larger scale
- Great Hall stonework
- part of the Great Knowledge Compass
- Palace Sigil geometry
- Great Hall architectural identity

If the Astronomy Door is open, the Astronomy Realm beyond should be visibly suggested through recognizable astronomy-related cues such as:

- celestial instruments
- observatory architecture
- star charts
- astrolabes
- cosmic or navigational study elements

If the Biology Door is open, the Biology Realm beyond should be visibly suggested through recognizable biology-related cues such as:

- living plants
- conservatory atmosphere
- botanical collections
- natural-history elements

If the Logic Door is open, the Logic Realm beyond should be visibly suggested through recognizable logic-related cues such as:

- geometric structures
- mathematical models
- brass analytical devices
- orderly pattern-based architectural cues

## Stations

No formal Hall of Discovery stations are defined yet.

## Non-Canonical Mistakes to Avoid

- Including the Star Whale
- Turning alcoves into freestanding displays, kiosks, islands, detached structures, or center-room furniture
- Omitting the Map of Understanding
- Omitting the Celestial Vault when it should be visible
- Showing open doors without recognizable connected spaces beyond them

---

# 16. Science Realm Doors and Alcoves

## Astronomy Door

Direction: North

Symbol: Astrolabe

Leads toward:

- Astronomy Tower
- Celestial Archives
- Cosmology Collections
- Navigation Observatories
- Star Mapping Halls

## Biology Door

Direction: West

Symbol: Leaf and Branch

Leads toward:

- Biological Conservatory
- Botanical Gardens
- Natural History Archives
- Living Systems Galleries
- Evolution Collections

## Logic Door

Direction: East

Symbol: Compass and Straightedge

Leads toward:

- Hall of Mathematics
- Geometry Archives
- Logic Chambers
- Pattern Galleries
- Algorithm Workshops
- Mechanical Computation Gallery
- Time Traveler Logic Engines

Modern computation should be represented through:

- Brass analytical engines
- Mechanical calculators
- Clockwork reasoning machines
- Time Traveler modifications

The Logic Realm should feel ancient, elegant, and intellectual rather than technological.

## Alcove Rule

Each primary door in the Hall of Discovery owns two alcoves.

Alcoves are architectural recesses built into perimeter walls.

They are not:

- Freestanding displays
- Kiosks
- Islands
- Detached structures
- Furniture placed within the center of a room

Alcoves should always appear as part of the room's perimeter architecture.

## Astronomy Alcoves

The two alcoves associated with the Astronomy Door contain:

- Planet models
- Celestial globes
- Star charts
- Constellation diagrams
- Astrolabes
- Orbital maps
- Lunar cycle displays
- Navigation instruments

## Biology Alcoves

The two alcoves associated with the Biology Door contain:

- Living plants
- Ferns
- Mosses
- Vines
- Botanical specimens
- Herb collections
- Seed archives
- Small trees and growth displays

## Logic Alcoves

The two alcoves associated with the Logic Door contain:

- Geometric constructions
- Mathematical models
- Tessellations
- Pattern demonstrations
- Mechanical puzzles
- Brass calculating devices
- Compass-and-straightedge studies

## Science Alcoves

The two alcoves associated with the Science Door contain:

- Observation journals
- Research notes
- Measuring instruments
- Experimental sketches
- Scientific records
- Unanswered questions

---

# 17. Arts Antechamber

## Purpose

The Arts Antechamber is the transitional room between the Great Hall and the Arts Realm.

It introduces making, beauty, image, performance, music, craft, color, writing, and expression.

It is not the full Arts Realm.

It is the threshold where the visitor first encounters the creative life of The Great Citadel.

The Arts Antechamber is a four-door creative orientation room.

It receives the visitor from the Great Hall and offers three primary artistic paths:

- Music
- Writing
- Visual

## Connections

```text
Great Hall → Arts Door → Arts Antechamber
```

From the Arts Antechamber:

```text
Arts Antechamber → Music Door → Music path / Music Halls
Arts Antechamber → Writing Door → Writing path / Literary Arts Halls
Arts Antechamber → Visual Door → Visual Arts path / Visual Arts Halls
Arts Antechamber → Great Hall Door → Arts Door → Great Hall
```

## Door Rules

The Arts Antechamber has four canonical doors:

1. Music Door
2. Writing Door
3. Visual Door
4. Great Hall Door

No additional Arts Antechamber doors are canonical unless later defined.

## Door Placement Rule

The Arts Antechamber has four canonical doors placed by compass direction:

```text
North wall: Music Door
East wall: Writing Door
South wall: Visual Door
West wall: Great Hall Door
```

Compass layout:

```text
                 NORTH

              Music Door

WEST                                      EAST

Great Hall Door                    Writing Door

              Visual Door

                 SOUTH
```

## Viewing Directions

The Arts Antechamber follows the General Antechamber Standards.

The viewer stands at or near the geometric center of the room.

Each rendering must specify a facing direction.

Only the forward hemisphere should be shown.

The Arts Antechamber should not show all four doors in a standard rendering.

The primary visible door should be the door on the wall being faced.

This means:

```text
Facing North → Music Door is primary
Facing East → Writing Door is primary
Facing South → Visual Door is primary
Facing West → Great Hall Door is primary
```

## Required Features

The Arts Antechamber should include:

- carved wood display panels
- framed sketches or studies
- small sculptures
- pigments or paint bowls
- parchment studies
- musical instruments as secondary details when not facing the Music Door
- masks or theatrical objects
- woven textiles or banners
- warm lantern light
- benches or worktables
- Music Door on north wall
- Writing Door on east wall
- Visual Door on south wall
- Great Hall Door on west wall

## Core Identity

The Arts Antechamber should feel like a warm, human-scaled studio-gallery inside the ancient Citadel.

It should contain signs of many arts, but it should not become cluttered or chaotic.

It should feel crafted, expressive, welcoming, and alive with creative possibility.

It should remain an antechamber, not the full Arts Realm.

## Material and Atmosphere

The Arts Antechamber should feel:

- warm
- crafted
- expressive
- intimate
- human-scaled
- creative
- welcoming
- visually alive
- ancient but actively used

It should suggest many creative paths without becoming the full Arts Realm.

## Standard Rendering Rules

Render the Arts Antechamber as a threshold room, not as a full museum, theater, or workshop.

The room should feel small enough to be intimate but rich enough to suggest many forms of art beyond it.

The viewer should stand near the geometric center.

The rendering should face one compass direction at a time.

Do not render all four Arts Antechamber doors in a standard room image unless a map, diagram, or special overview is explicitly requested.

When facing east, the Writing Door should be the primary door and writing-related cues should dominate the forward wall.

When facing north, the Music Door should be the primary door and music-related cues should dominate the forward wall.

When facing south, the Visual Door should be the primary door and visual-arts cues should dominate the forward wall.

When facing west, the Great Hall Door should be the primary door and Great Hall cues may be visible beyond it if the door is open.

## Open Door Display Rules

If the Great Hall Door is open, the Great Hall should be visibly shown beyond the threshold.

If the Music Door is open, the space beyond should show recognizable music-related cues such as:

- instruments
- music stands
- parchment sheet music
- carved acoustic wood
- warm performance or practice-room atmosphere

If the Writing Door is open, the space beyond should show recognizable writing or literary cues such as:

- writing desks
- manuscripts
- parchment
- ink bottles
- shelves of bound works
- quiet scriptorium atmosphere

If the Visual Door is open, the space beyond should show recognizable visual-arts cues such as:

- paintings
- sketches
- pigments
- canvases
- sculpture studies
- carved display panels
- studio-gallery atmosphere

All open-door views should preserve directional continuity with the current viewer position and facing direction.

If facing north and the Music Door is open, the Music path should be visible beyond it from the same north-facing perspective.

If facing east and the Writing Door is open, the Writing path should be visible beyond it from the same east-facing perspective.

If facing south and the Visual Door is open, the Visual Arts path should be visible beyond it from the same south-facing perspective.

If facing west and the Great Hall Door is open, the Great Hall should be visible beyond it from the same west-facing perspective.

## Stations

No formal Arts Antechamber stations are defined yet.

## Non-Canonical Mistakes to Avoid

- showing fewer or more than four canonical Arts Antechamber doors unless intentionally cropped by viewpoint
- omitting the Music Door
- omitting the Writing Door
- omitting the Visual Door
- omitting the Great Hall Door
- placing any Arts Antechamber door on the wrong compass wall
- showing all four doors in a standard rendering
- making the Arts Antechamber feel like the full Arts Realm
- making it a modern museum
- making it a giant theater
- making it a messy workshop
- making it a royal gallery
- making it cold, empty, or marble-only
- omitting crafted, human-scaled creative details
- showing open doors without recognizable connected spaces beyond them
- showing connected spaces from contradictory perspectives

---

# 18. Future Antechambers

Major realm doors do not open directly into fully developed realms.

Each primary realm door from the Great Hall opens first into an antechamber.

An antechamber is a transitional room that introduces the identity, atmosphere, symbols, and major paths of its realm.

Antechambers serve as orientation spaces between the Great Hall and deeper realm destinations.

The Foundational Door is the exception to the Antechamber Connection Principle.

## Media Antechamber

### Purpose

The Media Antechamber is the transitional room between the Great Hall and the Media Realm.

It introduces storytelling, transmission, memory, images, signals, and recorded experience.

### Connections

```text
Great Hall → Media Door → Media Antechamber → Media Realm
```

### Door Rules

The Media Antechamber has a Great Hall-facing doorway and an onward realm-facing doorway unless later refined.

### Viewing Directions

The Media Antechamber follows the General Antechamber Standards.

### Required Features

Not yet fully specified.

### Material and Atmosphere

The Media Antechamber should feel consistent with storytelling, memory, signal, and framed experience.

### Standard Rendering Rules

Render as a transitional antechamber, not the full Media Realm.

### Open Door Display Rules

If the Great Hall-facing doorway is open, the Great Hall should be visibly shown beyond the threshold.

If an onward realm doorway is open, the space beyond should show recognizable media-related cues consistent with the Media Realm.

### Stations

No formal Media Antechamber stations are defined yet.

### Non-Canonical Mistakes to Avoid

- Treating the antechamber as the full Media Realm
- Showing open doors without recognizable connected spaces beyond them

## History Antechamber

### Purpose

The History Antechamber is the transitional room between the Great Hall and the History Realm.

It introduces archives, timelines, memory, records, ruins, and preserved events.

### Connections

```text
Great Hall → History Door → History Antechamber → History Realm
```

### Door Rules

The History Antechamber has a Great Hall-facing doorway and an onward realm-facing doorway unless later refined.

### Viewing Directions

The History Antechamber follows the General Antechamber Standards.

### Required Features

Not yet fully specified.

### Material and Atmosphere

The History Antechamber should feel archival, timeworn, layered, and memory-bearing.

### Standard Rendering Rules

Render as a transitional antechamber, not the full History Realm.

### Open Door Display Rules

If the Great Hall-facing doorway is open, the Great Hall should be visibly shown beyond the threshold.

If an onward realm doorway is open, the space beyond should show recognizable history-related cues consistent with the History Realm.

### Stations

No formal History Antechamber stations are defined yet.

### Non-Canonical Mistakes to Avoid

- Treating the antechamber as the full History Realm
- Showing open doors without recognizable connected spaces beyond them

## Philosophy Antechamber

### Purpose

The Philosophy Antechamber is the transitional room between the Great Hall and the Philosophy Realm.

It introduces questions, contemplation, argument, ethics, metaphysics, and meaning.

### Connections

```text
Great Hall → Philosophy Door → Philosophy Antechamber → Philosophy Realm
```

### Door Rules

The Philosophy Antechamber has a Great Hall-facing doorway and an onward realm-facing doorway unless later refined.

### Viewing Directions

The Philosophy Antechamber follows the General Antechamber Standards.

### Required Features

Not yet fully specified.

### Material and Atmosphere

The Philosophy Antechamber should feel contemplative, ordered, quiet, and thoughtful.

### Standard Rendering Rules

Render as a transitional antechamber, not the full Philosophy Realm.

### Open Door Display Rules

If the Great Hall-facing doorway is open, the Great Hall should be visibly shown beyond the threshold.

If an onward realm doorway is open, the space beyond should show recognizable philosophy-related cues consistent with the Philosophy Realm.

### Stations

No formal Philosophy Antechamber stations are defined yet.

### Non-Canonical Mistakes to Avoid

- Treating the antechamber as the full Philosophy Realm
- Showing open doors without recognizable connected spaces beyond them

## Personal Antechamber

### Purpose

The Personal Antechamber is the transitional room between the Great Hall and the Personal Realm.

It introduces memory, identity, reflection, inner life, personal history, and self-understanding.

### Connections

```text
Great Hall → Personal Door → Personal Antechamber → Personal Realm
```

### Door Rules

The Personal Antechamber has a Great Hall-facing doorway and an onward realm-facing doorway unless later refined.

### Viewing Directions

The Personal Antechamber follows the General Antechamber Standards.

### Required Features

Not yet fully specified.

### Material and Atmosphere

The Personal Antechamber should feel reflective, intimate, inward-facing, and emotionally resonant.

### Standard Rendering Rules

Render as a transitional antechamber, not the full Personal Realm.

### Open Door Display Rules

If the Great Hall-facing doorway is open, the Great Hall should be visibly shown beyond the threshold.

If an onward realm doorway is open, the space beyond should show recognizable personal, reflective, or inward-facing cues consistent with the Personal Realm.

### Stations

No formal Personal Antechamber stations are defined yet.

### Non-Canonical Mistakes to Avoid

- Treating the antechamber as the full Personal Realm
- Showing open doors without recognizable connected spaces beyond them

## Inventor's Antechamber

### Purpose

The Inventor's Antechamber is the transitional room between the Great Hall and the Inventor's Realm.

It introduces invention, mechanisms, tools, experiments, prototypes, workshop thinking, and Time Traveler modifications.

### Connections

```text
Great Hall → Inventor's Door → Inventor's Antechamber → Inventor's Realm
```

### Door Rules

The Inventor's Antechamber has a Great Hall-facing doorway and an onward realm-facing doorway unless later refined.

### Viewing Directions

The Inventor's Antechamber follows the General Antechamber Standards.

### Required Features

Not yet fully specified.

### Material and Atmosphere

The Inventor's Antechamber should feel mechanical, clever, experimental, warm, and workshop-like while remaining part of the ancient Citadel.

### Standard Rendering Rules

Render as a transitional antechamber, not the full Inventor's Realm.

### Open Door Display Rules

If the Great Hall-facing doorway is open, the Great Hall should be visibly shown beyond the threshold.

If an onward realm doorway is open, the space beyond should show recognizable inventive, workshop, or mechanical cues consistent with the Inventor's Realm.

### Stations

No formal Inventor's Antechamber stations are defined yet.

### Non-Canonical Mistakes to Avoid

- Treating the antechamber as the full Inventor's Realm
- Making it feel modern or technological instead of ancient, mechanical, and handcrafted
- Showing open doors without recognizable connected spaces beyond them

---

# 19. Symbols and Floor Systems

## Palace Sigil

The Palace Sigil is the highest symbol of The Great Citadel.

It takes the form of a simple eight-spoked ship's helm inspired by traditional Buddhist wheel symbolism.

Characteristics:

- Circular form
- Eight spokes
- Strong silhouette
- Balanced geometry
- Immediate recognizability

The design should feel:

- Ancient
- Timeless
- Functional
- Calm
- Purposeful

The Palace Sigil represents guidance rather than destination.

The Citadel does not dictate what visitors should learn. It provides pathways through knowledge.

## Great Knowledge Compass

The Great Knowledge Compass is the floor of the Great Hall and one of the oldest known artifacts in the Citadel.

At its center is the Palace Sigil.

Its spokes extend outward through:

1. Palace Sigil
2. Domain Medallion
3. Door Track
4. Primary Opening

## Compass Rose of Discovery

The Compass Rose of Discovery sits at the center of the Map of Understanding in the Hall of Discovery.

It aligns:

- North → Astronomy Door
- East → Logic Door
- South → Science Door
- West → Biology Door

The Compass Rose is fixed within the architecture. It does not rotate based on the viewer.

---

# 20. Current Canonical Status

Canonical world name:

- The Great Citadel

Active Codex:

- Codex v1.5 — Rendering Continuity and Arts Antechamber Edition

Current Foundation rooms:

1. Entry Hall
2. Garden
3. Small Library
4. Foundational Door
5. Great Hall

Current defined rooms and antechambers:

1. Entry Hall
2. Garden
3. Small Library
4. Great Hall
5. Hall of Discovery
6. Media Antechamber
7. History Antechamber
8. Philosophy Antechamber
9. Arts Antechamber
10. Personal Antechamber
11. Inventor's Antechamber

Current defined stations:

1. Small Library — Instruction Manual Station
2. Garden — Buddha Statue Station

Retired room names:

- Front Entry
- Hallway

Rejected or non-canonical concepts:

- The Star Whale is not canonical.
- The former statement that “The Great Citadel naming change was rolled back” is superseded by v1.2 and later.
- The canonical project/world name is The Great Citadel.
- The large prominent display book in the Small Library is not the Codex; it is the Instruction Manual and Guest Book.
- A Small Library rendering that shows both doors at once is non-canonical.
- A standard Small Library rendering with an open door is non-canonical unless a later rule explicitly allows an exception.
- A Great Hall rendering that shows all eight primary openings at once is non-canonical.
- A Garden standard rendering with visible buildings is non-canonical.
- A Garden standard rendering that omits the raked sand Zen garden, stacked Zen stones, or single northwest-corner Buddha statue is non-canonical.
- An Arts Antechamber standard rendering that shows all four doors at once is non-canonical unless explicitly requested as a map, diagram, or special overview.
- An open doorway that shows the connected room from a contradictory or unrelated perspective is non-canonical.

---

# 21. Changelog

## v1.5 — Rendering Continuity and Arts Antechamber Edition

Created a new full-copy standalone Codex version.

Preserved v1.4 and consolidated the recent local working updates.

Added the Image Format Rule requiring standard room renderings, station renderings, and Codex visual references to default to 16:9 horizontal landscape format unless otherwise requested.

Added global Doorway Display Rule.

Added global Doorway Identification Rule.

Added Directional Continuity Through Doorways Rule.

Added Connected Room Perspective Rule.

Updated the room-section template to include Open Door Display Rules.

Added General Antechamber Standards, including:

- Purpose of Antechambers
- Antechamber Observer Position Rule
- Antechamber Viewing Angle Rule
- Antechamber Door Visibility Rule
- Antechamber Compass Door Rule
- Antechamber Open Door Display Rule
- Antechamber Directional Continuity Rule
- Antechamber Scale Rule
- Antechamber Identity Rule

Updated Entry Hall:

- Entry Hall now has exactly three canonical doors.
- North Door leads to Small Library.
- South Door leads to Outside / Arrival.
- West Door leads to Garden.
- Entry Hall West Door connects to Garden East Door.
- Entry Hall remains a narrow welcoming passage and not a hub.

Updated Garden:

- Garden has exactly one Buddha statue.
- The Buddha statue is located in the northwest corner.
- No additional Buddha statues are canonical.
- Added Garden — Buddha Statue Station.
- Buddha Statue Station is positioned directly in front of the northwest-corner Buddha statue.
- Buddha Statue Station uses eye-level framing and the statue fills most of the image.

Updated Arts Antechamber:

- Defined Arts Antechamber as a four-door creative orientation room.
- North wall: Music Door.
- East wall: Writing Door.
- South wall: Visual Door.
- West wall: Great Hall Door.
- Defined Arts Antechamber facing-direction rules.
- Facing North makes the Music Door primary.
- Facing East makes the Writing Door primary.
- Facing South makes the Visual Door primary.
- Facing West makes the Great Hall Door primary.
- Added Arts Antechamber Open Door Display Rules for Music, Writing, Visual, and Great Hall doors.
- Clarified that standard Arts Antechamber renderings should not show all four doors at once.

## v1.4 — Garden Meditation Edition

Created a new full-copy standalone Codex version.

Replaced the previous patched Garden theme with a refined meditation-garden identity.

Preserved the Garden orientation and room connection rules:

- The Garden connects through the Entry Hall side door.
- The Garden has one canonical door.
- The Garden door is on the east wall.
- Standard Garden renderings face west on the map.

Defined the Garden as a meditation garden.

Added required Garden features:

- Open sky
- Warm daylight
- Raked sand Zen garden
- Stacked Zen stones
- Small Buddha statue
- Modest living plants
- Vines or moss on old stone where appropriate
- Lanterns or small garden lights
- Old Citadel stone details
- Calm, happy, restorative atmosphere

Removed the prior required path identity from the Garden section.

Added the Building Visibility Rule: no buildings should be visible in standard Garden renderings.

Added the Dryness Rule: the Garden should not look wet, muddy, slick, swampy, or waterlogged.

Clarified that a distant mountain view may remain as a background feature but should not dominate the Garden.

Added non-canonical Garden mistakes including visible buildings, missing meditation identity, missing raked sand, missing Zen stones, missing Buddha statue, oversized Buddha statue, and extra Garden doors.

## v1.3 — Station Rendering Edition

Created a new full-copy standalone Codex version.

Refactored the Codex structure for image rendering.

Moved generalized room and rendering standards to the top.

Added Global Station Standards.

Added the Station Concept:

- A station is a fixed viewpoint inside a room.
- A station focuses on a particular object, feature, or area of a room.
- A station defines viewer position, viewing direction, focal object, framing, and purpose.

Added the Station Override Rule allowing stations to override normal central-viewing when a focused object study is required.

Added the Room Section Template:

- Purpose
- Connections
- Door Rules
- Viewing Directions
- Required Features
- Material and Atmosphere
- Standard Rendering Rules
- Stations
- Non-Canonical Mistakes to Avoid

Reorganized room-specific information into self-contained sections.

Added the first formal station:

- Small Library — Instruction Manual Station

Defined the Small Library — Instruction Manual Station as a fixed viewpoint just in front of the large Instruction Manual and Guest Book in the northeast corner of the Small Library.

Defined that the station view should look downward toward the book, with the Instruction Manual and Guest Book occupying most of the frame.

Added the approved visual reference principle for the station: the book dominates the image while the surrounding Small Library remains only as contextual background.

No prior v1.2 canon content was intentionally removed; the change was organizational plus the addition of station-based rendering standards.

## v1.2 — Great Citadel Foundations Edition

Created a new full-copy standalone Codex version.

Changed canonical world name from The Living Mind Palace to The Great Citadel.

Added local/GitHub save protocol.

Retired Front Entry and Hallway as separate active rooms.

Unified Front Entry, Entry Hall, and Hallway into the single canonical Entry Hall.

Updated the Foundations north-south sequence to:

```text
Great Hall → Foundational Door → Small Library → Entry Hall
```

Updated the main visitor path to:

```text
Entry Hall → Small Library → Foundational Door → Great Hall
```

Moved Garden branch connection to the Entry Hall.

Added Antechamber Connection Principle for all Great Hall realm doors except the Foundational Door.

Added Entry Hall spatial and atmosphere standards.

Revised universal room look-and-feel standards to emphasize wood, cozy human scale, warmth, plants, vines, moss, and inhabited character.

Added Great Hall Rendering Standards.

Added Great Hall Banner Standards.

Codified the Small Library as a compact linear preparatory room with exactly two doors: north to Foundational Door / Great Hall and south to Entry Hall.

Added Small Library viewing rules.

Added Small Library door state rule.

Changed the large prominent display book in the Small Library from the Codex to the Instruction Manual and Guest Book.

Placed the Instruction Manual and Guest Book in the northeast corner, where it must not block the north door.

Clarified that the Codex may remain in the Small Library as a protected reference volume, shelved master text, smaller lectern book, or curated reference source.

## v1.1 — Entry Hall Edition

Created a new full-copy standalone Codex version.

Added Entry Hall as a formal foundational room between the Front Entry and Hallway.

Defined the Entry Hall's purpose, spatial role, visual character, symbolism, inscriptions, and rendering rule.

Updated the canonical Foundations north-south sequence to include Entry Hall.

Updated the current canonical room list and room identity table.

## v1.0 — Discovery Edition

Initial full-copy canonical Codex version.

Included the Foundations, Great Hall, Palace Sigil, Science Realm, Hall of Discovery, Map of Understanding, Compass Rose of Discovery, Celestial Vault, Eight Alcoves of Discovery, and universal rendering standards.
