## Overview

The **Flotsam Mod Menu** is a comprehensive **single-player modification framework** that grants full control over colony pacing, resource flow, environmental behavior, automation, and construction.
Unlike a simple trainer, this mod menu supports modular plugins, live world editing, curve-based multipliers, and advanced crafting/production tweaks.

It enhances creativity without breaking the tranquil soul of *Flotsam*.

[!IMPORTANT]
All features operate strictly **offline** and do not interact with multiplayer environments.

---

## Features

### 💧 Global Resource Editing

Modify the way your colony gathers and consumes materials:

* adjustable wood/plastic/scrap multipliers
* instant resource injection
* debris spawn scaling
* infinite food/water modes
* inventory & storage overrides

### 🛠 Colony & Construction Tools

Streamline or reimagine colony management:

* instant building
* zero-cost construction
* boosted worker stamina
* job priority overrides
* global crafting time scaling

Perfect for both relaxed builds and high-speed expansion.

### 🌱 Environment & World Systems

Tune the sea itself:

* weather calm / storm intensity sliders
* fish spawn multipliers
* kelp/seaweed regeneration rate
* debris field density
* daylight duration modifiers

### 🚤 Navigation & Drifter Utilities

Help your explorers move freely:

* raft speed multiplier
* instant travel between map nodes
* no drowning / no exhaustion
* swimming cost adjustment

### 👁 Visual & Debug Modules

Gain improved situational awareness:

* resource highlight vision
* debris radar
* production flow overlay
* performance metrics panel

### 🧩 Plugin Loader (.flotmod)

Load custom mini-mods:

* new crafting trees
* colony automation packs
* economic overhauls
* UI enhancements
* shader effects

### 🖥 In-Game Mod Menu Overlay

The UI includes:

* sliders
* toggles
* numeric fields
* curve editors
* keybind manager

Simple, responsive, and ocean-themed.

---

## Compatibility

| Platform       | Support | Notes                            |
| -------------- | ------- | -------------------------------- |
| Windows 10/11  | ✔️      | Full support                     |
| Steam Release  | ✔️      | Auto-detected                    |
| GOG Release    | ✔️      | Manual path selection            |
| Linux (Proton) | ⚠️      | Menu overlay partially supported |
| Console Ports  | ❌       | Not supported                    |

*Accessibility note:* High-contrast theme, text scaling, and full keyboard navigation included.

---

## Setup ⚡

1. **Download the Flotsam Mod Menu build**
   Extract into a clean folder.

2. **Launch the Mod Loader**
   It scans for and links to Flotsam’s game process.

3. **Start Flotsam**
   Enter your settlement or create a new floating colony.

4. **Press the Menu Key** (default: **Insert**)
   A sleek ocean-blue interface unfolds.

5. **Customize the World**
   Adjust colony behavior, automate tasks, or reshape resources with intuitive controls.

### Sample Hotkeys

```plaintext
Insert — Open Mod Menu  
F1 — Infinite Materials  
F2 — Instant Build  
F3 — Calm Weather  
F4 — Highlight Resources  
F5 — Speed Multiplier  
F7 — Auto-Collect Debris
```
---

## Mermaid Diagram — Mod Menu Architecture

```mermaid
flowchart TD
    A[Launch Mod Loader] --> B[Scan Flotsam Process]
    B --> C{Process Found?}
    C -->|Yes| D[Inject Mod Framework]
    D --> E[Load Base Modules]
    E --> F[Load Plugins (.flotmod)]
    F --> G[Activate In-Game Menu]
    G --> H[Edit World / Colony / Resources]
    C -->|No| I[Retry Scan or Manual Selection]
```

---

## Advanced Capabilities

### 🔬 Curve-Based Scaling

Fine-tune colony progression:

```json
{
  "wood_multiplier": 12,
  "plastic_multiplier": 10,
  "food_multiplier": 6,
  "craft_speed_curve": "ease_out_quad"
}
```

### 🤖 Automation Scripts

Optional scripting layer for:

* auto-crafting
* automated drifter assignment
* resource balancing
* continuous debris collection sequences

### 🌊 Environmental Logic Editing

Modify:

* weather rotation
* sea current behavior
* spawn clusters
* scavengable biome distribution

### 🔐 SaveGuard

Persistent changes generate automatic backups.

[!NOTE]
Runtime adjustments do not modify save data.

---

## Example Mod Menu Profile

```json
{
  "profile": "calm_archipelago",
  "resources": {
    "wood_multiplier": 5,
    "plastic_multiplier": 5
  },
  "colony": {
    "instant_build": true,
    "boosted_stamina": true
  },
  "world": {
    "calm_weather": true,
    "debris_density": 1.4
  },
  "visuals": {
    "resource_highlight": true
  }
}
```

---

## FAQ

### **Does the mod menu break immersion?**

Not at all—its design emphasizes subtlety and atmospheric clarity.

### **Will this corrupt my save?**

Runtime features are safe. Permanent mods trigger SaveGuard backups.

### **Can I use other mods with it?**

Yes—most visual or economic mods work seamlessly.

### **Why aren't some features working?**

Game version differences may require updating offsets via the built-in updater.

### **Are hotkeys customizable?**

Fully—every key can be rebound.

---

## Final Thoughts

*Flotsam* is a peaceful drifting odyssey—equal parts survival, hope, and creativity.
A Mod Menu should honor that rhythm, offering tools that lighten the burden without stealing the magic of building a floating civilization from nothing.

Whether you seek a serene ocean village, a boosted mega-settlement, or a sandbox of pure creativity, this Mod Menu sails with you—quiet, adaptive, dependable.
