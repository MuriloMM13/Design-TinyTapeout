![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg)

# SRAM Full-Custom Design – Tiny Tapeout Project

## Overview

This repository contains the design and physical layout of a **full-custom SRAM cell**, developed using the **Tiny Tapeout** flow and fully **open-source tools**.  
The project demonstrates the complete process — from schematic design to GDSII generation — enabling fabrication in **CMOS 130 nm technology (Sky130)**.

## Objectives

- Design and optimize a **full-custom SRAM** cell for educational and research purposes.  
- Explore **analog and digital design principles** within a real fabrication workflow.  
- Gain practical experience in the **Tiny Tapeout** open-source ASIC design flow.

## Tools & Technologies

- **Technology:** SkyWater **Sky130** (CMOS 130 nm)
- **Tools used:** Magic, KLayout, Ngspice, OpenLane, and other Tiny Tapeout utilities
- **Languages:** Verilog / SPICE
- **Layout files:** GDS, LEF, and MAG views available in corresponding folders

## Repository Structure

.
├── docs/ → Technical documentation and design notes
├── gds/ → Final GDSII layout files
├── lef/ → Standard cell abstract views
├── mag/ → Magic layout files
├── src/ → Source code and SPICE netlists
├── test/ → Simulation scripts and validation data
└── README.md → Project overview


## Results

- Functional **Inverter cell** integrated within the Tiny Tapeout framework  
- Verified with **electrical simulations** (read/write operations and stability tests)  
- Compatible for manufacturing through the **Tiny Tapeout shuttle**

## Context

This work was part of a training project in **microelectronics and circuit design**, focused on developing **full-custom logic cells** using open-source ASIC design flows.  
It reflects hands-on experience in **layout conception, simulation, and verification** — essential steps in a professional R&D environment.

## References

- [Tiny Tapeout documentation](https://tinytapeout.com/)
- [SkyWater SKY130 PDK](https://github.com/google/skywater-pdk)
- [Magic VLSI](http://opencircuitdesign.com/magic/)
- [KLayout](https://www.klayout.de/)
