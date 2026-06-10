# 🕶️ Onboarding Guide: Literature Review & Research Matrix for Context-Aware Zero-UI

Welcome to the **Code Studio AI Research Lab**. This guide establishes the mandatory workflow, literature logging standards, and Git guidelines for all team members working on our project: **"Context-Aware UI Adaptation for Zero-UI Environments"**.

---

## 🔍 1. Where to Find High-Impact Papers
Human-Computer Interaction (HCI) and spatial computing have highly specialized, fiercely competitive publication venues. Do not rely on generic software design blogs; find papers exclusively via:
* **Google Scholar:** [scholar.google.com](https://scholar.google.com/) (Filter: *Since 2024/2025* for recent generative spatial layouts and XR eye-tracking pipelines).
* **Elite HCI/AR Conferences:** **CHI** (ACM Conference on Human Factors in Computing Systems), **CSCW** (Computer-Supported Cooperative Work), **UIST** (Symposium on User Interface Software and Technology), and **IEEE ISMAR** (International Symposium on Mixed and Augmented Reality).

---

## 🛠️ 2. Search Strategy & Keywords
Avoid common mobile UI syntax. Use precise **Boolean Operators** (`AND`, `OR`, `""`) to filter for adaptive environments:
* **Core Adaptive Layout Query:** `"Spatial computing" AND "Adaptive user interface" AND "Augmented reality"`
* **Gaze & Interaction Query:** `"Eye-gaze tracking" AND "Intent prediction" AND "Information architecture"`
* **Zero-UI/Privacy Query:** `"Zero-UI" AND "Context-aware interaction" AND "Visual privacy masking"`

---

## 📖 3. How to Read & Critically Evaluate an HCI Paper
1. **The Telemetry Rig:** Look at how user tests were run. Did they use actual hardware smart glasses with a physical user panel, or did they use an idealized desktop screen-gaze simulation?
2. **The Adaptation Frequency:** How often does the UI regenerate its layout? Is it static until a user triggers a menu button, or does it process continuously at 60Hz matching human eye saccades?
3. **The Practical Gap (Our Opportunity):** Look closely at their **Limitations**. Most papers fail to bridge software layout logic with complex machine vision. *Our lab's competitive advantage is building a unified pipeline combining OpenCV scene tracking with structural deep-learning layout optimization solvers.*

---

## 📂 4. GitHub Directory Structure & Collaborative Git Rules
To avoid chaotic merge conflicts and ensure clean asset versioning, adhere strictly to these repository rules:

### Folder Architecture:
```text
Context-Aware-ZeroUI/
└── Literature_Review/
    ├── PDFs/                 # Store downloaded paper PDFs here
    │   └── Format: FirstAuthor_Year.pdf (e.g., Ishii_2024.pdf)
    ├── BibTeX/               # Raw BibTeX snippets for LaTeX compilation
    │   └── citations.bib     # Open and append your BibTeX blocks here
    └── Research_Matrix.md    # The central markdown table file
