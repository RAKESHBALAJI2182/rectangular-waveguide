# Rectangular Waveguide Design & S-Parameter Analysis

A rectangular waveguide designed and simulated in **CST Studio Suite** operating in the dominant **$\text{TE}_{10}$ mode**.

---

## 📡 Waveguide 3D Geometry & Port Configuration

Below is the 3D model view from CST Studio Suite showing the rectangular waveguide body and the port excitation faces (Port 1 and Port 2):

<p align="center">
  <img src="https://raw.githubusercontent.com/RAKESHBALAJI2182/rectangular-waveguide/main/geometry.png" alt="Rectangular Waveguide Geometry" width="650"/>
</p>

---

## 📐 Design Specifications & CST Parameters

- **Broad wall ($a$):** $30.083\text{ mm}$
- **Narrow wall ($b$):** $15.5415\text{ mm}$
- **Length ($L$):** $50.0\text{ mm}$
- **Dominant Mode:** $\text{TE}_{10}$
- **Theoretical Cutoff Frequency ($f_c$):**
  $$f_c = \frac{c}{2a} \approx 4.99\text{ GHz}$$

<p align="center">
  <img src="https://raw.githubusercontent.com/RAKESHBALAJI2182/rectangular-waveguide/main/parameter_list.png" alt="CST Parameter List" width="450"/>
</p>

---

## 📊 Simulation & Results (2–6 GHz)

The structure was simulated across the $2\text{ GHz} - 6\text{ GHz}$ band to characterize mode propagation and matching behavior relative to the cutoff frequency.

### 1. $S_{11}$ Return Loss (dB)
Across the sweep, the reflection response exhibits mode propagation behavior with cutoff around $4.99\text{ GHz}$.

<p align="center">
  <img src="https://raw.githubusercontent.com/RAKESHBALAJI2182/rectangular-waveguide/main/s11_plot.png" alt="S11 Plot" width="700"/>
</p>

### 2. Voltage Standing Wave Ratio (VSWR)
The VSWR closely mirrors the matched transmission band and rises near the lower cutoff threshold.

<p align="center">
  <img src="https://raw.githubusercontent.com/RAKESHBALAJI2182/rectangular-waveguide/main/vswr_plot.png" alt="VSWR Plot" width="700"/>
</p>

---

## 📁 Repository Contents

| File | Description |
| :--- | :--- |
| `rectangular_waveguide.cst` | CST Studio Suite 3D simulation model file |
| `geometry.png` | 3D structure render showing waveguide body and port excitations |
| `parameter_list.png` | CST Parameter List screenshot ($a=30.083\text{ mm}$, $b=15.5415\text{ mm}$, $L=50\text{ mm}$) |
| `s11_plot.png` | S11 Magnitude (dB) vs. Frequency response |
| `vswr_plot.png` | Voltage Standing Wave Ratio vs. Frequency |
| `README.md` | Comprehensive design and simulation report |

---
**Tool:** CST Studio Suite  
**Author:** Bollam Rakesh Balaji (NIT Mizoram)