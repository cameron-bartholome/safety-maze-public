# 🔴 Safety Maze – Laser Reflection Simulator

**Safety Maze** is a visual simulation tool that traces laser beams through a 2D maze and shows how they reflect off surfaces.  
Originally built for quick testing, learning, and debugging of beam paths using Python + Tkinter.

---

> ⚠️ **Notice:**  
> This project has now been moved to a **private repository** for continued development.  
> As the project matured, I decided to restrict access while expanding features and preparing future releases.  
> 
> If you’d like to learn more or discuss the project, feel free to connect with me on linkdin

---

> ⚠️ **Disclaimer:** This is a solo laser simulation project built while I juggle Python, laser physics, and questionable design decisions.  
> It’s currently held together with duct tape, Tkinter, and hope.  
> Things are messy. That’s intentional (probably).  
> There’s a later stage where everything is supposed to look clean, modern, and professional ... assuming I ever get there.  
> Until then, welcome to the chaos. It works… mostly.

---

## ✅ Stage 1 – Core Simulation [Completed]
- Tkinter GUI + maze presets  
- Reflection logic + CSV logging  
- Beam path visualization (red/blue/green markers)  
- Reflection count display  
📦 Finalized: **2025-07-02**

---

## ✅ Stage 2 – Geometry Expansion [Completed]
- Maze shaping + editable presets  
- Visualize dimensional changes in GUI  
- Load/save maze presets  
📦 Finalized: **2025-08-15**

---

## 🔬 Stage 3 – Material Presets + Basic Beam Decay [Active]
- Preset surface reflectivity (aluminum, anodized, plastic)  
- Basic energy decay per bounce  
- Extend CSV with power tracking  
- Beam strength visualized via opacity  

---

## ⚡ Stage 4 – Energy Mapping + Surface Interaction [Planned]
- Map total energy dissipation along beam path  
- Visualize drop-off with gradients or line thickness  
- Factor in absorption per surface type  
- Summarize total energy loss in GUI  

---

## 🔍 Stage 5 – Gaussian Beam Modeling + Divergence [Planned]
- Simulate beams with width, not just a line  
- Gaussian intensity distribution  
- Inputs: beam waist (w₀), divergence (θ)  
- Handle clipping in narrow passages  

---

## 📊 Stage 6 – Result Analysis + Graph Exports [Planned]
- Add result summary pane  
- Graphs: power vs bounces, beam strength, absorption  
- Export: CSV / JSON / PNG / PDF  
- Annotate loss points  

---

## 🎨 Stage 7 – UI/UX Redesign in Figma [Planned]
- Wireframes + mockups in Figma  
- Dark mode + accessibility  
- Plan responsive desktop/tablet layouts  

---

## 💻 Stage 8 – Frontend Rebuild (React or PyQt) [Planned]
- Replace Tkinter with modern UI  
- Rebuild canvas interactions (zoom, pan, etc.)  
- Load presets + input data  
- Real-time feedback  

---

## 🔗 Stage 9 – Backend Refactor (FastAPI or Flask) [Planned]
- Move simulation logic to backend module  
- REST endpoints for simulation + results  
- Support cloud/local deployment  

---

## 🚀 Stage 10 – Final Tool Packaging + Sharable App [Planned]
- Bundle app for desktop (PyInstaller/Electron/Tauri)  
- Versioning + changelog  
- Example simulations + demo GIFs  
- Public landing page
