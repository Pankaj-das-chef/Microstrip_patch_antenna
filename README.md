# PXE INTERNSHIP
# Simulation and Design in RF Systems, RADAR Technology, and Antenna Arrays

This project presents a comprehensive overview of simulation and design work across multiple domains including RF systems, RADAR technology and microstrip patch antennas especially oriented towards defense use-cases.

---

## Overview

The work is divided into three major parts:
- **RADAR System Simulation**
- **Antenna Design and Array Optimization**
- **Radar Cross Section (RCS) Modelling**

---

## 📡 1. RADAR System Modelling and Simulation

This section involves theoretical analysis and MATLAB simulation of the **Radar Range Equation**:


![image](https://github.com/user-attachments/assets/ee14280e-aa63-4e2b-a354-e2ee7f9a9f19)


**Key Studies:**
- Radar Cross Section (RCS) effect on detection range
- Power attenuation over distance

**Tools Used:** MATLAB

**Outputs:**
- Plots: `RCS vs Range`, `Power vs Distance`
- Interpretation of system-level radar performance and limitations

---

## 🛰️ 2. Microstrip Patch Antenna Design

Designed a patch antenna resonating at **3.2 GHz (S-band)** using **CST Microwave Studio**.

**Design Stages:**
- Single Patch
- 1×2 Array
- 2×2 Array
- Final 4×8 High-Gain Array

![Screenshot 2025-07-01 061226](https://github.com/user-attachments/assets/2e7384af-d1d4-4908-aeb1-5975a81dfbd7)

**Simulated Parameters:**
- Return Loss (S11)
- Bandwidth
- Gain

Increasing array size led to higher directional gain — ideal for long-range RADAR applications.

---

## 3. Radar Cross Section (RCS) Evaluation

**Geometries Simulated:**
- Plate
- Sphere
- Shell

**Software Used:**
- CST Microwave Studio (3D EM simulation)
- MATLAB (Analytical RCS estimation)

**Outcome:**
> Results showed strong correlation between CST and MATLAB calculations, validating the simulation workflow and accuracy.

---

## Tools and Technologies

- `MATLAB` – RADAR simulation, RCS computation
- `CST Microwave Studio` – Antenna and RCS 3D design

