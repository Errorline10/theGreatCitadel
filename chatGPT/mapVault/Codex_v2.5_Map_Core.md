# Codex v2.5 — Map Core

Project: The Great Citadel
Version: v2.5
Role: Coordinate system, bearing rules, topology, map rendering, and map compliance.
Supersedes: Map portions of /chatGPT/codexVault/Codex_v2.4_Canon_Render_Rooms.md

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

Canonical room connections take precedence over visual symmetry.

Rooms may only connect where a canonical doorway or passage exists.

Do not create shortcut connections.

Do not connect rooms that merely share a compass bearing.

Preserve all known room relationships exactly.

Unknown areas may be omitted or shown as unexplored.

Use parchment-map styling unless otherwise requested.

Use a 1:1 square format.

Display room names, compass orientation, and major paths.

---

# Great Citadel Master Map Prompt

Generate a canonical map of the known Great Citadel.

North at top.

Primary spine:

Outside -> Entry Hall -> Small Library -> Foundational Door -> Great Hall -> Hall of Discovery

Garden is west of Entry Hall.

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
- Great Hall remains the central hub.
- Great Hall openings are positioned at exact 45-degree intervals.
- No non-canonical room connections exist.
- All displayed room connections correspond to canonical doors or passages.
- Room placement follows the Canonical Bearing Rules.
- Topology is prioritized over visual symmetry.

---

# Render-Derived Mapping Rule

Every room definition should be simple enough that a map can be generated directly from compass orientation, door locations, connected rooms, and canonical topology without requiring interpretation.

If a room definition cannot be converted into a map, the room definition is incomplete.

---

# Topology Preservation Rule Expanded

Maps, room renders, doorway views, connected-room views, and navigation diagrams must all describe the same underlying architecture.

A room render may show only part of a room. A map may show all of a room. Neither may contradict the other.

---

# Canonical Bearing Requirement

Whenever a new room, antechamber, realm, station, path, map, or connection is added to the Codex, its canonical compass bearing and relationship to existing spaces should be explicitly defined.

Rooms should be added in a manner that allows deterministic map generation.

End of Codex v2.5 — Map Core.
