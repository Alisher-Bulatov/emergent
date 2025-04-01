
# 🌿 Branch Sculpting

## Overview

Branch Sculpting is a core mechanic in *Emergent*, symbolizing the player’s growing agency within the mindscape. It allows the Consciousness to extend new paths—branches—by directing focus and intent. These branches are more than traversal mechanics; they are metaphors for forming new thoughts, possibilities, and connections.

---

## 🎮 Gameplay Mechanics

### Unlock Phase

- Becomes available in **Phase 3** of Cycle 1 (Insight Phase).
- Introduced narratively as the player's first active act of reshaping their inner world.

### Activation

- Activated by holding a specific input while looking in a direction.
- A branch visually grows from the **CoreSelf** or current **MindNode** toward the aimed direction.
- Solidifies into a traversable path, enabling new movement and exploration.

### Visual Feedback

- Grows as a glowing tendril of light.
- Curves organically, representing mental flow.
- Snaps to nearby fragments if applicable.

---

## 🧠 Technical Implementation (from Design Bible)

### Data Structure

- **MindNodes** represent fragment locations or memory loci.
- **BranchEdges** connect nodes and are rendered as curves.

### Sculpting Process

1. Identify the **current node context** (tip of branch or CoreSelf).
2. Determine **gaze direction**.
3. Project forward to find a **valid endpoint** (max length or snap to fragment).
4. Create new **MindNode** and mark stability if:
   - It’s max distance.
   - It holds a major fragment.
5. Create **BranchEdge** connecting nodes.
6. Render the branch.
7. Allow traversal from current position.

### Constraints

- Cannot sculpt during Intrusions or high stress.
- One active branch per node at a time (limits chaos).
- May require emotional calm to function.

---

## 🌀 Symbolic Significance

Branch Sculpting represents:

- **Cognitive expansion** – forging new pathways of thought.
- **Agency** – player asserting will over mindscape.
- **Reflection** – branches are shaped by where you *choose* to look.
- **Memory seeking** – drawn to fragments and buried insights.

It aligns with the game’s theme: *we shape the mind as we explore it.*

---

## 🛠 Design Tips

- Use it to reward curiosity—hide rare fragments just out of reach.
- Pair with **Projection** for open traversal later in the game.
- Combine with **Anchor** to re-center CoreSelf at new discoveries.

---

## 🧪 Future Enhancements

- Upgradeable branch range via **Modules**.
- Multiple branching styles (e.g., chaotic vs. focused).
- Emotional state affecting branch form: stressed branches flicker, calm ones glow.

---

Branch Sculpting is the player’s first taste of **true authorship** in *Emergent*. From following paths to forging them, this moment marks the mind’s shift from passive reflection to creative becoming.
