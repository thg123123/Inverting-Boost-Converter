# Inverting Boost Converter: Design & Transient Analysis

**Focus:** Power Electronics | PCB Design | Circuit Simulation

This repository documents the end-to-end design of an inverting boost (buck-boost) converter. It includes the theoretical circuit validation using LTspice transient analysis and the physical 2-layer PCB layout translated into KiCad. 

## ⚡ Design & Simulation Highlights
*   **Topology:** Designed an inverting boost converter to provide a negative output voltage from a positive input supply.
*   **Transient Validation:** Simulated switching characteristics, inductor current ripple, and output voltage ripple using LTspice to ensure power delivery meets baseline design constraints before fabrication.
*   **PCB Layout:** Routed the physical board in KiCad, emphasizing optimized trace widths for high-current paths and minimizing the switching node loop area to reduce parasitic inductance and EMI.

## 🗂️ Repository Structure

*   **`/KiCad Design`**: Contains the complete physical board design.
    *   `schematic.kicad_sch`: The physical circuit schematic.
    *   `PCB.kicad_pcb`: The finalized PCB layout[cite: 8].
    *   **/3D Viewer**: Contains visual renders of the populated board[cite: 8].
*   **`/LTspice Simulation`**: Contains the theoretical validation files.
    *   `Schematic.asc`: The LTspice circuit model[cite: 9].
    *   `TransientAnalysis.plt`: Plot settings and results for the converter's transient response and ripple verification[cite: 9].
