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

---

## 🌡️ Module 2: Laws of Thermodynamics & Entropy

### The Fundamental Laws
* **0th Law**: Defines temperature; if two systems are in thermal equilibrium with a third, they are in equilibrium with each other.
* **1st Law**: $\Delta U = Q - W$ (Conservation of Energy). 
    * **Logic**: $Q > 0$ (Heat added to system); $W > 0$ (Work done **by** system/expansion).
* **2nd Law**: Total entropy of an isolated system never decreases ($\Delta S_{total} \geq 0$).
* **3rd Law**: As $T \to 0$ K, entropy ($S$) reaches a minimum constant (0 for perfect crystals).

### Thermodynamic Processes ($PV = nRT$)

| Process | Constant | Work Done ($W$) | First Law ($\Delta U$) |
| :--- | :--- | :--- | :--- |
| **Isobaric** | Pressure ($P$) | $W = P\Delta V$ | $\Delta U = Q - W$ |
| **Isochoric** | Volume ($V$) | $W = 0$ | $\Delta U = Q = nC_v\Delta T$ |
| **Isothermal** | Temp ($T$) | $W = nRT \ln(V_2/V_1)$ | $\Delta U = 0 \implies Q = W$ |
| **Adiabatic** | Heat ($Q=0$) | $W = \frac{P_1V_1 - P_2V_2}{\gamma - 1}$ | $\Delta U = -W$ |

### Entropy ($S$)
* **Definition**: $\Delta S = \int \frac{dQ_{rev}}{T}$
* **Isothermal Change**: $\Delta S = nR \ln\left(\frac{V_2}{V_1}\right)$
* **Isobaric Change**: $\Delta S = nC_p \ln\left(\frac{T_2}{T_1}\right)$
* **Statistical**: $S = k \ln \Omega$ (Boltzmann's Principle).

---

## ⚛️ Module 3: Molecular Properties & Kinetic Theory

### Equipartition & Internal Energy
* **Internal Energy ($U$)**: $U = \frac{f}{2}nRT$
    * **Monatomic ($f=3$)**: 3 translational degrees of freedom.
    * **Diatomic ($f=5$)**: 3 translational + 2 rotational.
* **Average KE per Molecule**: $\frac{3}{2}kT$
* **RMS Speed**: $v_{rms} = \sqrt{\frac{3kT}{m}}$
* **Mean Free Path ($\lambda$)**: $\lambda = \frac{V}{\sqrt{2}\pi d^2 N}$
    * **Logic**: Higher density or larger molecular diameter ($d$) decreases the distance between collisions.



---

## 📐 Module 4: Mechanics & Electromagnetism

### Mechanics & Dynamics
* **Momentum**: $p = mv$
* **Kinetic Energy**: $KE = \frac{1}{2}mv^2$
* **Potential Energy**: $PE = mgh$
* **Work-Energy Theorem**: $W = \Delta KE = \frac{1}{2}m(v_f^2 - v_i^2)$
* **Impulse**: $J = \Delta p = F\Delta t$
* **Power**: $P = \frac{W}{t} = Fv$
* **Gravitational Force**: $F_G = G \frac{m_1m_2}{r^2}$

### Rotational Mechanics
* **Torque**: $\tau = r \times F = rF\sin\theta$
* **Angular Momentum**: $L = I\omega$
* **Rotational KE**: $KE_{rot} = \frac{1}{2}I\omega^2$
* **Moments of Inertia ($I$)**: 
    * **Point Mass**: $mr^2$
    * **Disk/Cylinder**: $\frac{1}{2}mr^2$
    * **Solid Sphere**: $\frac{2}{5}mr^2$
    * **Rod (Center)**: $\frac{1}{12}mL^2$ | **Rod (End)**: $\frac{1}{3}mL^2$

### Electricity & Fields
* **Ohm's Law**: $V = IR$
* **Coulomb's Law**: $F_E = k \frac{q_1q_2}{r^2}$
* **Electric Field**: $E = \frac{F}{q} = k \frac{q}{r^2}$
* **Capacitor Discharge**: $V(t) = V_0 e^{-t/(RC)}$
* **Faraday's Law**: $\mathcal{E} = -\frac{d\Phi_B}{dt}$
* **Electrical Power**: $P = IV = I^2R = \frac{V^2}{R}$

---

## 📊 Module 5: Constants & Reference Data

### Physical Constants
| Constant | Symbol | Value (SI Units) |
| :--- | :---: | :--- |
| **Gas Constant** | $R$ | $8.314\ J \cdot mol^{-1} \cdot K^{-1}$ |
| **Boltzmann** | $k$ | $1.3807 \times 10^{-23}\ J/K$ |
| **Avogadro** | $N_A$ | $6.022 \times 10^{23}\ mol^{-1}$ |
| **Elem. Charge** | $e$ | $1.602 \times 10^{-19}\ C$ |
| **Electrostatic**| $k$ | $8.99 \times 10^9\ N \cdot m^2/C^2$ |
| **Gravitational**| $G$ | $6.674 \times 10^{-11}\ N \cdot m^2/kg^2$ |
| **Std. Pressure**| $P$ | $101,325\ Pa = 1\ atm$ |

### Element Properties
| Element | Z | Mass (g/mol) | Density ($g/cm^3$) | Specific Heat ($J/g\cdot°C$) |
| :--- | :---: | :---: | :---: | :---: |
| **Hydrogen** | 1 | 1.008 | 0.0000837 | 14.3 |
| **Helium** | 2 | 4.0026 | 0.000166 | 5.19 |
| **Nitrogen** | 7 | 14.007 | 0.001165 | 1.04 |
| **Oxygen** | 8 | 15.999 | 0.001331 | 0.918 |
| **Copper** | 29 | 63.55 | 8.96 | 0.385 |

### Temperature Conversions
* $T_K = T_C + 273.15$
* $T_F = \frac{9}{5}T_C + 32$
* $T_C = \frac{5}{9}(T_F - 32)$