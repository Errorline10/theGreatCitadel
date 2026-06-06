# The Codex v1.6 — Garden, Map, and Media Antechamber Edition

## The Great Citadel

**Status:** Current canonical version  
**Versioning model:** Full-copy standalone Codex version  
**Canonical world name:** The Great Citadel  
**Source:** Supersedes Codex v1.5 — Rendering Continuity and Arts Antechamber Edition  

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

### Codex v1.5 — Rendering Continuity and Arts Antechamber Edition
Preserved v1.4 and consolidated doorway continuity, general antechamber standards, Entry Hall three-door layout, Garden Buddha station, Arts Antechamber compass layout, and 16:9 rendering rules.

### Codex v1.6 — Garden, Map, and Media Antechamber Edition
Preserves v1.5 and consolidates the latest local working updates:

- all rooms can be rendered from all eight compass directions
- map rendering has a dedicated Codex section
- Codex maps use 1:1 square format by default
- approved known-rooms map visual direction added
- Garden wall, mountain view, steampunk blimps, and direction-specific Buddha visibility rules added
- approved Garden east-facing visual direction added
- Media Antechamber door layout, identity, features, and door-specific visual identities added

---

# 3. Versioning System and Saving Protocol

Every Codex version is a complete standalone copy of the full document.

A version should include all foundational rooms, defined realms, symbols, rendering rules, accepted amendments, current architectural standards, version number, title, and changelog.

No version depends on another version to be understood.

Branches may experiment, but only full Codex copies are promoted into the MAIN archive.

Local Codex files are working drafts and may be overwritten during editing.

The Codex version number does not change for local-only edits.

The no-overwrite-history rule applies only when saving or publishing the Codex to GitHub.

When the user asks to save the Codex to GitHub, the Codex version number must increment, a changelog entry must be added, and the previous state must be preserved through Git history.

---

# 4. Global Room and Rendering Standards

## Image Format Rule

All standard room renderings, station renderings, and Codex visual references should be rendered in a 16:9 horizontal format unless a different format is explicitly requested.

The default image format for standard room and station renderings is 16:9 landscape.

Non-16:9 formats should only be used for special cases such as maps, diagrams, vertical object studies, icons, sigils, or explicitly requested alternate compositions.

## Eight-Direction Room Viewing Rule

Every room in The Great Citadel should be renderable from all eight compass directions unless a station rule, map rule, diagram rule, or explicit room-specific exception overrides this.

The eight standard compass directions are:

- North
- Northeast
- East
- Southeast
- South
- Southwest
- West
- Northwest

A room may still have a preferred or default rendering direction, but that does not prevent alternate compass-facing renderings from being valid.

When a room is rendered from any of the eight compass directions:

- the viewer should stand inside the room
- the viewer should normally stand at or near the geometric center
- the viewer should face the requested compass direction
- only the forward hemisphere should be shown
- doors, features, and connected spaces should remain fixed to their canonical compass positions
- the room should not rotate for convenience
- the viewer rotates; the room does not

## Visitor Perspective Principle

All rooms should be rendered from the perspective of a visitor physically present within the space.

The viewer should feel: I am standing in this room.

The viewer should not feel: I am looking at a diagram of this room.

## Central Viewing Principle — Expanded

When rendering a room from visitor perspective, the viewer should be positioned at or near the geometric center of the room unless a room-specific rule or station rule overrides this.

Only the viewing direction changes.

Rooms should be renderable from all eight compass directions.

The room remains fixed to the map.

The viewer turns to face the requested direction.

## Forward Hemisphere Rule — Expanded

The viewer should only see the portion of the room in front of them.

Architecture behind the viewer remains unseen.

This applies to all eight compass-facing renderings.

A north-facing view shows the northern forward hemisphere.

An east-facing view shows the eastern forward hemisphere.

A southwest-facing view shows the southwest forward hemisphere.

A rendering should not show the full room unless explicitly requested as a map, diagram, architectural overview, or special non-standard reference.

## Fixed Compass Architecture Rule

Room architecture is fixed to the room's canonical compass layout.

Doors and major features do not move between renderings.

When the viewer changes direction, the viewer rotates in place; the room itself does not rotate.

A door assigned to the north wall remains on the north wall in every rendering.

A door assigned to the east wall remains on the east wall in every rendering.

A rendering should never relocate a door, altar, statue, station, or major room feature for visual convenience.

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

Recognizable features may include furniture, bookshelves, floor systems, lighting character, banners, plants, symbols, room scale, or architectural identity.

## Directional Continuity Through Doorways Rule

When a rendering shows a connected room through an open doorway, the visible room beyond the threshold should be presented from a direction consistent with the current viewer position and facing direction.

The connected room should feel like a natural continuation of the viewer's current line of sight.

The next room should not appear from an unrelated, opposite, or contradictory perspective.

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

Examples: Great Knowledge Compass, Map of Understanding, future realm maps, navigation mosaics.

The viewer should feel they are standing upon the artifact rather than observing it from above.

## Visible Ceiling Rule

Whenever a room contains a significant ceiling feature, that feature should be included when practical.

## No Omniscient Perspective Rule

Avoid bird's-eye views, floating camera angles, ceiling-level viewpoints, and impossible perspectives.

Exceptions include maps, blueprints, architectural diagrams, Codex reference illustrations, and approved station views that require a focused downward angle while remaining physically plausible.

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

Common materials include stone, timber, carved wood, brass, bronze, leather, parchment, water, living plants, vines, and moss.

Subtle Time Traveler modifications may appear throughout the Citadel.

## Cozy Human Scale Rule

Rooms should generally feel comfortable to occupy.

Even when the architecture is old, ceremonial, or important, most rooms should retain a smaller human scale.

Preferred qualities include warmth, shelter, intimacy, readable proportions, places to sit/study/rest/reflect, wood details that soften stone architecture, lanterns, hearth light, and warm indirect illumination.

## Wood Emphasis Rule

Rooms should make greater use of wood: beams, railings, doors, wall panels, shelves, tables, benches, ceiling ribs, carved screens, decorative trim, and warm architectural framing.

Stone remains foundational, but wood should add warmth, texture, and human presence.

## Plant and Vine Integration Rule

Plants, vines, moss, and living greenery may appear throughout the Citadel.

Some walls may include climbing vines, small plants, or signs of nature reclaiming the architecture.

Plant life should feel integrated, not random.

Heavy plant growth should be strongest in gardens, biology-related spaces, older corridors, and rooms connected to reflection or restoration.

## Archaeology Principle

Every room should show evidence of age and history: repairs, additions, modifications, patina, worn stone, and updated mechanisms.

Nothing should appear newly constructed.

## Room Identity Principle

Every major room should possess at least one defining architectural feature.

| Room | Defining Feature |
|---|---|
| Great Hall | Great Knowledge Compass |
| Hall of Discovery | Map of Understanding and Celestial Vault |
| Small Library | Instruction Manual and Guest Book; Codex reference source |
| Garden | Raked sand Zen garden, stacked Zen stones, single northwest-corner Buddha statue |
| Entry Hall | Human-scaled welcome passage; side tables; coat/jacket hanging place |
| Arts Antechamber | Four-door creative orientation room: Music, Writing, Visual, Great Hall |
| Media Antechamber | Four-door media orientation room: Movie Theater, Audio Theater, Physical Archive Index, Great Hall |

## Codex Principle

The Citadel is experienced, not observed.

Every rendering should place the visitor inside the world rather than outside it.

---

# 5. Map Rendering Standards

## Purpose

Map renderings are special Codex reference images.

They are not standard visitor-perspective room renderings.

A map rendering may use an overhead, diagrammatic, or architectural-plan viewpoint in order to show room relationships, compass orientation, and known pathways.

Map renderings are allowed exceptions to the Visitor Perspective Principle, Central Viewing Principle, Forward Hemisphere Rule, and No Omniscient Perspective Rule.

## Map Aspect Ratio Rule

Codex map renderings should use a 1:1 square aspect ratio unless a different ratio is explicitly requested.

This map aspect ratio is separate from standard room renderings.

Standard room and station renderings default to 16:9 landscape.

Map renderings default to 1:1 square.

This format should be used for known-room maps, full Citadel layout maps, architectural relationship diagrams, Codex reference maps, and compass-oriented room maps.

## Map Perspective Rule

Maps should be rendered from an overhead or near-overhead perspective.

The map should feel like a crafted Citadel document, parchment plan, illuminated floorplan, or architect's record.

Preferred styles include parchment map, hand-drawn architectural plan, illuminated manuscript diagram, medieval floorplan, explorer's chart, or Codex reference plate.

## Map Orientation Rule

All Codex maps should be north-oriented unless explicitly requested otherwise.

North should appear at the top of the image.

A compass rose should be included when practical.

Compass labels should match the Codex layout.

## Fixed Compass Architecture Rule for Maps

Rooms, doors, and connections must remain fixed to their canonical compass positions.

The map should not rearrange rooms for convenience.

If a door is defined on a specific wall, it should appear on that wall in the map.

If a room connects in a specific compass direction, that relationship should be preserved.

The map may simplify distances and shapes, but it should not reverse, rotate, or relocate canonical room relationships.

## Known-Room Map Rule

A map of known rooms should include only rooms, antechambers, stations, and major destinations currently defined in the Codex.

Undefined future areas may be shown only as labeled unknowns, dashed outlines, sealed doors, shadowed passages, or beyond-this-point markers.

A known-room map should not invent fully detailed rooms that are not yet canonical.

## Great Hall Map Rule

The Great Hall should appear as the central compass hub of the Citadel's known realm structure.

Its eight primary openings remain fixed:

- North: Science Door → Hall of Discovery
- Northeast: Philosophy Door → Philosophy Antechamber
- East: Arts Door → Arts Antechamber
- Southeast: Personal Door → Personal Antechamber
- South: Foundational Door → Small Library
- Southwest: Inventor's Door → Inventor's Antechamber
- West: Media Door → Media Antechamber
- Northwest: History Door → History Antechamber

The Great Knowledge Compass and Palace Sigil may appear at the center of the Great Hall.

## Foundation Map Rule

The Foundation path should appear south of the Great Hall.

Canonical Foundation sequence:

Entry Hall → Small Library → Foundational Door → Great Hall

The Garden is a branch off the Entry Hall:

Entry Hall West Door → Garden East Door → Garden

The Garden should appear west of the Entry Hall.

The Small Library should appear north of the Entry Hall and south of the Foundational Door / Great Hall connection.

## Antechamber Map Rule

Antechambers should appear as transitional rooms between the Great Hall and deeper realm paths.

They should not be drawn as full realms unless the room itself has been canonically expanded.

When an antechamber has defined internal doors, those doors should be shown in their canonical compass positions.

## Arts Antechamber Map Rule

The Arts Antechamber is east of the Great Hall.

Its doors are fixed:

- North wall: Music Door
- East wall: Writing Door
- South wall: Visual Door
- West wall: Great Hall Door

The Great Hall Door connects back west toward the Great Hall.

The Music, Writing, and Visual paths may be shown as labeled onward destinations, but they should not be expanded into full rooms unless later defined.

## Media Antechamber Map Rule

The Media Antechamber is west of the Great Hall.

Its doors are fixed:

- North wall: Movie Theater Door
- East wall: Great Hall Door
- South wall: Physical Archive Index Door
- West wall: Audio Theater Door

The Great Hall Door connects back east toward the Great Hall.

Movie Theater, Audio Theater, and Physical Archive Index may be shown as labeled onward destinations.

## Hall of Discovery Map Rule

The Hall of Discovery is north of the Great Hall through the Science Door.

Its doors are fixed:

- North: Astronomy Door
- East: Logic Door
- South: Science Door / Great Hall return
- West: Biology Door

Astronomy, Logic, and Biology may be shown as labeled onward destinations unless their full rooms are later defined.

## Map Labeling Rule

Map labels should be readable and simple.

Use canonical room names.

Avoid over-labeling or adding invented room names.

Preferred labels include Great Hall, Entry Hall, Small Library, Garden, Hall of Discovery, Arts Antechamber, Media Antechamber, History Antechamber, Philosophy Antechamber, Personal Antechamber, Inventor's Antechamber, Music, Writing, Visual, Movie Theater, Audio Theater, Physical Archive Index, Astronomy, Biology, and Logic.

## Map Visual Language Rule

Maps should feel like they belong inside The Great Citadel.

They may include parchment texture, inked outlines, hand-drawn room shapes, aged labels, compass rose, brass or gold ink accents, worn edges, symbolic room icons, subtle color coding by realm, decorative border, and small Codex notes or legend.

Maps should avoid modern UI styling, glowing digital lines, subway-map abstraction unless explicitly requested, sterile CAD-blueprint style unless explicitly requested, invented non-canonical rooms, incorrect door placement, and flipped compass orientation.

## Map Scale Rule

Maps do not need to be perfectly to scale.

They should prioritize canonical relationships, compass directions, door placement, and readability.

Room size may be adjusted for clarity, but relative importance should be respected.

The Great Hall should remain visually central and prominent.

Foundation rooms should feel smaller and more linear.

Antechambers should feel transitional.

## Approved Map Visual Reference

The approved local visual reference for map renderings is The Great Citadel — Known Rooms Map.

Approved traits:

- parchment / illuminated manuscript style
- north-oriented
- compass rose included
- Great Hall central
- known rooms only
- Garden west of Entry Hall
- Media Antechamber west of Great Hall
- Arts Antechamber east of Great Hall
- Hall of Discovery north of Great Hall
- Foundation path south of Great Hall
- readable room labels
- decorative Codex border
- 1:1 square map composition

## Map Non-Canonical Mistakes to Avoid

- placing north anywhere except the top unless explicitly requested
- moving the Garden away from the Entry Hall west side
- placing the Garden door anywhere except the Garden east wall
- placing Arts Antechamber doors on incorrect walls
- placing Media Antechamber doors on incorrect walls
- showing all Great Hall realm doors in incorrect compass positions
- inventing full rooms that are only labeled onward paths
- omitting the Great Hall as the central hub
- making the map look like a modern digital interface
- reversing east and west
- showing disconnected rooms that should be connected

---

# 6. Global Station Standards

## Station Concept

A station is a fixed viewpoint inside a room.

A station is used when a rendering should focus on a particular object, feature, or area of a room rather than presenting the room as a general whole.

A station defines the viewer's fixed position, viewing direction, focal object, intended framing, and purpose of the view.

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

- the viewpoint should remain physically plausible
- the focal object should be clearly emphasized
- the framing should support the purpose of the station
- the surrounding room may appear, but only as supporting context
- the focal object may occupy most of the image if that is the purpose of the station

## Station Naming Convention

Stations should be named by room and purpose.

Suggested format: [Room Name] — [Station Name]

---

# 7. General Antechamber Standards

## Purpose of Antechambers

Antechambers are transitional rooms between the Great Hall and deeper realm paths.

They are not the full realm.

They introduce the identity, atmosphere, symbols, and major paths of the realm beyond.

An antechamber should function as an orientation space, giving the visitor a first sense of the realm before they enter its deeper halls.

## Antechamber Observer Position Rule

In a standard antechamber rendering, the viewer stands at or near the geometric center of the antechamber.

The viewer should feel physically present inside the room.

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

## Antechamber Open Door Display Rule

If a visible antechamber door is open, the connected room, realm path, or connected space beyond the threshold should be visible.

The view beyond the open doorway should include recognizable features of the connected destination.

The visible destination should preserve directional continuity with the current viewer position and facing direction.

The open doorway should not reveal an unrelated scene, blank void, impossible angle, or destination viewed from the wrong perspective.

## Antechamber Directional Continuity Rule

When a connected room or path is visible through an open antechamber doorway, it should be rendered from the same directional line of sight as the current image.

The view beyond the doorway should feel like a natural continuation of the visitor's current gaze.

## Antechamber Scale Rule

Antechambers should be smaller and more focused than the Great Hall.

They may be richer or more specialized than the Foundation rooms, but they should remain human-scaled enough to feel like threshold spaces.

They should not feel like full realms, large public museums, huge theaters, or complete destination spaces.

## Antechamber Identity Rule

Each antechamber should clearly communicate the identity of its realm.

This identity may be shown through door symbols, banners, materials, lighting, objects, alcoves, tools, inscriptions, furniture, and visible connected-room cues.

The antechamber should suggest what lies beyond without fully revealing the deeper realm.

---

# 8. Global Map and Connection Rules

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

# 9. Room Index

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

Absorbed into Entry Hall.

---

# 10. Room Section Template

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

# 11. Entry Hall

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

All eight compass-facing renderings are valid if requested.

The room remains fixed; the viewer rotates.

## Required Features

The Entry Hall should include small tables on each side, a place to hang a coat or jacket, a clear forward path, warm lantern light, wood-softened stone architecture, plants/vines/moss where appropriate, practical arrival details, and welcoming signs or inscriptions when appropriate.

## Material and Atmosphere

The Entry Hall should feel narrow, warm, cozy, human-scaled, ancient, lived-in, cared for, welcoming, safe, practical, and inviting.

It should feel like the first human-scaled threshold of The Great Citadel.

## Standard Rendering Rules

Render the Entry Hall as a narrow welcoming passage.

Do not render it as a broad ceremonial chamber.

It should feel longer than wide.

It should show a clear path inward toward the Small Library.

The room should include practical arrival details such as side tables, coat hooks, bags, lanterns, or small welcoming signs.

If the north door is open, the Small Library should be visible beyond it.

## Open Door Display Rules

If the north door is open, the Small Library should be visibly shown beyond the threshold from the same northward-facing direction as the Entry Hall rendering.

If the south door is open, the exterior arrival side of the Citadel should be shown beyond the threshold.

If the west door is open, the Garden should be visibly shown beyond the threshold with recognizable Garden features such as open sky, raked sand, Zen stones, modest plants, and meditation atmosphere.

## Stations

No formal Entry Hall stations are defined yet.

## Non-Canonical Mistakes to Avoid

- rendering the Entry Hall as a broad ceremonial chamber
- making it feel grand, vast, or open like the Great Hall
- omitting small human-scaled welcome qualities
- omitting practical arrival features
- adding more than three doors
- placing the Garden door anywhere except the west side of the Entry Hall
- making the Entry Hall feel like a hub
- showing an open north door without the Small Library visible beyond it
- showing the Small Library beyond the north door from the wrong perspective

---

# 12. Garden

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

## Garden Wall Rule

The Garden includes old stone boundary walls, with the east wall containing the Garden's only canonical door back to the Entry Hall.

The walls should feel aged, vine-covered, and integrated into the Citadel.

They should not make the Garden feel closed-in, gloomy, or like a building interior.

## Distant View Rule

Beyond the Garden wall, there should be a distant view of mountains.

The mountains should appear far beyond the Garden boundary and should help give the Garden a sense of openness and a larger world beyond the Citadel.

A few scattered steampunk blimps may also be visible in the distant sky beyond the Garden wall.

These blimps should feel small, far away, and atmospheric rather than dominant.

They should read as part of the broader world beyond the Garden, not as the primary subject of the scene.

## Viewing Directions

The standard Garden rendering faces west on the map.

All eight compass-facing renderings are valid if requested.

The viewer stands inside the Garden and faces the requested compass direction.

The Garden remains fixed; the viewer rotates.

The Garden's east-wall door remains on the east wall.

The Buddha statue remains in the northwest corner.

## Required Features

The Garden should include:

- open sky
- warm daylight
- old stone garden boundary walls
- distant mountains beyond the Garden wall
- a few scattered distant steampunk blimps in the sky beyond the Garden wall
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

The Garden should feel open, airy, happy, dry, bright, calm, meditative, restorative, human-scaled, cared for, lightly cultivated, and spiritually quiet.

The Garden should strongly read as a meditation garden.

It should not feel like a park, a farm, a wet courtyard, or a public plaza.

## Buddha Statue Rule

There is only one Buddha statue in the Garden.

The Buddha statue is located in the northwest corner of the Garden.

It should support the meditation-garden identity of the space.

The statue should feel peaceful, modest, and integrated into the Garden.

It should not be monumental or oversized.

No additional Buddha statues are canonical.

## West-Facing Buddha Placement Rule

In a west-facing rendering of the Garden, the Buddha statue should appear on the right side of the image when visible.

This is because the Buddha statue is canonically located in the northwest corner of the Garden.

When the viewer stands inside the Garden and faces west:

- north appears to the right
- south appears to the left
- west is forward
- east is behind the viewer

Therefore, the northwest-corner Buddha statue should appear toward the forward-right portion of the composition.

It should not appear on the left side of a west-facing Garden rendering.

## East-Facing Garden Buddha Visibility Rule

In an east-facing rendering of the Garden, the Buddha statue should not be visible.

The Buddha statue is located in the northwest corner of the Garden.

When the viewer stands inside the Garden and faces east:

- east is forward
- west is behind the viewer
- north is to the viewer's left
- south is to the viewer's right

Therefore, the northwest corner is behind the viewer and to the left.

Because standard renderings follow the Forward Hemisphere Rule, the northwest-corner Buddha statue should not appear in an east-facing Garden rendering.

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

The east-wall door connection to the Entry Hall may exist canonically, but it should not require visible buildings in the standard view.

## Dryness Rule

The Garden should not look wet.

It should not appear rainy, muddy, slick, waterlogged, swampy, or freshly soaked.

Moisture may exist only locally around an optional water feature, but the Garden as a whole should read as dry, comfortable, and pleasant to inhabit.

## Standard Rendering Rules

The standard Garden rendering faces west on the map.

The Garden should appear dry, bright, open, and welcoming.

It should strongly read as a meditation garden.

The raked sand Zen garden should be visible.

Stacked Zen stones should be visible.

The single small Buddha statue should be visible only if composition and direction allow, and it must be in the northwest corner.

No buildings should be visible.

No pathways should lead directly to distant mountains.

When rendered facing east, the composition should focus on the east wall, the Garden East Door, the Entry Hall connection if the east door is open, raked sand, Zen stones, plants, and stone details in the eastern forward hemisphere. The Buddha statue should not be visible.

## Open Door Display Rules

If the Garden's east-wall door is visible and open, the Entry Hall should be visibly shown beyond the threshold.

The Entry Hall should appear from the direction created by the Garden viewer position and the east-wall doorway.

The view through the east door should preserve directional continuity and should not show the Entry Hall from an unrelated angle.

## Approved Visual References

### Garden — Facing East

Approved as Codex-aligned reference.

Key approved traits:

- viewer faces east toward the Garden East Door
- Buddha statue is not visible
- east wall and Garden East Door are primary
- Entry Hall is visible through the open east door
- raked sand Zen garden remains visible
- stacked Zen stones remain visible
- dry, bright, calm meditation atmosphere
- old stone walls with vines and moss
- no exterior buildings visible as dominant elements

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

It emphasizes the meditative identity of the Garden, the quiet spiritual focus of the northwest corner, and the calm contemplative role of the Buddha statue.

#### Framing Rule

From this station, the Buddha statue should be the dominant object in the image.

The viewpoint should be direct and eye-level.

The statue should occupy most of the frame.

The background may include small amounts of recognizable Garden context such as raked sand, Zen stones, plants, old stone surfaces, and warm daylight.

However, the Garden itself is secondary to the Buddha statue.

#### Context Rule

There is only one Buddha statue in the Garden.

That statue is located in the northwest corner.

This station should preserve that placement.

The image should not turn into a broad full-Garden overview.

The image should remain a focused station rendering centered on the single Buddha statue.

## Non-Canonical Mistakes to Avoid

- showing visible buildings in a standard Garden rendering
- omitting the meditation identity
- omitting the raked sand Zen garden
- omitting the stacked Zen stones
- omitting the Buddha statue when it should be visible
- adding more than one Buddha statue
- placing the Buddha statue anywhere other than the northwest corner
- making the Buddha statue monumental or oversized
- showing the Buddha statue on the left side of a west-facing Garden rendering
- showing the Buddha statue in an east-facing Garden rendering
- making the Garden feel wet, muddy, slick, swampy, or waterlogged
- making the Garden gloomy or oppressive
- turning it into a large park
- turning it into a farm
- turning it into a public plaza
- adding extra Garden doors
- placing the Garden door on any wall other than the east wall
- making the east-wall door the main focus of the standard west-facing rendering
- making distant blimps too large, too numerous, or dominant over the Garden

---

# 13. Small Library

## Purpose

The Small Library is the final preparatory room before entering the Great Hall.

It represents understanding before exploration.

It is a compact, warm, human-scaled study room.

## Connections

Entry Hall → Small Library → Foundational Door → Great Hall

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

The Small Library has preferred canonical views facing north and south, but all eight compass-facing renderings are valid if requested.

The room remains fixed; the viewer rotates.

## Required Features

The Small Library contains Instruction Manual and Guest Book, the Codex as a reference source, introductory collections, maps, symbol references, historical records, reading tables, lecterns, shelves, reference books, writing tools, map tables, and lamps or lanterns.

## Material and Atmosphere

The Small Library should feel compact, warm, quiet, human-scaled, focused, preparatory, lived-in, welcoming, and studious.

Wood should strongly soften the room.

## Standard Rendering Rules

A standard Small Library rendering should show one primary door, warm compact human scale, no extra exits, no full circulation diagram, Instruction Manual and Guest Book in the northeast corner when visible, and north door unobstructed when facing north.

The large prominent display book in the Small Library is not the Codex. It is the combined Instruction Manual and Guest Book.

## Open Door Display Rules

If the north door is open, the onward connection toward the Foundational Door and Great Hall should be visibly shown beyond the threshold.

If the south door is open, the Entry Hall should be visibly shown beyond the threshold.

All open-door views should preserve spatial continuity and should not show connected spaces from unrelated angles.

## Instruction Manual and Guest Book

The large prominent display book in the Small Library is not the Codex.

It is a combined Instruction Manual and Guest Book.

It serves as the visitor's practical introduction to The Great Citadel and as a record of arrival.

It may include welcoming guidance, orientation notes, how to use the Citadel, suggested starting points, simple rules of conduct, and reflections or signatures from prior visitors.

It should be placed in the northeast corner of the Small Library and must not block the north door.

## The Codex in the Small Library

The Codex remains one of the important contents of the Small Library, but it is not the large display book used to greet visitors.

The Codex may appear as a protected reference volume, shelved master text, smaller lectern book, or curated reference source within the room.

## Stations

### Small Library — Instruction Manual Station

This station is a fixed viewpoint in the Small Library.

It is positioned just in front of the large Instruction Manual and Guest Book in the northeast corner of the room.

The view should look downward toward the book.

The Instruction Manual and Guest Book should be the primary object in the image and should occupy most of the frame.

The surrounding room may appear only as secondary context.

## Non-Canonical Mistakes to Avoid

- showing more than one primary door at once in a standard rendering
- showing open doors unless intentionally using the open-door connection rule
- adding extra exits
- making the Small Library feel like a hub
- placing the Instruction Manual and Guest Book in the center of the room
- blocking the north door with the book
- treating the large display book as the Codex
- rendering the room as grand, vast, or monumental
- rendering the Instruction Manual Station as a full-room overview

---

# 14. Foundational Door

## Purpose

The Foundational Door connects the Small Library to the Great Hall.

It is one of the eight primary openings of the Great Hall.

It leads back to the Foundations rather than to a realm antechamber.

## Connections

Small Library → Foundational Door → Great Hall

Great Hall → Foundational Door → Small Library → Entry Hall

## Door Rules

The Foundational Door is the exception to the Antechamber Connection Principle.

It does not lead to an antechamber.

It leads between the Great Hall and the Foundations.

## Viewing Directions

No special standalone viewing directions are currently defined for the Foundational Door.

It may be rendered from the Small Library side or Great Hall side.

## Required Features

The Foundational Door should communicate threshold, return, and foundation.

It may include old stone, carved wood, brass or bronze fittings, foundational symbols, threshold markings, Palace Sigil or root/return motifs where appropriate.

## Open Door Display Rules

If the Foundational Door is viewed open from the Small Library side, the Great Hall should be visibly shown beyond the threshold.

If the Foundational Door is viewed open from the Great Hall side, the Small Library should be visibly shown beyond the threshold.

## Non-Canonical Mistakes to Avoid

- treating the Foundational Door as a realm door
- showing it leading to an antechamber
- disconnecting it from the Small Library
- showing an open Foundational Door without recognizable connected space beyond it

---

# 15. Great Hall

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

The Great Hall has eight canonical viewing directions:

- North
- Northeast
- East
- Southeast
- South
- Southwest
- West
- Northwest

## Required Features

The Great Hall should include Palace Sigil, Great Knowledge Compass, eight primary openings, domain medallions, door tracks, ancient stonework, brass mechanisms, and banners where appropriate.

## Standard Rendering Rules

The Great Hall is not a map. It is an architectural experience.

The viewer stands at or near the geometric center of the Great Hall.

The viewer stands upon the Great Knowledge Compass.

Only the forward half of the chamber should be visible.

Visible doors: minimum 1, preferred 2–3, maximum 4.

A rendering that reveals all eight doors is non-canonical.

## Open Door Display Rules

Any visible room or antechamber shown beyond an open Great Hall door should preserve the viewer's current facing direction.

The destination should appear as a continuation through that specific door, not as an independent view of the destination room from another angle.

If the Science Door is open, the Hall of Discovery should be shown beyond the threshold.

If the Philosophy Door is open, the Philosophy Antechamber should be shown beyond the threshold.

If the Arts Door is open, the Arts Antechamber should be shown beyond the threshold.

If the Personal Door is open, the Personal Antechamber should be shown beyond the threshold.

If the Foundational Door is open, the Small Library should be shown beyond the threshold.

If the Inventor's Door is open, the Inventor's Antechamber should be shown beyond the threshold.

If the Media Door is open, the Media Antechamber should be shown beyond the threshold.

If the History Door is open, the History Antechamber should be shown beyond the threshold.

## Banner Rules

Banners serve as architectural identity markers, not modern signs.

They should be aged, symbolic, physically attached to the architecture, and should use symbols more than text.

## Stations

No formal Great Hall stations are defined yet.

## Non-Canonical Mistakes to Avoid

- rendering the Great Hall as a complete map
- showing all eight doors at once
- using a bird's-eye view for standard room renderings
- showing the entire Great Knowledge Compass from normal standing perspective
- using floating labels instead of integrated signs, inscriptions, or banners
- showing an open door without the connected room or antechamber visible beyond it

---

# 16. Hall of Discovery

## Purpose

The Hall of Discovery is the antechamber of the Science Realm.

It introduces visitors to Astronomy, Biology, and Logic.

It represents inquiry before specialization.

## Connections

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

All eight compass-facing renderings are valid if requested.

The room remains fixed; the viewer rotates.

## Required Features

The Hall of Discovery should include Map of Understanding, Compass Rose of Discovery, Celestial Vault, and Eight Alcoves of Discovery.

## Standard Rendering Rules

The floor contains the Map of Understanding.

The ceiling forms the Celestial Vault, which may include constellations, planetary paths, lunar cycles, seasonal markers, astronomical symbols, and scientific inscriptions.

All elements should appear handcrafted and integrated into the architecture.

## Open Door Display Rules

If the Science Door is open, the Great Hall should be visibly shown beyond the threshold.

If the Astronomy Door is open, the Astronomy Realm beyond should be visibly suggested through astronomy-related cues.

If the Biology Door is open, the Biology Realm beyond should be visibly suggested through biology-related cues.

If the Logic Door is open, the Logic Realm beyond should be visibly suggested through logic-related cues.

## Non-Canonical Mistakes to Avoid

- including the Star Whale
- turning alcoves into freestanding displays, kiosks, islands, detached structures, or center-room furniture
- omitting the Map of Understanding
- omitting the Celestial Vault when it should be visible
- showing open doors without recognizable connected spaces beyond them

---

# 17. Science Realm Doors and Alcoves

## Astronomy Door

Direction: North

Symbol: Astrolabe

Leads toward Astronomy Tower, Celestial Archives, Cosmology Collections, Navigation Observatories, and Star Mapping Halls.

## Biology Door

Direction: West

Symbol: Leaf and Branch

Leads toward Biological Conservatory, Botanical Gardens, Natural History Archives, Living Systems Galleries, and Evolution Collections.

## Logic Door

Direction: East

Symbol: Compass and Straightedge

Leads toward Hall of Mathematics, Geometry Archives, Logic Chambers, Pattern Galleries, Algorithm Workshops, Mechanical Computation Gallery, and Time Traveler Logic Engines.

Modern computation should be represented through brass analytical engines, mechanical calculators, clockwork reasoning machines, and Time Traveler modifications.

The Logic Realm should feel ancient, elegant, and intellectual rather than technological.

## Alcove Rule

Each primary door in the Hall of Discovery owns two alcoves.

Alcoves are architectural recesses built into perimeter walls.

They are not freestanding displays, kiosks, islands, detached structures, or furniture placed within the center of a room.

---

# 18. Arts Antechamber

## Purpose

The Arts Antechamber is the transitional room between the Great Hall and the Arts Realm.

It introduces making, beauty, image, performance, music, craft, color, writing, and expression.

It is not the full Arts Realm.

It is the threshold where the visitor first encounters the creative life of The Great Citadel.

The Arts Antechamber is a four-door creative orientation room.

It receives the visitor from the Great Hall and offers three primary artistic paths: Music, Writing, and Visual.

## Connections

Great Hall → Arts Door → Arts Antechamber

From the Arts Antechamber:

- Arts Antechamber → Music Door → Music path / Music Halls
- Arts Antechamber → Writing Door → Writing path / Literary Arts Halls
- Arts Antechamber → Visual Door → Visual Arts path / Visual Arts Halls
- Arts Antechamber → Great Hall Door → Arts Door → Great Hall

## Door Rules

The Arts Antechamber has four canonical doors:

1. Music Door
2. Writing Door
3. Visual Door
4. Great Hall Door

## Door Placement Rule

The Arts Antechamber has four canonical doors placed by compass direction:

- North wall: Music Door
- East wall: Writing Door
- South wall: Visual Door
- West wall: Great Hall Door

## Viewing Directions

The Arts Antechamber follows the General Antechamber Standards.

All eight compass-facing renderings are valid if requested.

The viewer stands at or near the geometric center.

Only the forward hemisphere should be shown.

The primary visible door should be the door on the wall being faced.

Facing North → Music Door is primary.

Facing East → Writing Door is primary.

Facing South → Visual Door is primary.

Facing West → Great Hall Door is primary.

Diagonal views show the forward portions between adjacent walls.

## Required Features

The Arts Antechamber should include carved wood display panels, framed sketches or studies, small sculptures, pigments or paint bowls, parchment studies, musical instruments as secondary details when not facing the Music Door, masks or theatrical objects, woven textiles or banners, warm lantern light, benches or worktables, and its four canonical doors.

## Standard Rendering Rules

Render the Arts Antechamber as a threshold room, not as a full museum, theater, or workshop.

Do not render all four Arts Antechamber doors in a standard room image unless a map, diagram, or special overview is explicitly requested.

## Open Door Display Rules

If the Great Hall Door is open, the Great Hall should be visibly shown beyond the threshold.

If the Music Door is open, the space beyond should show recognizable music-related cues.

If the Writing Door is open, the space beyond should show recognizable writing or literary cues.

If the Visual Door is open, the space beyond should show recognizable visual-arts cues.

All open-door views should preserve directional continuity with the current viewer position and facing direction.

## Non-Canonical Mistakes to Avoid

- showing fewer or more than four canonical Arts Antechamber doors unless intentionally cropped by viewpoint
- placing any Arts Antechamber door on the wrong compass wall
- showing all four doors in a standard rendering
- making the Arts Antechamber feel like the full Arts Realm
- making it a modern museum, giant theater, messy workshop, royal gallery, or cold marble room
- showing open doors without recognizable connected spaces beyond them
- showing connected spaces from contradictory perspectives

---

# 19. Media Antechamber

## Purpose

The Media Antechamber is the transitional room between the Great Hall and the Media Realm.

It is a four-door orientation room for recorded and shared experience.

It receives the visitor from the Great Hall and offers three primary media paths:

- Movie Theater
- Audio Theater
- Physical Archive Index

It is not the full Media Realm.

It is the threshold where the visitor first encounters image, sound, record, story, and indexed memory.

## Core Identity

The Media Antechamber is a warm, human-scaled chamber of recorded experience.

It introduces three forms of media:

- moving image
- recorded sound
- physical archives

The room should feel like a medieval-Citadel interpretation of a media index, not a modern media center.

Media in The Great Citadel is not digital content, but preserved experience: images, sounds, stories, records, and references held in physical form.

## Connections

Great Hall → Media Door → Media Antechamber

From the Media Antechamber:

- Media Antechamber → Movie Theater Door → Movie Theater
- Media Antechamber → Audio Theater Door → Audio Theater
- Media Antechamber → Physical Archive Index Door → Physical Archive Index
- Media Antechamber → Great Hall Door → Media Door → Great Hall

## Door Rules

The Media Antechamber has four canonical doors:

1. Great Hall Door
2. Movie Theater Door
3. Audio Theater Door
4. Physical Archive Index Door

No additional Media Antechamber doors are canonical unless later defined.

## Door Placement Rule

The Media Antechamber has four canonical doors placed by compass direction:

- North wall: Movie Theater Door
- East wall: Great Hall Door
- South wall: Physical Archive Index Door
- West wall: Audio Theater Door

Compass layout:

```text
                 NORTH

           Movie Theater Door

WEST                                      EAST

Audio Theater Door              Great Hall Door

      Physical Archive Index Door

                 SOUTH
```

## Viewing Directions

The Media Antechamber follows the General Antechamber Standards.

All eight compass-facing renderings are valid if requested.

The viewer stands at or near the geometric center of the room.

Only the forward hemisphere should be shown.

The Media Antechamber should not show all four doors in a standard rendering.

The primary visible door should be the door on the wall being faced.

This means:

- Facing North → Movie Theater Door is primary
- Facing East → Great Hall Door is primary
- Facing South → Physical Archive Index Door is primary
- Facing West → Audio Theater Door is primary

Diagonal views show the forward portions between adjacent walls:

- Northeast → between Movie Theater and Great Hall
- Southeast → between Great Hall and Physical Archive Index
- Southwest → between Physical Archive Index and Audio Theater
- Northwest → between Audio Theater and Movie Theater

## Required Features

The Media Antechamber should include:

- carved wood media panels
- framed story panels
- projection-lantern or camera-obscura-like devices
- acoustic horns or resonance bowls
- catalog drawers
- archive labels
- parchment reference slips
- warm lantern light
- benches or listening seats
- brass mechanisms
- shelves of media records
- symbols for image, sound, and archive

## Material and Atmosphere

The Media Antechamber should feel:

- warm
- human-scaled
- archival
- story-rich
- handcrafted
- memory-bearing
- quietly theatrical
- carefully indexed
- ancient but actively used

## Door Identity Rules

Each door in the Media Antechamber should have a distinct visual identity that communicates the path beyond it.

The doors should feel like part of the same Citadel civilization, but each should use different symbols, materials, and surrounding details.

### North wall — Movie Theater Door

The Movie Theater Door should suggest moving image, projection, shadow, performance, and framed vision.

Visual cues may include carved film-frame-like borders interpreted in medieval materials, projection-lantern symbols, shadow-play motifs, brass lens mechanisms, dark velvet or heavy curtain details, and framed light spilling from beyond the doorway.

### West wall — Audio Theater Door

The Audio Theater Door should suggest listening, resonance, voice, music, sound, and acoustic memory.

Visual cues may include carved sound-wave patterns, acoustic horn shapes, resonance bowls, hanging bells or chimes, warm wood acoustic panels, and symbols of voice, ear, vibration, or instrument strings.

### South wall — Physical Archive Index Door

The Physical Archive Index Door should suggest cataloging, records, reference, shelves, and indexed memory.

Visual cues may include catalog drawer motifs, small label plates, parchment tabs, archive symbols, ledgers or index tables near the threshold, and shelves or boxes visible beyond the doorway.

### East wall — Great Hall Door

The Great Hall Door should clearly read as the return door.

Visual cues may include Great Hall stonework, Palace Sigil or compass motif, warmer golden light from the Great Hall, domain banners, or hints of the Great Knowledge Compass beyond the threshold.

## Standard Rendering Rules

Render the Media Antechamber as a transitional antechamber, not the full Media Realm.

Do not make it look modern.

Do not show all four doors in a standard rendering unless a map, diagram, or special overview is explicitly requested.

When facing north, the Movie Theater Door should be primary.

When facing east, the Great Hall Door should be primary.

When facing south, the Physical Archive Index Door should be primary.

When facing west, the Audio Theater Door should be primary.

## Open Door Display Rules

If the Great Hall Door is open, the Great Hall should be visibly shown beyond the threshold.

If the Movie Theater Door is open, the Movie Theater should be visibly shown beyond the threshold with recognizable movie-theater cues such as rows of seats, projection light, screen glow, framed viewing space, and warm theatrical darkness.

If the Audio Theater Door is open, the Audio Theater should be visibly shown beyond the threshold with recognizable audio-theater cues such as acoustic wood, listening benches, sound-horn or resonance structures, instruments or playback-like Citadel mechanisms, and warm listening-room atmosphere.

If the Physical Archive Index Door is open, the Physical Archive Index should be visibly shown beyond the threshold with recognizable archive-index cues such as catalog drawers, shelves, labeled archive boxes, ledgers, index tables, and parchment reference slips.

All open-door views should preserve directional continuity with the current viewer position and facing direction.

## Stations

No formal Media Antechamber stations are defined yet.

## Non-Canonical Mistakes to Avoid

- making the room look modern
- using televisions
- using modern speakers
- using digital screens
- using cinema posters
- using plastic equipment
- using neon
- using modern computers
- making it feel like a modern media center
- making it feel like a commercial movie theater lobby
- making it feel like the full Media Realm
- placing any Media Antechamber door on the wrong compass wall
- showing all four doors in a standard rendering
- showing open doors without recognizable connected spaces beyond them
- showing connected spaces from contradictory perspectives

---

# 20. Future Antechambers

Major realm doors do not open directly into fully developed realms.

Each primary realm door from the Great Hall opens first into an antechamber.

An antechamber is a transitional room that introduces the identity, atmosphere, symbols, and major paths of its realm.

The Foundational Door is the exception to the Antechamber Connection Principle.

## History Antechamber

The History Antechamber is the transitional room between the Great Hall and the History Realm. It introduces archives, timelines, memory, records, ruins, and preserved events.

Connection: Great Hall → History Door → History Antechamber → History Realm.

The History Antechamber follows the General Antechamber Standards.

No formal History Antechamber stations are defined yet.

## Philosophy Antechamber

The Philosophy Antechamber is the transitional room between the Great Hall and the Philosophy Realm. It introduces questions, contemplation, argument, ethics, metaphysics, and meaning.

Connection: Great Hall → Philosophy Door → Philosophy Antechamber → Philosophy Realm.

The Philosophy Antechamber follows the General Antechamber Standards.

No formal Philosophy Antechamber stations are defined yet.

## Personal Antechamber

The Personal Antechamber is the transitional room between the Great Hall and the Personal Realm. It introduces memory, identity, reflection, inner life, personal history, and self-understanding.

Connection: Great Hall → Personal Door → Personal Antechamber → Personal Realm.

The Personal Antechamber follows the General Antechamber Standards.

No formal Personal Antechamber stations are defined yet.

## Inventor's Antechamber

The Inventor's Antechamber is the transitional room between the Great Hall and the Inventor's Realm. It introduces invention, mechanisms, tools, experiments, prototypes, workshop thinking, and Time Traveler modifications.

Connection: Great Hall → Inventor's Door → Inventor's Antechamber → Inventor's Realm.

The Inventor's Antechamber follows the General Antechamber Standards.

No formal Inventor's Antechamber stations are defined yet.

---

# 21. Symbols and Floor Systems

## Palace Sigil

The Palace Sigil is the highest symbol of The Great Citadel.

It takes the form of a simple eight-spoked ship's helm inspired by traditional Buddhist wheel symbolism.

Characteristics:

- Circular form
- Eight spokes
- Strong silhouette
- Balanced geometry
- Immediate recognizability

The design should feel ancient, timeless, functional, calm, and purposeful.

The Palace Sigil represents guidance rather than destination.

The Citadel does not dictate what visitors should learn. It provides pathways through knowledge.

## Great Knowledge Compass

The Great Knowledge Compass is the floor of the Great Hall and one of the oldest known artifacts in the Citadel.

At its center is the Palace Sigil.

Its spokes extend outward through Palace Sigil, Domain Medallion, Door Track, and Primary Opening.

## Compass Rose of Discovery

The Compass Rose of Discovery sits at the center of the Map of Understanding in the Hall of Discovery.

It aligns:

- North → Astronomy Door
- East → Logic Door
- South → Science Door
- West → Biology Door

The Compass Rose is fixed within the architecture. It does not rotate based on the viewer.

---

# 22. Current Canonical Status

Canonical world name:

- The Great Citadel

Active Codex:

- Codex v1.6 — Garden, Map, and Media Antechamber Edition

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
- The former statement that The Great Citadel naming change was rolled back is superseded by v1.2 and later.
- The canonical project/world name is The Great Citadel.
- The large prominent display book in the Small Library is not the Codex; it is the Instruction Manual and Guest Book.
- A standard Small Library rendering with an open door is non-canonical unless a later rule explicitly allows an exception.
- A Great Hall rendering that shows all eight primary openings at once is non-canonical.
- A Garden standard rendering with visible buildings is non-canonical.
- A Garden standard rendering that omits the raked sand Zen garden, stacked Zen stones, or single northwest-corner Buddha statue when it should be visible is non-canonical.
- A west-facing Garden rendering with the Buddha statue on the left side is non-canonical.
- An east-facing Garden rendering showing the Buddha statue is non-canonical.
- An Arts Antechamber standard rendering that shows all four doors at once is non-canonical unless explicitly requested as a map, diagram, or special overview.
- A Media Antechamber standard rendering that shows all four doors at once is non-canonical unless explicitly requested as a map, diagram, or special overview.
- An open doorway that shows the connected room from a contradictory or unrelated perspective is non-canonical.
- A Codex map using modern digital UI styling is non-canonical unless explicitly requested as a special alternate style.

---

# 23. Changelog

## v1.6 — Garden, Map, and Media Antechamber Edition

Created a new full-copy standalone Codex version.

Preserved v1.5 and consolidated the latest local working updates.

Added Eight-Direction Room Viewing Rule:

- every room can be rendered from all eight compass directions unless an exception applies
- preferred/default views still exist
- stations still override normal center-view rules
- doors and features remain fixed to compass positions
- the viewer rotates; the room does not

Expanded the Central Viewing Principle and Forward Hemisphere Rule to support eight-direction room rendering.

Added Fixed Compass Architecture Rule.

Added a dedicated Map Rendering Standards section.

Added Map Aspect Ratio Rule:

- map renderings default to 1:1 square
- standard room and station renderings default to 16:9 landscape

Added approved map visual reference for The Great Citadel — Known Rooms Map.

Updated Garden:

- Garden includes old stone boundary walls
- Garden has distant mountains beyond the wall
- Garden may show a few scattered distant steampunk blimps beyond the wall
- Buddha statue remains the only Buddha statue and remains in the northwest corner
- west-facing Garden renderings should show the Buddha on the right side when visible
- east-facing Garden renderings should not show the Buddha statue
- approved Garden — Facing East visual reference added

Updated Media Antechamber:

- defined as a four-door media orientation room
- North wall: Movie Theater Door
- East wall: Great Hall Door
- South wall: Physical Archive Index Door
- West wall: Audio Theater Door
- added Media Antechamber core identity
- added Media Antechamber required features
- added Media Antechamber door identity rules
- added Media Antechamber open-door display rules

## v1.5 — Rendering Continuity and Arts Antechamber Edition

Created a full-copy standalone Codex version.

Added global 16:9 image-format rule, doorway display rules, doorway identification rules, directional-continuity rules, connected-room perspective rules, general antechamber standards, Entry Hall three-door layout, Garden Buddha statue placement and station, and detailed Arts Antechamber compass layout.

## v1.4 — Garden Meditation Edition

Created a full-copy standalone Codex version.

Replaced the previous patched Garden theme with a refined meditation-garden identity.

Defined the Garden as a dry, bright, open-air Zen meditation garden connected to the Entry Hall side door.

## v1.3 — Station Rendering Edition

Created a full-copy standalone Codex version.

Refactored the Codex structure for image rendering and added station-based rendering standards.

Added Small Library — Instruction Manual Station.

## v1.2 — Great Citadel Foundations Edition

Created a full-copy standalone Codex version.

Changed canonical world name to The Great Citadel.

Retired Front Entry and Hallway as separate rooms.

Unified them into Entry Hall.

Added save protocol, revised Foundations, added antechamber principle, revised room look-and-feel, Great Hall standards, and detailed Small Library rules.

## v1.1 — Entry Hall Edition

Created a full-copy standalone Codex version.

Added Entry Hall as a formal foundational room between the Front Entry and Hallway.

## v1.0 — Discovery Edition

Initial full-copy canonical Codex version.

Included the Foundations, Great Hall, Palace Sigil, Science Realm, Hall of Discovery, Map of Understanding, Compass Rose of Discovery, Celestial Vault, Eight Alcoves of Discovery, and universal rendering standards.
