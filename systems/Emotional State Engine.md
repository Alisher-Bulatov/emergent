
# 💢 Emotional State Engine

## Overview

The Emotional State Engine governs the fluctuating internal landscape of the player in *Emergent*. It transforms fragment absorption, environmental stimuli, and player choices into meaningful emotional metrics that directly affect gameplay, narrative, and perception. These emotional states are not just numbers—they are the dynamic soul of the experience.

---

## 🎭 Core Emotional Stats

### 🔷 Clarity
- **Represents**: Focus, calm, and lucidity.
- **Base Max**: 100 (increases via Clarity Modules).
- **Functions**:
  - Reduces stress gain over time.
  - Enables advanced synthesis under emotional alignment.
  - Required for high-level insights and deep zone navigation.
- **Visual Cue**: Brightening aura around CoreSelf, harmonic ambient tones.

### 🔺 Stress
- **Represents**: Emotional strain and instability.
- **Base Threshold**: 100 (increased via Resilience Modules).
- **Functions**:
  - Accumulates from negative fragments and events.
  - Triggers **Intrusions** at threshold.
  - Impairs clarity and cognitive control.
- **Visual Cue**: World distortion, heartbeat audio, red visual filter.

### 🕳 Echo
- **Represents**: Lingering, unresolved mental residue.
- **Range**: 0–100.
- **Functions**:
  - Increases when absorbing many fragments without synthesis.
  - Amplifies Stress gain.
  - May trigger passive intrusions or ghost-layer effects.
- **Visual Cue**: Faint doubles, echo sounds, UI glitching.

---

## ⚙️ Emotional Feedback Loops

### Emotional Decay

- **Clarity Decay**: Very slow, only under high stress.
- **Stress Decay**: Accelerated by Clarity.
- **Echo Decay**: Only via synthesis or meditation.

> Formula:  
> `StressRecoveryRate = k * (currentClarity / maxClarity)`  
> `EffectiveStressGain = BaseStress * (1 + Echo%)`

---

## 🧘 Emotional Tools

### 🌀 Meditation

- **Use**: Drains Stress, reduces Echo.
- **Availability**: Only at Core Sanctum or safe zones.
- **Cooldown**: Enforced to prevent abuse.
- **Visual**: Breathing light, dissolving fog.
- **Audio**: Resonant chimes, softening ambience.

### 🧩 Synthesis

- **Use**: Reduces Echo, provides Clarity and abilities.
- **Effect**: Converts emotional load into insight.
- **Emotional Requirement**: Varies by fragment combo.
- **Risk**: Wrong state can fail synthesis and increase Echo.

---

## ⚔ Intrusion Triggering

- **Threshold**: Stress ≥ 100 triggers an Intrusion unless already active.
- **Other Triggers**:
  - Absorbing unstable fragments.
  - Scripted narrative events.
- **Modifiers**:
  - High Echo = longer/more intense intrusions.
  - Archetype alignment affects type of intrusion.

---

## 📊 Stat Modifiers from Modules

| Module Type        | Effect |
|--------------------|--------|
| Clarity Module     | +Max Clarity (e.g., +15) |
| Resilience Module  | +Stress Threshold / -Stress Gain |
| Insight Module     | Unique bonuses, e.g. slower Echo gain |
| Echo Dampener      | Flat reduction to Echo over time |

---

## 🌪 Emotional Resonance by Zone

| Zone               | Effect on Emotions |
|--------------------|--------------------|
| Mountains of Knowledge | Slows Stress buildup |
| Forest of Doubt    | Increases Echo gain |
| Sea of Longing     | Stress decay halved |
| Inversion Zone     | Inverts Clarity effects |
| Dream Fracture     | Randomized feedback, surreal modifiers |

---

## 🧠 Symbolic Design Philosophy

The Emotional State Engine reinforces *Emergent*’s core message:  
> **“Growth comes not from escape, but from integration.”**

- Clarity allows insight.
- Stress challenges it.
- Echo reveals the weight of unprocessed thought.

To survive and evolve, players must not just act—they must *feel*, *reflect*, and *resolve*.

---

## 🔮 Future System Extensions

- **Emotional Weather**: Zones react to dominant emotion.
- **Voice of the CoreSelf**: Inner narration based on emotional stats.
- **Emotional Imprints**: Echo-based ghost fragments with lingering dialogue.

---

The engine doesn't simulate emotion. It *is* emotion—alive, reactive, and central to the game's unfolding soul.

