# 🚀 CHOOSE.YOUR.ROADMAP — Interactive Engineering Career Matrix

> An interactive 3D engineering career and skill roadmap designed to eliminate tutorial paralysis for undergraduate engineering students.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Frontend](https://img.shields.io/badge/architecture-Vanilla_HTML_CSS_JS-orange.svg)
![3D Engine](https://img.shields.io/badge/3D_Engine-Three.js_WebGL-purple.svg)
![Status](https://img.shields.io/badge/status-Production_Ready-emerald.svg)

---

## 🌐 Live Demo & Deployment
Hosted directly on **GitHub Pages**:
👉 **[https://shahrukhkathat199.github.io/myfirstrepo/](https://shahrukhkathat199.github.io/myfirstrepo/)**

*(To enable GitHub Pages in this repository: go to **Settings > Pages > Branch: `main` / `master` > Save**)*

---

## 💡 The Problem & Engineering Perspective
Undergraduate engineering students frequently face **cognitive overload and tutorial fatigue**. Traditional roadmaps are static PNG diagrams that show hundreds of confusing arrows with zero prerequisite enforcement, realistic time estimates, or verifiable project deliverables.

**CHOOSE.YOUR.ROADMAP** solves this through **progressive disclosure** and visual computing:
- Future milestones remain locked until foundational prerequisites are completed.
- A **3D isometric matrix** powered by Three.js provides visual hierarchy and spatial perspective.
- Each milestone provides verified, **100% free university/industry resources** (Harvard CS50, Fast.ai, MIT OCW, PortSwigger, etc.) and a practical portfolio mini-project.

---

## 🛠️ Core Features

1. **Interactive 3D Skill Matrix (Three.js WebGL)**:
   - Dynamic 3D isometric nodes floating in an engineering grid that respond to mouse coordinates.
   - Clickable nodes that directly invoke detailed inspector drawers.

2. **4 Specialized Engineering Disciplines (36 Milestones)**:
   - 💻 **Computer Science (CSE)**: Memory management, DSA, Computer Org, Operating Systems, Databases, Distributed Systems, Compilers, and HPC.
   - 🤖 **AI & Machine Learning**: Linear algebra, Scientific Python, Classical ML, Deep Learning, Transformers & NLP, Vision, RL, MLOps, and LLM RAG.
   - 📊 **Data Science**: Probability & statistics, Data wrangling, Advanced SQL, Predictive modeling, Apache Spark big data, Stream analytics, and Causal inference.
   - 🛡️ **Cyber Security**: Packet inspection, Linux hardening, Cryptography, OWASP Top 10 web security, Penetration testing, SIEM SOC ops, Reverse engineering, and DevSecOps.

3. **Dual Visualization Modes**:
   - **Prerequisite Graph View**: Connected with animated SVG Bezier wire traces that illuminate upon completing dependencies.
   - **Structured Card Matrix**: Clean 3-tier responsive grid (Foundation, Core, Advanced).

4. **Intelligent Dashboard HUD**:
   - **Recommended Next Target**: Persistent spotlight highlighting the next milestone to tackle.
   - **Progress Ring**: Real-time circular SVG indicator showing progress percentage, hours remaining, and engineering rank titles.

5. **Gamification & Delights**:
   - Synthesized **Web Audio API** sound effects (clicks, level chimes, mute toggle).
   - **Celebration Confetti burst** upon completing skills.
   - **Trophy Cabinet**: 5 unlockable engineering badges persisted via `localStorage`.

6. **Student Utilities**:
   - **Export Checklist**: Instant one-click Markdown study plan download.
   - **Instant Search & Filter Chips**: Press `Ctrl+K` or `/` to search topics, tools, and prerequisites.
   - **Theme Engine**: Seamless toggle between Cosmic Dark Mode and Technical Blueprint Light Mode.

---

## 🎨 Design System
- **Typography**: Plus Jakarta Sans (headings & body) & JetBrains Mono (metrics & code tags).
- **Aesthetic**: Modern glassmorphism with 14px card radius, 8px layout rhythm, and WCAG AA high-contrast compliance.
- **Performance**: Zero build step, zero frameworks, 60 FPS WebGL rendering, 100% static hosting on GitHub Pages.

---

## 📂 Project Structure
```
├── index.html       # Complete self-contained web application
└── README.md        # Documentation and competition case study
```

---

## 🚀 Running Locally
Clone the repository and open `index.html` in any modern web browser:
```bash
git clone https://github.com/shahrukhkathat199/myfirstrepo.git
cd myfirstrepo
# Open in browser directly:
start index.html
# Or serve via Python:
python -m http.server 8080
```

---

*Designed and engineered with passion for engineering design competitions.*