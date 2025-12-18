# 🚀 Physics & Thermodynamics Master Cheat Sheet

## 🛠️ Module 1: Electronics & Resistor Codes

### Resistor Color Code Guide
The total resistance **R** (in Ω) is: $R = (D_1D_2) \times 10^{M} \pm T\%$

| Color | Digit ($D_1, D_2$) | Multiplier ($M$) | Tolerance ($T$) |
| :--- | :---: | :---: | :---: |
| **Black** | 0 | $10^{0}$ | — |
| **Brown** | 1 | $10^{1}$ | ± 1% |
| **Red** | 2 | $10^{2}$ | ± 2% |
| **Orange** | 3 | $10^{3}$ | — |
| **Yellow** | 4 | $10^{4}$ | — |
| **Green** | 5 | $10^{5}$ | ± 0.5% |
| **Blue** | 6 | $10^{6}$ | ± 0.25% |
| **Violet** | 7 | $10^{7}$ | ± 0.1% |
| **Grey** | 8 | $10^{8}$ | ± 0.05% |
| **White** | 9 | $10^{9}$ | — |
| **Gold** | — | $10^{-1}$ | ± 5% |
| **Silver** | — | $10^{-2}$ | ± 10% |

**Logic Aid:** D₁ is the first significant digit, D₂ is the second, and M is the power of ten.

---

## 🌡️ Module 2: Laws of Thermodynamics & Entropy

### The Fundamental Laws
* **0th Law:** Defines Temperature. If A and B are in thermal equilibrium with C, they are in equilibrium with each other.
* **1st Law:** Energy conservation: $\Delta U = Q - W$.
    * **Logic:** $Q > 0$ (Heat added to system); $W > 0$ (Work done **by** system/expansion).
* **2nd Law:** Entropy of an isolated system never decreases ($\Delta S_{total} \geq 0$).
* **3rd Law:** As $T \to 0$ K, $S$ reaches a minimum constant (0 for perfect crystals).

### Thermodynamic Processes ($PV = nRT$)
| Process | Constant | Work Done ($W$) | First Law ($\Delta U$) |
| :--- | :--- | :--- | :--- |
| **Isobaric** | Pressure ($P$) | $P\Delta V$ | $Q - W$ |
| **Isochoric** | Volume ($V$) | $0$ | $\Delta U = Q = nC_v\Delta T$ |
| **Isothermal** | Temp ($T$) | $nRT \ln(V_2/V_1)$ | $\Delta U = 0 \implies Q = W$ |
| **Adiabatic** | Heat ($Q=0$) | $\frac{P_1V_1 - P_2V_2}{\gamma - 1}$ | $\Delta U = -W$ |



### Entropy ($S$)
* **Definition:** $\Delta S = \int \frac{dQ_{rev}}{T}$
* **Isothermal Change:** $\Delta S = nR \ln(V_2/V_1)$
* **Isobaric Change:** $\Delta S = nC_p \ln(T_2/T_1)$
* **Statistical:** $S = k \ln \Omega$ (Boltzmann's Principle).

---

## ⚛️ Module 3: Molecular Properties & Kinetic Theory

### Equipartition Theorem & Internal Energy
Internal Energy ($U$) is distributed among degrees of freedom ($f$): $U = \frac{f}{2}nRT = \frac{f}{2}Nk_BT$
* **Monatomic ($f=3$):** 3 translational (x, y, z directions).
* **Diatomic ($f=5$):** 3 translational + 2 rotational (at room temp).
* **Polyatomic ($f=6$):** 3 translational + 3 rotational.

### Molecular Speeds & Path
* **Average KE per Molecule:** $\frac{3}{2}kT$
* **RMS Speed:** $v_{rms} = \sqrt{\frac{3kT}{m}}$
* **Mean Free Path ($\lambda$):** $\lambda = \frac{V}{\sqrt{2}\pi d^2 N}$
    * *Logic:* Higher pressure or larger molecular diameter ($d$) decreases the distance between collisions.



---

## 📐 Module 4: Mechanics & Electricity Formulas

### Rotational Mechanics
* **Torque:** $\tau = rF\sin\theta = I\alpha$
* **Angular Momentum:** $L = I\omega$
* **Common Moments of Inertia ($I$):**
    * *Disk/Cylinder:* $\frac{1}{2}mr^2$ | *Sphere:* $\frac{2}{5}mr^2$
    * *Rod (Center):* $\frac{1}{12}mL^2$ | *Rod (End):* $\frac{1}{3}mL^2$

### Electricity & Magnetism
* **Ohm's Law:** $V = IR$
* **Coulomb's Law:** $F = k \frac{q_1q_2}{r^2}$
* **Faraday's Law:** $\mathcal{E} = -\frac{d\Phi_B}{dt}$ where $\Phi_B = BA\cos\theta$
* **Power:** $P = IV = I^2R = V^2/R$

---

## 📊 Module 5: Constants & Reference Data

### Physical Constants
| Constant | Symbol | Value (SI Units) |
| :--- | :---: | :--- |
| **Boltzmann** | $k$ | $1.3807 \times 10^{-23}\text{ J/K}$ |
| **Gas Constant** | $R$ | $8.314\text{ J/(mol}\cdot\text{K)}$ |
| **Avogadro** | $N_A$ | $6.022 \times 10^{23}\text{ mol}^{-1}$ |
| **Elem. Charge** | $e$ | $1.602 \times 10^{-19}\text{ C}$ |
| **Speed of Light**| $c$ | $2.998 \times 10^8\text{ m/s}$ |
| **Gravitational** | $G$ | $6.674 \times 10^{-11}\text{ N}\cdot\text{m}^2/\text{kg}^2$ |
| **Std. Pressure** | $P$ | $101,325\text{ Pa} = 1\text{ atm}$ |

### Element Properties
| Element | Z | Mass (g/mol) | Density ($g/cm^3$) | Specific Heat ($J/g\cdot°C$) |
| :--- | :---: | :---: | :---: | :---: |
| **Hydrogen** | 1 | 1.008 | 0.0000837 | 14.3 |
| **Helium** | 2 | 4.0026 | 0.000166 | 5.19 |
| **Carbon** | 6 | 12.011 | 2.25 | 0.709 |
| **Nitrogen** | 7 | 14.007 | 0.001165 | 1.04 |
| **Oxygen** | 8 | 15.999 | 0.001331 | 0.918 |
| **Copper** | 29 | 63.55 | 8.96 | 0.385 |

### Temperature Conversions
* $T_K = T_C + 273.15$
* $T_F = \frac{9}{5}T_C + 32$
* $T_C = \frac{5}{9}(T_F - 32)$