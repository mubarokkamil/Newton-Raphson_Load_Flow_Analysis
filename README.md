<p align="center">
  <img src="banner2.jpg" width="100%">
</p>

# Power Systems Analysis: Newton-Raphson Load Flow

![Status](https://img.shields.io/badge/Status-Complete-success)
![Subject](https://img.shields.io/badge/Subject-Power_Systems-blue)
![Level](https://img.shields.io/badge/Level-Undergraduate-orange)

This repository provides a comprehensive, step-by-step mathematical guide to solving **Newton-Raphson Load Flow** problems. Designed for electrical engineering students, it bridges the gap between theoretical textbook formulas and practical, manual computation.

### 📄 Access the Documentation
* 👉 **[Download the Full PDF Guide](./Newton_Raphson_Guide.pdf)** *(Recommended)*
* 💻 **[View LaTeX Source Code](./main.tex)** 

---

## 📖 Overview

Unlike standard textbooks that often omit intermediate calculations, this document provides an explicit, line-by-line manual execution of a **3-Bus Power System** (containing Slack, PQ, and PV buses). 

**Key Topics Covered:**
* **Theoretical Formulation:** General power flow equations, power mismatches, and Jacobian matrix structure.
* **Iteration 1 (Flat Start):** Mathematical simplification of trigonometric derivatives using conductance ($G$) and susceptance ($B$) components.
* **Iteration 2 (Full Execution):** Handling non-zero angles, recalculating partial derivatives, and updating state variables.
* **The Quadrant Trap:** A critical methodology for avoiding common calculator errors during rectangular-to-polar $Y_{bus}$ conversions.

---

## 🧮 Mathematical Formulation

The core of this guide explicitly maps Power Mismatches ($\Delta P, \Delta Q$) to Voltage Corrections ($\Delta \delta, \Delta |V|$) via the Jacobian Matrix. For our specific 3-bus system, this is formulated as:

$$
\begin{bmatrix} \Delta P_2 \\ \Delta P_3 \\ \Delta Q_2 \end{bmatrix} = 
\begin{bmatrix} 
\frac{\partial P_2}{\partial \delta_2} & \frac{\partial P_2}{\partial \delta_3} & \frac{\partial P_2}{\partial |V_2|} \\[0.3cm]
\frac{\partial P_3}{\partial \delta_2} & \frac{\partial P_3}{\partial \delta_3} & \frac{\partial P_3}{\partial |V_2|} \\[0.3cm]
\frac{\partial Q_2}{\partial \delta_2} & \frac{\partial Q_2}{\partial \delta_3} & \frac{\partial Q_2}{\partial |V_2|} 
\end{bmatrix}
\begin{bmatrix} \Delta \delta_2 \\ \Delta \delta_3 \\ \Delta |V_2| \end{bmatrix}
$$

*(Please refer to the PDF for the full numerical evaluation, partial derivative expansions, and matrix inversion).*

---
*Authored by **Mubarok Hossen Kamil**.*
