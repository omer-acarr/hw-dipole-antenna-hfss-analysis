# HW Dipole Antenna Design & Analysis

This repository contains the design, electromagnetic simulation, and radiation performance analysis of a **Half-Wave (HW) Dipole Antenna**. The project was modeled and validated using **Ansys Electronics Desktop (HFSS) 2025 R2 Student**.

## 🚀 Project Overview
The half-wave dipole is the most fundamental antenna structure in RF engineering. This project demonstrates the transition from theoretical electromagnetic principles to a validated simulation model, focusing on impedance matching and far-field radiation patterns.

### Design Specifications:
- **Resonance Frequency:** 2.2 GHz
- **Antenna Type:** Wire Dipole (λ/2)
- **Environment:** Vacuum / Radiation Boundary Setup
- **Coordinate System:** Infinite Sphere (Phi: 0-360°, Theta: 0-360°)

---

## 🛠 Design & Setup
The antenna consists of two conductive arms, each approximately λ/4 in length, fed from the center. A radiation boundary (Air Box) was defined to encapsulate the antenna and simulate open-space conditions.

### Far-Field Setup:
To capture the complete 3D radiation pattern, an **Infinite Sphere** was configured with a **5-degree step size** for both Phi and Theta angles.



---

## 📊 Simulation Results

### 1. S-Parameters (Return Loss)
The frequency sweep shows a sharp and deep resonance:
- **S11 (Return Loss):** Measured at **-33.8 dB** at exactly **2.21 GHz**.
- **Impedance Matching:** The deep null indicates an excellent match to the 50 Ohm feed line, ensuring maximum power transfer.



### 2. Radiation Pattern & Gain
The 3D Far-Field results confirm the classical dipole characteristics:
- **Radiation Pattern:** A perfect "doughnut" (toroidal) shape was verified.
- **Peak Directivity/Gain:** **2.19 dB**, which aligns perfectly with the theoretical value of 2.15 dBi for a lossless half-wave dipole.



---

## 🖥 Computational Information
- **Solver:** Driven Terminal
- **Mesh:** Adaptive meshing was applied to refine the solution near the antenna elements for high-fidelity far-field results.

