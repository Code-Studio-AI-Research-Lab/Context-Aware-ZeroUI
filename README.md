# Context-Aware UI Adaptation for Zero-UI and Spatial Environments

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Framework: OpenCV / Unity / PyTorch](https://img.shields.io/badge/Framework-OpenCV%20%2F%20Unity%20%2F%20PyTorch-orange.svg)]()
[![Domain: Human-Computer Interaction (HCI)](https://img.shields.io/badge/Domain-HCI%20%26%20Spatial%20Computing-pink.svg)]()

This repository hosts the computational layouts, gaze-telemetry loggers, and context-aware adaptation logic for the **Zero-UI Dynamic Interaction Framework**. As computing shifts away from physical screens toward Augmented Reality (AR) glasses and smart contact lenses, static application layouts become obsolete. This project engineers a dynamic layout optimization model that reads a user's real-time environmental context, physical movement vectors, and eye-gaze tracking telemetry to organically adapt, resize, and project floating interface controls safely and privately within a 3D spatial field.

---

## 📌 Research Vision & Core Concept
In a screenless ecosystem, user interfaces must respect both physical geometry and social boundaries. A standard button shouldn't block a user's view while they are walking down a crowded street, nor should confidential text float openly in a public train. This project introduces a three-layer adaptive engine:
1.  **Spatial Geometry Mapping:** Using computer vision to detect physical constraints (walls, tables, moving obstacles) so interface modules never clip into real-world geometry.
2.  **Cognitive Gaze Telemetry:** Predicting user intent by analyzing continuous dwell-time and saccadic eye movements to highlight or hide UI components intuitively.
3.  **Context & Privacy Adaptation:** Shifting layout transparency, sizing, and position depending on behavioral states (e.g., automatically shrinking text fields or applying visual masks when high-density public crowds are detected).

---

## 🛠️ Key Features & Methodology
1. **Dynamic Spatial Anchoring Engine:** Logic workflows calculating ideal placement coordinates for floating virtual elements using environment occlusion algorithms.
2. **Gaze-Glint Intent Predictor:** Deep learning models mapping rapid eye movements to specific layout component scaling behaviors.
3. **Crowd-Responsive Privacy Filters:** Automated heuristic filters that modify contrast ratios and rendering priority based on surrounding pedestrian proximity counts.
4. **HCI Interaction Telemetry Suite:** Real-time logging metrics measuring user task-completion times, error rates, and cognitive drift across variable environmental scenarios.

---

## 📂 Repository Structure
```text
├── src/
│   ├── gaze_telemetry/     # Eye-tracking processing, calibration, and blink filtering
│   ├── spatial_mapping/    # Scene parsing, obstacle detection, and plane tracking anchors
│   ├── adaptive_layout/    # Dynamic layout solvers, boundary optimization, and sizing nodes
│   └── privacy_filters/    # Contrast shift algorithms and real-time crowd masking rules
├── assets/                 # Lightweight UI design configurations and component mockups
├── simulations/            # Mock situational data profiles (Walking, Public Transit, Desk Work)
├── notebooks/              # Saccade heatmaps, layout response curves, and performance graphs
├── Literature_Review/      # Team research matrices and BibTeX reference files
└── README.md
