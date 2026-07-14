# Heavy-Duty Tractor PTO Wood Chipper

[![Engineering](https://img.shields.io/badge/Mechanical-Engineering-blue.svg)](#)
[![CAD](https://img.shields.io/badge/CAD-SolidWorks_2024-red.svg)](#)
[![Rendering](https://img.shields.io/badge/Render-KeyShot-orange.svg)](#)
[![Drafting](https://img.shields.io/badge/Drafting-ASME_Standards-brightgreen.svg)](#)

> **A robust, professional-grade mechanical solution for agricultural waste management and sustainable biomass production.**

## Project Overview
This repository contains the complete mechanical design, 3D CAD modeling, and engineering calculations for a high-capacity tractor PTO-driven wood chipper (PEFNAA Project). Designed to tackle agricultural waste like branches and pruning waste, this machine converts biomass into usable fuel and compost while eliminating the environmental hazards of open burning. 

The design bridges the gap between affordable local manufacturability and heavy-duty commercial performance.

## Core Technical Specifications
* **Prime Mover:** Engineered for the New Holland 4710 4WD tractor (or equivalent 55 HP utility tractors) utilizing a standard 540 RPM PTO.
* **Chipping Capacity:** Capable of processing branch diameters up to 6 inches (150 mm) in a single pass.
* **Cutting Mechanism:** High-inertia disc-type chipper acting as a flywheel to store kinetic energy and ensure uniform chip length.
* **Power Transmission:** V-belt drive system configured for a 3:1 speed step-up, delivering a targeted rotor speed of 1,620 RPM.
* **Feeding System:** Professional-grade hydraulic-powered infeed rollers with automatic jam-reversal for superior operator safety and consistent throughput.

## Engineering & Analytical Scope
To ensure survival under extreme impact and shock loading, the design is backed by rigorous mechanical analysis:
* **Combined Stress Analysis:** Rotor shaft sizing evaluated under simultaneous torsional and bending loads using the maximum shear stress theory (Tresca criterion) and ASME shaft equations.
* **Fatigue & Fracture Mechanics:** Alternating stress amplitudes evaluated via the modified Goodman criterion to guarantee infinite fatigue life, alongside fracture toughness analysis for the D2 tool steel blades and AISI 1045 steel rotor shaft.
* **Vibration Control:** Dynamic rotor balancing to ISO 1940-1 Grade G6.3 and natural frequency calculations to avoid operational resonance.
* **Fastener Safety:** High-strength Grade 8.8 mounting hardware sized with an impact loading safety factor of 3 to 4.

## Modeling & Manufacturing Pipeline
* **3D Assembly & Part Modeling:** fully defined and constrained utilizing **SolidWorks 2024**.
* **Visualization:** Photorealistic machine renders and exploded material views generated in **KeyShot**.
* **Technical Documentation:** Comprehensive manufacturing drawings (front, plan, elevation views) and Bill of Materials (BOM) standardized to strict **ASME drafting standards** for seamless handover to local fabricators.

## Development Status
- [ ] **Phase 1:** Theoretical calculations, cutting force estimation, and commercial benchmarking.
- [ ] **Phase 2:** Detailed 3D CAD modeling and commercial component selection (Bearings, Hydraulics).
- [ ] **Phase 3:** Finite Element Analysis (FEA) validation on the structural frame.
- [ ] **Phase 4:** Finalization of ASME-standard manufacturing drawings.

---
*Developed as part of PEFNAA Engineering Project #003.*
