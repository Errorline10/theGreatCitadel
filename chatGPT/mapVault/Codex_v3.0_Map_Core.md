# Codex v3.0 — Map Core

Project: The Great Citadel
Version: v3.0
Role: Coordinate system, bearing rules, topology, map rendering, topology separation, exterior alignment, and map compliance.
Supersedes: /chatGPT/mapVault/Codex_v2.9_Map_Core.md

---

# Global Citadel Coordinate System

The Great Citadel uses a fixed canonical compass orientation.

North = Top
East = Right
South = Bottom
West = Left

This orientation never rotates. The viewer may rotate. The Citadel does not.

All maps, room diagrams, navigation charts, architectural layouts, room connections, exterior views, exterior blueprints, rendering audits, room blueprints, 360 references, and door renders derive from this coordinate system.

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

Garden is west of Entry Hall and directly attached to the west side of Entry Hall.

---

# Direct Adjacency Mapping Rule

On all canonical maps and blueprints, Garden must be drawn directly adjacent to the west side of the Entry Hall.

A visible gap, connecting corridor, or bridge between Garden and Entry Hall is non-canonical.

The two spaces share an immediate doorway connection across a common boundary.

---

# Topology Separation Rule

Canonical adjacency and canonical non-adjacency are both mandatory topology constraints.

When two rooms are not canonically connected, prompts must explicitly state that no doorway, corridor, shared wall, bridge, tunnel, path, label-line connection, visual connector, or architectural connection may exist between them.

Known critical separations:

- Garden and Media Antechamber must not connect.
- Garden and Great Hall must not connect.
- Garden and all antechambers must not connect.

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

---

# Canonical Map Render Block

Render a canonical architectural map of The Great Citadel.

North must be at the top. South must be at the bottom. East must be on the right. West must be on the left.

The map represents physical room topology, not artistic composition.

Physical room topology takes precedence over artistic composition, spacing, symmetry, readability, decoration, and visual balance.

Rooms that are directly attached in the Codex must remain directly attached in the map.

Rooms that are not connected in the Codex must remain visibly unconnected in the map.

Use parchment-map styling unless otherwise requested.

Use a 1:1 square format.

Display room names, compass orientation, and major paths.

---

# Great Citadel Master Map Prompt

Generate a canonical map of the known Great Citadel.

North at top.

Primary spine: Outside -> Entry Hall -> Small Library -> Foundational Door -> Great Hall -> Hall of Discovery.

Garden is west of Entry Hall and directly attached to the Entry Hall west wall.

Garden connects only to Entry Hall.

Media Antechamber is west of Great Hall, not adjacent to Garden.

Garden and Media Antechamber must be separated by empty map space.

No wall, doorway, path, shared boundary, label-line connection, visual connector, or architectural connection may exist between Garden and Media Antechamber.

No wall, doorway, path, shared boundary, label-line connection, visual connector, or architectural connection may exist between Garden and Great Hall.

Great Hall is the central compass hub with eight openings at exact 45-degree intervals.

Only canonical room connections may exist.

---

# Exterior Map Alignment Rule

Exterior maps and exterior blueprints must align to the same fixed compass orientation.

The Entry Hall exterior mass represents the southern known interior room.

The Garden must appear directly west of the Entry Hall exterior mass.

The bridge must extend southwest from the Entry Hall exterior mass and terminate at a landing platform southwest of the entire Citadel structure.

Exterior depictions do not override interior topology.

---

# Map Compliance Checklist

A canonical map is compliant only if north is top, the primary spine is preserved, Garden is connected only to Entry Hall, Garden is directly attached to Entry Hall, no non-canonical room connections exist, Great Hall remains the central hub, and Great Hall openings are positioned at exact 45-degree intervals.

---

# Topology Preservation Rule Expanded

Maps, room renders, exterior renders, doorway views, connected-room views, navigation diagrams, 360 panoramas, blueprints, and door renders must all describe the same underlying architecture.

Direct physical attachment relationships must remain direct. Non-adjacent rooms must remain non-adjacent.

---

# Canonical Bearing Requirement

Whenever a new room, exterior location, station, path, map, connection, reference, blueprint, or door render is added to the Codex, its canonical compass bearing and relationship to existing spaces should be explicitly defined.

End of Codex v3.0 — Map Core.
