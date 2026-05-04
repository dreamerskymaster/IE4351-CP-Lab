# IE 4351 — Cyber-Physical & Advanced Manufacturing Labs

> **Northeastern University · MIE Department**
> Interactive, slide-based laboratory materials for **IE 4351: Cyber-Physical Manufacturing**.

---

## 🗂️ Repository Structure

```
IE4351/
├── index.html                       # Central navigation hub (start here)
├── lab1.html                        # Lab 1: Cyber-Physical Manufacturing & Industry 4.0
├── lab2.html                        # Lab 2: Subtractive Manufacturing (CNC Milling)
├── lab3a.html                       # Lab 3A: Additive Manufacturing (FDM 3D Printing)
├── lab3b.html                       # Lab 3B: Laser Manufacturing (Laser Engraving)
├── lab4.html                        # Lab 4: Online Robot Programming (UR5e)
├── offline_robot_programming_lab.html  # Lab 5: Offline Robot Programming (OCTOPUZ)
├── mie_lab_safety_guide.html        # MIE Lab Safety Guide
├── vlab-install-guidance.html       # COE VLAB / OCTOPUZ Installation Guide
└── img_*.png                        # AI-generated photorealistic equipment images
```

---

## 🏠 Navigation Hub

Open **[`index.html`](index.html)** in any modern browser to access the central dashboard. All lab sessions are reachable from there — no server or build step required.

---

## 📚 Laboratory Presentations

Each lab is a self-contained, interactive slide deck navigated with keyboard arrow keys or on-screen buttons.

### ⚙️ [Lab 1 — Cyber-Physical Manufacturing](lab1.html)
**Equipment:** Festo CP Factory  
Topics covered:
- Industry 4.0 and Smart Manufacturing principles
- Cyber-Physical Systems (CPS) and the Industrial Internet of Things (IIoT)
- Modular, networked production architecture
- Manufacturing Execution Systems (MES)
- Integration of heterogeneous manufacturing equipment

---

### 🔧 [Lab 2 — Subtractive Manufacturing](lab2.html)
**Equipment:** Emco Concept Mill 105  
Topics covered:
- Workplace safety & shop attire
- Machine components (spindle, ATC, precision slides)
- Coordinate systems (X, Y, Z axes) and work zero points
- G-Code fundamentals and CAM programming with Fusion 360

---

### 🖨️ [Lab 3A — Additive Manufacturing](lab3a.html)
**Equipment:** Stratasys F170 (FDM)  
Topics covered:
- FDM process and material selection (PLA, ABS, ASA)
- Support strategies and build orientation
- GrabCAD Print workflow from CAD model to print job
- Post-processing and support removal

---

### 🔆 [Lab 3B — Laser Manufacturing](lab3b.html)
**Equipment:** Gravotech LS900 CO₂ Laser  
Topics covered:
- Laser engraving vs. laser cutting principles
- Power, speed, and resolution settings
- Gravotech Laser Designer workflow
- Engraving the Northeastern logo and personal design onto a leather coaster

---

### 🦾 [Lab 4 — Online Robot Programming](lab4.html)
**Equipment:** Universal Robots UR5e (6-axis collaborative arm)  
Topics covered:
- Robot safety and collaborative operation modes
- PolyScope teach pendant navigation
- Waypoint creation and program flow
- Part-transfer task: cell phone case from carrier to assembly fixture

---

### 🖥️ [Lab 5 — Offline Robot Programming](offline_robot_programming_lab.html)
**Software:** OCTOPUZ (via COE VLAB)  
**Equipment simulated:** UR5e + FANUC CR-7iA/L  
Topics covered:
- Digital twin workcell construction
- Offline program creation, simulation, and collision detection
- Multi-robot workflow orchestration
- Post-processing and virtual commissioning

---

### 🛡️ [MIE Lab Safety Guide](mie_lab_safety_guide.html)
Mandatory pre-lab safety orientation covering:
- Personal Protective Equipment (PPE) requirements
- Machine-specific hazard protocols
- Emergency procedures and lab conduct rules

---

### 💻 [VLAB / OCTOPUZ Installation Guide](vlab-install-guidance.html)
Step-by-step setup instructions for accessing the COE Virtual Lab to run OCTOPUZ from any device (on-campus or remote).

---

## ✨ Features

| Feature | Details |
|---|---|
| **Interactive Slides** | Keyboard arrow key navigation, smooth CSS transitions |
| **Photorealistic Assets** | 8 AI-generated equipment images for professional visual context |
| **Embedded Timers** | Built-in countdown timers for lab leads |
| **Progress Indicators** | Slide progress bars for at-a-glance pacing |
| **Glassmorphic UI** | Modern dark/light design system with gradient accents |
| **Zero Dependencies** | Pure HTML + CSS + JS — open any file directly in a browser |
| **Evergreen Content** | No semester-specific dates or cohort references — reuse as-is |

---

## 🖼️ Image Assets

All `img_*.png` files are AI-generated photorealistic renders of the physical equipment used in each lab. They must remain in the same directory as the HTML files to display correctly.

| File | Used In |
|---|---|
| `img_hub_hero.png` | `index.html` hero banner |
| `img_lab1_cp_factory.png` | `lab1.html` title slide |
| `img_lab2_cnc_mill.png` | `lab2.html` title & equipment slides |
| `img_lab3a_3d_printer.png` | `lab3a.html` title slide |
| `img_lab3b_laser_cutter.png` | `lab3b.html` title slide |
| `img_lab4_robot_arm.png` | `lab4.html` title slide |
| `img_vlab_octopuz.png` | `vlab-install-guidance.html` & `offline_robot_programming_lab.html` |
| `img_safety_ppe.png` | `mie_lab_safety_guide.html` |

---

## 🚀 Usage

1. **Clone or download** this repository.
2. Keep all files in the **same directory** (images must be co-located with the HTML files).
3. Open **`index.html`** in any modern browser (Chrome, Firefox, Edge, Safari).
4. No build step, server, or internet connection is required.

> **For faculty:** All semester-specific content (dates, section numbers, cohort names) has been removed. These materials are ready for direct reuse in any future semester without modification.

---

## 🏗️ Technical Notes

- **Navigation:** Arrow keys (`←` / `→`) or the on-screen prev/next buttons advance slides.
- **Responsive:** Layouts adapt to projector (16:9), laptop, and tablet viewports.
- **Slide CSS classes:** Hero images use `.hero-image-wrapper` and `.hero-image-overlay` — reuse these for any new slides you add.

---

*Created and maintained by **Ajith Srikanth** · MIE Department, Northeastern University*
