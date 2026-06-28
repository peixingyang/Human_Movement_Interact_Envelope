# Human Movement Interact Envelope

A parametric design workflow and computational engine in Rhino & Grasshopper (Python) for human-machine interaction, featuring soft robotic morphing logic and adaptive spatial envelopes.

---

## 🚀 Core Components

The repository contains the following advanced computational modules, all tightly integrated into the **Envelope** development framework:

### 1. Local Adaptive Envelope Generator (`Intelligent Ergonomics Edition`)
* **Mechanism**: Manages localized deformation of the interaction envelope around human joint topology through autonomous PUSH/PULL boundaries.
* **Feature**: Employs an inward contraction inverse-pulling engine to dynamically shrink the envelope via `Morph_Factor` linear interpolation (Lerp), ensuring a precise, body-fitting skin.

### 2. Global Envelope Assembly Plant (`Pole End Anchorage Repair Edition`)
* **Mechanism**: Constructs a continuous global envelope lofting sequence by processing and weaving spatial curve matrices into a unified shell structure.
* **Feature**: Fixes structural envelope deformation anomalies at polar boundaries, locks boundary conditions to rigid limits, and filters localized seam geometry seamlessly.

### 3. Differential Inflatable Envelope Generator (`Soft Pneumatic Variant`)
* **Mechanism**: Simulates real-time cross-sectional pressure differential adjustments within the inflatable envelope based on curve tangents and localized rotational transformations.
* **Feature**: Exaggerates asymmetric envelope inflation boundaries while firmly constraining forward directional safety ceilings to prevent over-expansion.

---

## 🛠️ Requirements & Environment

* **Platform**: Rhino 7 / Rhino 8
* **Environment**: Grasshopper (built-in Python/GhPython components)
* **Dependencies**: Standard `Rhino.Geometry`, `scriptcontext`, and `Grasshopper` core libraries.

---

## 📂 How to Use

1. Clone or download this repository.
2. Open the primary `.3dm` Rhino file to load the reference human positioning or bounding geometries.
3. Open the corresponding `.gh` or `.ghx` file in Grasshopper.
4. Connect your curves and human skeleton nodes (`Pts_Curr`) into the input ports of the respective Python components.
5. Drive the `Morph_Factor` or `Play` toggle to trigger live visualization and viewport refreshes.

---

## 🤝 Acknowledgments & AI Collaboration

This project and its computational core were developed with the collaborative assistance of advanced AI foundation models. They provided significant support in code internationalization, technical comment refactoring, and envelope logic optimization:
* **Google Gemini** (Architecture framing, localization)
* **Anthropic Claude** (Algorithm analysis and safety checks)
