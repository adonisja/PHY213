# Resistor Color Code Guide

## Band Positions and Roles

| Position | Color Code Role | Description | Formula Contribution |
|----------|----------------|-------------|---------------------|
| Band 1 | 1st Significant Digit (D₁) | Represents the first digit of the resistance value | D₁ × 10 |
| Band 2 | 2nd Significant Digit (D₂) | Represents the second digit of the resistance value | D₂ × 1 |
| Band 3 | Multiplier (M) | The power of ten by which the two digits (D₁, D₂) are multiplied. It determines the magnitude (in ohms) | × 10^{M} |
| Band 4 | Tolerance (T) | Indicates the percentage deviation (accuracy) of the actual resistance from the marked value | ± T% |

## Color Code Reference Table

| Color | Digit (Bands 1 & 2) | Multiplier (Band 3) | Tolerance (Band 4) |
|--------|---------------------|---------------------|-------------------|
| Black | 0 | × 10^{0} (× 1) | — |
| Brown | 1 | × 10^{1} (× 10) | ± 1% |
| Red | 2 | × 10^{2} (× 100) | ± 2% |
| Orange | 3 | × 10^{3} (× 1k) | — |
| Yellow | 4 | × 10^{4} (× 10k) | — |
| Green | 5 | × 10^{5} (× 100k) | ± 0.5% |
| Blue | 6 | × 10^{6} (× 1M) | ± 0.25% |
| Violet | 7 | × 10^{7} (× 10M) | ± 0.1% |
| Grey | 8 | × 10^{8} (× 100M) | ± 0.05% |
| White | 9 | × 10^{9} (× 1G) | — |
| Gold | — | × 10^{-1} (× 0.1) | ± 5% |
| Silver | — | × 10^{-2} (× 0.01) | ± 10% |

## Calculation Formula

The total resistance **R** (in Ω) is calculated as:

$$R = (D_1D_2) \times 10^{M} \pm T\%$$

Where:
- D₁ = First digit (Band 1)
- D₂ = Second digit (Band 2)
- M = Multiplier exponent (Band 3)
- T = Tolerance percentage (Band 4)

## Example

For a resistor with bands: **Red, Violet, Orange, Gold**
- Band 1 (Red) = 2
- Band 2 (Violet) = 7
- Band 3 (Orange) = × 10^{3}
- Band 4 (Gold) = ± 5%

Calculation: R = (27) × 10^{3} = **27,000 Ω = 27 kΩ ± 5%**

---

# ⚛️ Fundamental Physical Constants

| Constant | Symbol | Value (SI Units) |
|----------|--------|------------------|
| Boltzmann constant | k | $1.3807 \times 10^{-23}\ J·K^{-1}$ |
| Gas constant | R | $8.314\ J·mol^{-1}·K^{-1}$ |
| Elementary charge | e | $1.602 \times 10^{-19}\ C$ |
| Gravitational constant | G | $6.674 \times 10^{-11}\ N·m^{2}·kg^{-2}$ |
| Avogadro's number | N_A | $6.022 \times 10^{23}\ mol^{-1}$ |
| Planck constant | h | $6.626 \times 10^{-34}\ J·s$ |
| Speed of light | c | $2.998 \times 10^{8}\ m·s^{-1}$ |
| Electron mass | m_e | $9.109 \times 10^{-31}$ kg |
| Permittivity of free space | ε₀ | $8.854 \times 10^{-12}\ C^{2}·N^{-1}·m^{-2}$ |
| Permeability of free space | μ₀ | $4\pi \times 10^{-7}\ T·m·A^{-1}$ |

---

# 🧪 Element Properties (Appendix D & Tables 23-1, 23-2)

| Element | Z | Atomic Mass (g/mol) | Density (g·cm^{-3}) | Melting (°C) | Boiling (°C) | Specific Heat (J·g^{-1}·°C^{-1}) |
|---------|---|---------------------|-----------------|--------------|--------------|------------------------|
| Hydrogen | 1 | 1.008 | 0.0000837 | −259.3 | −252.9 | 14.3 |
| Helium | 2 | 4.0026 | 0.000166 | −272.2 | −268.9 | 5.19 |
| Carbon | 6 | 12.011 | 2.25 | 3550 | — | 0.709 |
| Nitrogen | 7 | 14.007 | 0.001165 | −210.0 | −195.8 | 1.04 |
| Oxygen | 8 | 15.999 | 0.001331 | −218.8 | −183.0 | 0.918 |
| Neon | 10 | 20.180 | 0.000839 | −248.6 | −246.0 | 1.03 |
| Copper | 29 | 63.55 | 8.96 | 1084.6 | 2562 | 0.385 |
| Silver | 47 | 107.87 | 10.49 | 961.8 | 2162 | 0.235 |
| Gold | 79 | 196.97 | 19.32 | 1064.2 | 2856 | 0.129 |

---

# 📐 Commonly Used Physics Formulas

## Electricity & Circuits

| Formula | Description | Expression |
|---------|-------------|------------|
| Ohm's Law | Relationship between voltage, current, and resistance | $V = I \cdot R$ |
| Power | Electrical power dissipation | $P = I \cdot V = I^{2} \cdot R = \frac{V^{2}}{R}$ |
| Parallel Resistors | Equivalent resistance in parallel | $\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \ldots$ |
| Coulomb's Law | Force between two charges | $F = k \cdot \frac{q_1 q_2}{r^{2}}$ |
| Electric Field | Field created by a charge | $E = \frac{F}{q} = k \cdot \frac{q}{r^{2}}$ |
| Capacitor Discharge | Voltage decay over time | $V(t) = V_0 e^{-t/(RC)}$ |

## Thermodynamics

| Formula | Description | Expression |
|---------|-------------|------------|
| Work | Thermodynamic work | $W = P\Delta V$ |
| First Law | Energy conservation | $\Delta U = Q - W$ |
| Ideal Gas Law | Equation of state | $PV = nRT$ |
| Entropy (Isothermal) | Entropy change at constant temperature | $\Delta S = nR \ln\left(\frac{V_2}{V_1}\right)$ |
| Entropy (Isobaric) | Entropy change at constant pressure | $\Delta S = nC_p \ln\left(\frac{T_2}{T_1}\right)$ |
| Carnot Efficiency | Maximum theoretical efficiency | $\eta = 1 - \frac{T_C}{T_H}$ |

## Kinetic Theory & Statistical Mechanics

| Formula | Description | Expression |
|---------|-------------|------------|
| Kinetic Energy per Molecule | Average translational KE | $\frac{3}{2}kT$ |
| RMS Speed | Root-mean-square molecular speed | $v_{rms} = \sqrt{\frac{3kT}{m}}$ |

## Electromagnetism

| Formula | Description | Expression |
|---------|-------------|------------|
| Faraday's Law | Induced EMF from changing magnetic flux | $\mathcal{E} = -\frac{d\Phi_B}{dt}$, where $\Phi_B = BA \cos\theta$ |
