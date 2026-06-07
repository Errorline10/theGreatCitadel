# Codex v3.2 — Map Core

Project: The Great Citadel
Version: v3.2
Role: Coordinate system, bearing rules, topology, map rendering, topology separation, exterior alignment, 360 compass normalization context, door count preservation, and map compliance.
Supersedes: /chatGPT/mapVault/Codex_v3.1_Map_Core.md

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

# 360 Orientation Note

For 360 equirectangular panoramas, compass layout is governed by the 360 Panorama Compass Normalization Rule in Render Continuity Rules.

---

# Primary Spine Layout

The foundational path is a north-south spine:

Outside -> Entry Hall -> Small Library -> Foundational Door -> Great Hall -> Hall of Discovery.

Garden is west of Entry Hall and directly attached to the west side of Entry Hall.

---

# Direct Adjacency Mapping Rule

On all canonical maps and blueprints, Garden must be drawn directly adjacent to the west side of the Entry Hall. A visible gap, connecting corridor, or bridge between Garden and Entry Hall is non-canonical.

---

# Topology Separation Rule

Canonical adjacency and canonical non-adjacency are both mandatory topology constraints.

Garden and Media Antechamber must not connect. Garden and Great Hall must not connect. Garden and all antechambers must not connect.

---

# Canonical Door Count Mapping Rule

Maps, blueprints, diagrams, room renders, exterior renders, 360 panoramas, door renders, and reference images must preserve canonical door counts.

Do not add non-canonical doors, corridors, arches, passages, stair exits, balcony exits, tunnels, hidden openings, or implied navigable connections.

Decorative architectural features are allowed only when they do not imply a navigable room connection.

---

# Great Hall Radial Geometry Rule

The Great Hall is the center of an eight-spoke compass system. The eight primary openings are evenly spaced at exactly 45-degree intervals.

0 degrees = Science Door
45 degrees = Philosophy Door
90 degrees = Arts Door
135 degrees = Personal Door
180 degrees = Foundational Door
225 degrees = Inventor's Door
270 degrees = Media Door
315 degrees = History Door

---

# Hall of Discovery Compass Geometry Rule

The Hall of Discovery has exactly four canonical doors aligned to cardinal compass bearings:

0 degrees / North = Astronomy Door
90 degrees / East = Logic Door
180 degrees / South = Science Door to Great Hall
270 degrees / West = Biology Door

No diagonal, upper-level, hidden, or secondary navigable openings are canonical.

---

# Canonical Map Render Block

Render a canonical architectural map of The Great Citadel. North must be at the top. South must be at the bottom. East must be on the right. West must be on the left. The map represents physical room topology, not artistic composition. Use a 1:1 square format.

---

# Exterior Map Alignment Rule

Exterior maps and exterior blueprints must align to the same fixed compass orientation.

The Entry Hall exterior mass represents the southern known interior room.

The Garden must appear directly west of the Entry Hall exterior mass.

The bridge must extend southwest from the Entry Hall exterior mass and terminate at a landing platform southwest of the entire Citadel structure.

Exterior depictions do not override interior topology.

---

# Topology Preservation Rule Expanded

Maps, room renders, exterior renders, doorway views, connected-room views, navigation diagrams, 360 panoramas, blueprints, and door renders must all describe the same underlying architecture.

Direct physical attachment relationships must remain direct. Non-adjacent rooms must remain non-adjacent.

End of Codex v3.2 — Map Core.