## 2U-server-chasis-design
A 19-inch 2U rackmount server chasis modelled and assembled in SOLIDWORKS
## 📸 Visual Showcase

Renders/SOLIDWORKS Premium 2023 SP0.1 - [2U_Server_Chasis_Assembly _] 10_8_2026 9_31_13 PM_1.png




## 📊 Technical Specifications

| Parameter | Specification |
| :--- | :--- |
| **Enclosure Standard** | 19-inch Standard Rackmount (2U Height) |
| **Footprint Dimensions** | 430 mm (Width) × 400 mm (Length) × 88 mm (Height) |
| **Sheet Metal Gauge** | Uniform 1.0 mm thickness |
| **Top Cover Design** | Slip-on U-profile with 15 mm drop flanges |
| **Material Selection** | Cold Rolled Steel (AISI 1020) / Aluminum 6061-T6 |

## ⚙️ Design & Manufacturing Highlights

* **Sheet Metal Forming:** Created using base flanges, edge flanges, and controlled bend allowances to simulate real-world press brake press-forming.
* **Thermal Management:** Integrated precision rear exhaust ventilation slots to ensure optimal continuous airflow and prevent internal heat accumulation.
* **Assembly & Interference Validation:** Conducted automated multi-component clearance and interference checks to guarantee zero physical collisions between the chassis frame, mounting points, and the slip-on top cover.
* **Fastener Integration:** Configured standard metric hardware layout with proper clearance holes for structural assembly.

  *
  🗂️ Repository Directory Structure

```text
2u-server-chassis-design/
│
├── CAD/                  # Neutral .STEP files and native assembly files
│   ├── 2U_Assembly.step
│   └── ...
├── Renders/              # High-resolution isometric and exploded view screenshots
│   └── isometric-view.png
├── Drawings/             # 2D technical production drawings (PDFs)
│   └── Chassis_Drawing.pdf
└── Docs/                 # Mass properties reports and engineering notes
    └── Mass_Properties.txt
