
# 🧮 Procedural Generation

## Overview

Procedural generation in *Emergent* is not just randomness—it’s emotional logic carved into code. Every mindscape is a reflection of choices, archetypes, and emotional resonance. The procedural systems ensure each run is thematically coherent, symbolically rich, and emotionally surprising.

---

## 🧠 Generation Philosophy

- **Meaningful Randomness**: Generation is seeded by player archetype and prior cycles.
- **Emotional Geometry**: Zones form based on internal states (Clarity, Stress, Echo).
- **Growth Reflection**: The world evolves as the player integrates fragments and choices.

> *The mindscape is not a place. It is a projection of what you are becoming.*

---

## 🌍 Zone Construction

### Mindscape Zones

- Zones are procedurally selected and shaped at cycle start.
- Number and type of zones influenced by player’s Archetype, emotional residue, and past failures.

| Zone Type           | Bias Condition |
|---------------------|----------------|
| Sea of Longing      | High Echo      |
| Mountains of Knowledge | High Clarity |
| Forest of Doubt     | High Stress    |
| Inversion Zone      | Conflicting Archetypes |
| Dream Fracture      | Late Cycle / Meta-Synthesis |

Each zone has:
- **Visual theme** tied to emotion
- **Fragment pool** (weighted by internal stats)
- **Unique mechanics or distortions**
- **Synthesis possibilities specific to that zone**

---

## 🧩 Fragment Distribution Logic

Fragments are not placed randomly.

- **Seeded by cycle ID + Archetype + zone emotion**
- **Weighted by emotional state and recent intrusions**
- **Clustering**: Fragments appear in thematic clusters
- **Echo Residues** may appear around unresolved zones

---

## 🌿 Branch & Node Generation

### Node Types

| Type           | Function |
|----------------|----------|
| Anchor Nodes   | Allow CoreSelf teleport |
| Fragment Nodes | Contain primary collectables |
| Reflection Nodes | Trigger lore or insight |
| Synthesis Nodes | Allow combination of fragments |

### Branch Logic

- Branches connect meaningful thoughts (not random paths)
- Maximum number per node increases with player growth
- Dead-end nodes often contain symbolic secrets or lore fragments

---

## 🔁 Cycle-Based Adaptation

Each cycle reacts to previous outcomes.

- **Success Bias**: Grants access to higher-order zones, rarer fragments
- **Failure Echo**: Seeds the next run with residues or emotional hazards
- **Archetype Drift**: Player’s Intent Archetype evolves subtly each run

> Over time, no two minds look the same.

---

## 🧪 Intrusion Integration

Intrusions are semi-scripted but procedurally infused.

- Location chosen based on Stress spikes and Echo pressure
- Intrusion form influenced by dominant emotion + zone context
- Visual distortion blends procedural and thematic logic

---

## ⚙️ Technical Notes

- Generation seeded with:
  - `player_id + cycle_number + archetype_hash`
- Weighted fragment pool with noise-based placement
- Spatial node graph constructed before rendering world
- Real-time adjustments based on stress and echo changes

---

## 🔮 Future Enhancements

- **Recursive Zone Folding**: Later cycles collapse earlier zones into abstract memory constructs
- **Emotionally Emergent Topology**: Terrain literally bends to reflect inner turmoil
- **Archetype-locked Events**: Whole microzones accessible only under specific conditions

---

In *Emergent*, procedural generation is not a tool.  
It is the **mind's memory machine**—weaving loss, hope, and insight into the fabric of each world anew.
