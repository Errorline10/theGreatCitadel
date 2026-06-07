# Codex v2.8 — Map Core

Project: The Great Citadel
Version: v2.8
Role: Coordinate system, bearing rules, topology, map rendering, topology separation, and map compliance.
Supersedes: /chatGPT/mapVault/Codex_v2.7_Map_Core.md

---

# Global Citadel Coordinate System

The Great Citadel uses a fixed canonical compass orientation.

North = Top
East = Right
South = Bottom
West = Left

This orientation never rotates. The viewer may rotate. The Citadel does not.

All maps, room diagrams, navigation charts, architectural layouts, room connections, and rendering audits derive from this coordinate system.

---

# Primary Spine Layout

The foundational path is a north-south spine:

North

Hall of Discovery
|
Great Hall
|
Foundational Door
|
Small Library
|
Entry Hall
|
Outside

South

Entry Hall is the southernmost known interior room. Small Library is north of Entry Hall. Foundational Door is north of Small Library. Great Hall is north of Foundational Door. Hall of Discovery is north of Great Hall.

Garden is west of Entry Hall.

Garden is physically attached directly to the west side of Entry Hall. The Garden East Door and Entry Hall West Door are the same immediate doorway connection.

---

# Direct Adjacency Mapping Rule

On all canonical maps:

Garden must be drawn directly adjacent to the west side of the Entry Hall.

A visible gap between Garden and Entry Hall is non-canonical.

A connecting corridor between Garden and Entry Hall is non-canonical.

A connecting bridge between Garden and Entry Hall is non-canonical.

The two spaces share an immediate doorway connection across a common boundary.

---

# Topology Separation Rule

Canonical adjacency and canonical non-adjacency are both mandatory topology constraints.

When two rooms are not canonically connected, map prompts must explicitly state that no doorway, corridor, shared wall, bridge, tunnel, path, label-line connection, visual connector, or architectural connection may exist between them.

Known critical separations:

- Garden and Media Antechamber must not connect.
- Garden and Great Hall must not connect.
- Garden and all antechambers must not connect.

For maps, the Garden and Media Antechamber must remain visibly separated by empty map space unless a future Codex release explicitly defines a canonical connection.

The Garden must not share a wall, doorway, path, boundary, label-line connection, visual connector, or architectural connector with the Media Antechamber.

The Garden must not share a wall, doorway, path, boundary, label-line connection, visual connector, or architectural connector with the Great Hall.

Any visual suggestion of Garden-to-Media or Garden-to-Great-Hall adjacency is non-canonical.

---

# Great Hall Radial Geometry Rule

The Great Hall is the center of an eight-spoke compass system.

The eight primary openings are evenly spaced at exactly 45-degree intervals:

0 degrees = Science Door
45 degrees = Philosophy Door
90 degrees = Arts Door
135 degrees = Personal Door
180 degrees = Foundational Door
225 degrees = Inventor's Door
270 degrees = Media Door
315 degrees = History Door

No opening may be repositioned for artistic convenience.

All maps, diagrams, room connections, doorway views, navigation systems, and room placement logic derive from this compass geometry.

---

# Great Hall Compass Layout

N: Science Door -> Hall of Discovery
NE: Philosophy Door -> Philosophy Antechamber
E: Arts Door -> Arts Antechamber
SE: Personal Door -> Personal Antechamber
S: Foundational Door -> Small Library -> Entry Hall
SW: Inventor's Door -> Inventor's Antechamber
W: Media Door -> Media Antechamber
NW: History Door -> History Antechamber

The Great Hall is the central hub. The eight openings are evenly spaced around the center at 45-degree intervals.

---

# Canonical Map Render Block

Render a canonical architectural map of The Great Citadel.

North must be at the top. South must be at the bottom. East must be on the right. West must be on the left.

The map represents physical room topology, not artistic composition.

Physical room topology takes precedence over artistic composition, spacing, symmetry, readability, decoration, and visual balance.

Rooms that are directly attached in the Codex must remain directly attached in the map.

Rooms that are not connected in the Codex must remain visibly unconnected in the map.

The renderer may not introduce spacing or connector structures for visual convenience.

The renderer may not introduce adjacency, wall contact, doorway contact, path contact, or label-line contact between rooms that are not canonically connected.

Canonical room connections take precedence over visual symmetry.

Rooms may only connect where a canonical doorway or passage exists.

Do not create shortcut connections.

Do not connect rooms that merely share a compass bearing.

Preserve all known room relationships exactly.

Unknown areas may be omitted or shown as unexplored.

Use parchment-map styling unless otherwise requested.

Use a 1:1 square format.

Display room names, compass orientation, and major paths.

## Garden Attachment Rendering Requirement

The Garden is physically attached directly to the west side of the Entry Hall.

The Garden East Door and Entry Hall West Door form a single direct doorway connection.

When rendering a map:

- Draw the Garden immediately adjacent to the west wall of the Entry Hall.
- The Garden boundary should touch or directly adjoin the Entry Hall structure.
- The direct doorway relationship must be visually obvious.
- Draw the Media Antechamber west of the Great Hall, not adjacent to the Garden.
- Keep the Garden and Media Antechamber separated by empty map space.

Do not depict:

- connecting corridors
- connecting hallways
- connecting tunnels
- connecting bridges
- connector rooms
- vestibules
- transition spaces
- detached Garden placement
- visible gaps between Garden and Entry Hall
- any wall, doorway, path, boundary, shared edge, label line, or visual connector between Garden and Media Antechamber
- any wall, doorway, path, boundary, shared edge, label line, or visual connector between Garden and Great Hall

A map showing the Garden separated from the Entry Hall by any intermediate structure is non-canonical.

A map showing the Garden connected or visually adjacent to Media Antechamber or Great Hall is non-canonical.

---

# Great Citadel Master Map Prompt

Generate a canonical map of the known Great Citadel.

North at top.

Primary spine:

Outside -> Entry Hall -> Small Library -> Foundational Door -> Great Hall -> Hall of Discovery

Garden is west of Entry Hall and directly attached to the Entry Hall west wall.

The Garden must not be drawn as a detached room.

The Garden must not be connected by a corridor, bridge, tunnel, path room, connector chamber, or transitional structure.

The Garden connects only to Entry Hall.

Media Antechamber is west of Great Hall, not adjacent to Garden.

Garden and Media Antechamber must be separated by empty map space.

No wall, doorway, path, shared boundary, label-line connection, visual connector, or architectural connection may exist between Garden and Media Antechamber.

No wall, doorway, path, shared boundary, label-line connection, visual connector, or architectural connection may exist between Garden and Great Hall.

Great Hall is the central compass hub.

Great Hall connections:

N Science Door / Hall of Discovery
NE Philosophy Antechamber
E Arts Antechamber
SE Personal Antechamber
S Foundational Door
SW Inventor's Antechamber
W Media Antechamber
NW History Antechamber

The eight Great Hall openings are spaced at exact 45-degree intervals.

Only canonical room connections may exist.

Do not connect Garden to Media Antechamber.

Do not connect Garden directly to Great Hall.

Display room labels.

Display compass bearings.

Display architectural topology rather than decorative symmetry.

---

# Map Compliance Checklist

A canonical map is compliant only if:

- North is at the top.
- South is at the bottom.
- East is on the right.
- West is on the left.
- The primary spine is preserved.
- Garden is connected only to the Entry Hall.
- Garden is directly attached to the west side of the Entry Hall.
- No corridor exists between Garden and Entry Hall.
- No gap exists between Garden and Entry Hall.
- The shared doorway relationship between Garden and Entry Hall is visually obvious.
- Great Hall remains the central hub.
- Great Hall openings are positioned at exact 45-degree intervals.
- No non-canonical room connections exist.
- All displayed room connections correspond to canonical doors or passages.
- Room placement follows the Canonical Bearing Rules.
- Topology is prioritized over visual symmetry.
- Garden and Media Antechamber are visibly separated.
- Garden and Great Hall are visibly separated.
- No wall, doorway, path, shared boundary, label-line connection, visual connector, or architectural connection exists between Garden and Media Antechamber.
- No wall, doorway, path, shared boundary, label-line connection, visual connector, or architectural connection exists between Garden and Great Hall.

---

# Render-Derived Mapping Rule

Every room definition should be simple enough that a map can be generated directly from compass orientation, door locations, connected rooms, canonical topology, and explicit topology separation rules without requiring interpretation.

If a room definition cannot be converted into a map, the room definition is incomplete.

---

# Topology Preservation Rule Expanded

Maps, room renders, doorway views, connected-room views, and navigation diagrams must all describe the same underlying architecture.

A room render may show only part of a room. A map may show all of a room. Neither may contradict the other.

Direct physical attachment relationships must remain direct in maps and renders. They may not be abstracted into corridors, bridges, paths, transition rooms, or separated structures.

Non-adjacent rooms must remain non-adjacent in maps and renders. Their separation may not be weakened into wall contact, doorway contact, path contact, shared-boundary contact, label-line contact, or visual connector contact.

---

# Canonical Bearing Requirement

Whenever a new room, antechamber, realm, station, path, map, or connection is added to the Codex, its canonical compass bearing and relationship to existing spaces should be explicitly defined.

Rooms should be added in a manner that allows deterministic map generation.

End of Codex v2.8 — Map Core.
