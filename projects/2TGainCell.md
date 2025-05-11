---
layout: project
type: project
image: img/tinyML/ICDesign.jpg
title: "Design and Implementation of a 2T Gain Cell for an 8x8 Dynamic Memory Array"
date: "Jan. 2025 – May 2025"
published: true
labels:
  - Mixed-Signal
  - Integrated Circuit Design
  - Embedded DRAM
summary: "Designed and verified a compact 2-transistor (2T) gain cell in 180nm CMOS for low-power embedded memory applications. The project includes schematic design, simulation, and layout for integration into an 8×8 dynamic memory array, with a focus on minimizing leakage and area. Work was completed using Cadence tools as part of a senior capstone project."
---
## Objective
The goal of this project was to design, simulate, and lay out a compact 2-transistor (2T) gain cell using TSMC’s 180nm CMOS technology. The gain cell was intended for integration into an 8×8 dynamic memory array, with a focus on minimizing leakage current and cell area while ensuring stable read and write functionality.

## Motivation
As demand grows for low-power and high-density memory in embedded systems, traditional architectures like 6T SRAM and 1T-1C eDRAM present challenges in area and leakage control. The 2T gain cell offers an alternative that eliminates the need for a discrete capacitor and enables area-efficient design using standard CMOS processes. This project aimed to explore the feasibility of the 2T cell for system-on-chip (SoC) integration.

## Design and Methodology

- **Schematic Design**: Implemented in Cadence Virtuoso Studio. Transistor sizing was optimized to balance read stability, write access, and data retention.
- **Simulation**: Performed using ADE Explorer. Transient simulations validated the read/write operation, signal inversion, and storage node behavior.
- **Layout Design**: Created in Virtuoso Layout Suite XL. Routing used Metal 3 and 4 layers. DRC and LVS checks confirmed physical and functional correctness.
- **Array Integration**: A 4×4 memory test array was developed to evaluate shared wordline/bitline configuration and array-level read functionality.

## Results

- Achieved leakage currents in the range of hundreds of picoamps, consistent with literature.
- Verified functional read/write operation and signal inversion via transient simulation.
- Layout passed all DRC and LVS checks; cell area measured 4.825 µm × 3.091 µm.
- Simulation results from the 4×4 array testbench confirmed correct array behavior.

## Future Work

- Complete physical layout and verification of the full 8×8 memory array.
- Incorporate sense amplifiers and decoding logic for robust array operation.
- Prepare for chip tapeout and post-fabrication testing.

## Tools and Technologies

- **Design Tools**: Cadence Virtuoso, ADE Explorer, Layout Suite XL
- **Technology**: TSMC 180nm CMOS
- **Project Type**: Senior Capstone (EE 496), University of Hawai‘i at Mānoa


Faculty Advisor: Prof. Boris Murmann  
Department of Electrical Engineering, University of Hawai‘i at Mānoa

[Project Paper](https://drive.google.com/file/d/1gkHhqiikhmhTg3mCifFzDiNkLjQ-RD0x/view?usp=share_link)   

[Presented Poster](https://drive.google.com/file/d/1XZDddKPwc98K-UlU4_XUWc0KLH-DGzlc/view?usp=sharing)   

