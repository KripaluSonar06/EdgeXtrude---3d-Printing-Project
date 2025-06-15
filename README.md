# EdgeXtrude-3d Printing Project
EdgeXtrude Panzer III is a parametric Solid Edge 2025 CAD model and 3D‑printed scale of the early‑war WWII tank. It features a rotating turret, elevating gun, optimized PLA prints on a Creality Ender‑3, curated slicing profiles, cleaned G‑code, and a QR‑linked demo.

A parametric Solid Edge design and 3D‑printed scale model of the WWII Panzer III (early‑war variant), built by Team EdgeXtrude. This project demonstrates the full digital‑fabrication pipeline: CAD modeling, slicing, printing, assembly, and mechanical movement.

For more detailed go to this drive link , where you can go through our ppt , video and other files - https://drive.google.com/drive/folders/1kPaTNsE83MmNdSoIJOmHf4R8uJcNijvb?usp=drive_link

## 🚀 Features

- **Fully Parametric CAD**:  
  - Designed in Solid Edge 2025 using Extrude, Sweep, Hole, Draft, Pattern & Mirror  
  - Configurable turret rotation ring and elevating gun axle  

- **3D Printing–Ready**:  
  - Optimized STL export for Creality Ender‑3  
  - Recommended settings: PLA @ 0.2 mm layer, 30–50% infill, minimal supports  

- **Mechanical Functionality**:  
  - Smooth, clearance‑tuned turret rotation  
  - Elevating main gun with pinned axle  

- **Documentation & Demo**:  
  - G‑code cleanup script (removes priming “linear lines”)  
  - Interactive QR‑code plate linking to demo video  

---

## 🗂️ Repository Structure
    EdgeXtrude‑PanzerIII/
├── src/
│ ├── CAD/ # Solid Edge part & assembly files
│ ├── STL/ # Exported STL models ready for slicing
│ ├── GCode/ # Cleaned and original .gcode files
├── assets/ # Reference images, renders & photos
├── slicing/ # Cura profiles & slice settings
├── LICENSE.md
└── README.md

Open CAD files in Solid Edge 2025 (or later).
Export STL from src/CAD/ → src/STL/.
Slice using Cura with provided profiles in slicing/.
Print on Ender‑3 (PLA, 0.2 mm, 30–50% infill).
Assemble parts per assembly guide in assets/assembly_diagram.png.

🤝 Contributing
We welcome improvements! Feel free to open issues or PRs for:
CAD optimizations (clearance, support reduction)
Alternative slice profiles or printer configurations
Enhanced documentation or additional feature modules
