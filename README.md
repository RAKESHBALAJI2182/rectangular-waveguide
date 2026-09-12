# Rectangular Waveguide Design & S-Parameter Analysis

A rectangular waveguide designed and simulated in **CST Studio Suite** operating in the dominant **$\text{TE}_{10}$ mode**.

---

## 📡 Waveguide Geometry & Port Configuration

3D CST perspective showing the rectangular waveguide body and the excitation waveguide port (Port 1).

![Waveguide Geometry](geometry.png)

---

## 📡 3D Waveguide Structure & Port Setup

![Rectangular Waveguide 3D Model](geometry.png)

---

## 📐 Design Specifications & CST Parameters

- **Broad wall ($a$):** $30.083\text{ mm}$
- **Narrow wall ($b$):** $15.5415\text{ mm}$
- **Length ($L$):** $50.0\text{ mm}$
- **Dominant Mode:** $\text{TE}_{10}$
- **Theoretical Cutoff Frequency ($f_c$):**
  $$f_c = \frac{c}{2a} \approx 4.99\text{ GHz}$$

![CST Parameter List](parameter_list.png)

---

## 📊 Simulation & Results (2–6 GHz)

The design was simulated across the $2\text{ GHz} - 6\text{ GHz}$ frequency band in CST Studio Suite to characterize transmission and reflection characteristics.

### 1. $S_{11}$ Return Loss (dB)
Across the sweep, the reflection response exhibits standard mode propagation behavior with cutoff around $4.99\text{ GHz}$.
![S11 Plot](s11_plot.png)

### 2. Voltage Standing Wave Ratio (VSWR)
The VSWR closely mirrors the matched transmission band and rises near the lower cutoff threshold.
![VSWR Plot](vswr_plot.png)

---

## 📁 Repository Contents

| File | Description |
| :--- | :--- |
| `rectangular_waveguide.cst` | CST Studio Suite 3D simulation model file |
| `geometry.png` | 3D structure render showing waveguide ports and body |
| `parameter_list.png` | CST Parameter List screenshot ($a=30.083\text{ mm}$, $b=15.5415\text{ mm}$, $L=50\text{ mm}$) |
| `s11_plot.png` | S11 Magnitude (dB) vs. Frequency response |
| `vswr_plot.png` | Voltage Standing Wave Ratio vs. Frequency |
| `README.md` | Comprehensive design and simulation report |

---
**Tool:** CST Studio Suite  
**Author:** Bollam Rakesh Balaji (NIT Mizoram)