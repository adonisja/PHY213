# Resistor Color Code Guide

## Band Positions and Roles

| Position | Color Code Role | Description | Formula Contribution |
|----------|----------------|-------------|---------------------|
| Band 1 | 1st Significant Digit (D₁) | Represents the first digit of the resistance value | D₁ × 10 |
| Band 2 | 2nd Significant Digit (D₂) | Represents the second digit of the resistance value | D₂ × 1 |
| Band 3 | Multiplier (M) | The power of ten by which the two digits (D₁, D₂) are multiplied. It determines the magnitude (in ohms) | × 10^M |
| Band 4 | Tolerance (T) | Indicates the percentage deviation (accuracy) of the actual resistance from the marked value | ± T% |

## Color Code Reference Table

| Color | Digit (Bands 1 & 2) | Multiplier (Band 3) | Tolerance (Band 4) |
|--------|---------------------|---------------------|-------------------|
| Black | 0 | × 10⁰ (× 1) | — |
| Brown | 1 | × 10¹ (× 10) | ± 1% |
| Red | 2 | × 10² (× 100) | ± 2% |
| Orange | 3 | × 10³ (× 1k) | — |
| Yellow | 4 | × 10⁴ (× 10k) | — |
| Green | 5 | × 10⁵ (× 100k) | ± 0.5% |
| Blue | 6 | × 10⁶ (× 1M) | ± 0.25% |
| Violet | 7 | × 10⁷ (× 10M) | ± 0.1% |
| Grey | 8 | × 10⁸ (× 100M) | ± 0.05% |
| White | 9 | × 10⁹ (× 1G) | — |
| Gold | — | × 10⁻¹ (× 0.1) | ± 5% |
| Silver | — | × 10⁻² (× 0.01) | ± 10% |

## Calculation Formula

The total resistance **R** (in Ω) is calculated as:

$R = (D_1D_2) \times 10^M \pm T\%$

Where:
- D₁ = First digit (Band 1)
- D₂ = Second digit (Band 2)
- M = Multiplier exponent (Band 3)
- T = Tolerance percentage (Band 4)

## Example

For a resistor with bands: **Red, Violet, Orange, Gold**
- Band 1 (Red) = 2
- Band 2 (Violet) = 7
- Band 3 (Orange) = × 10³
- Band 4 (Gold) = ± 5%

Calculation: R = (27) × 10³ = **27,000 Ω = 27 kΩ ± 5%**

---

# ⚛️ Fundamental Physical Constants

| Constant | Symbol | Value (SI Units) |
|----------|--------|------------------|
| Boltzmann constant | k | $1.3807 × 10^{-23} JK^{-1}$ |
| Gas constant | R | $8.314 J mol⁻¹ K⁻¹$ |
| Elementary charge | e | $1.602 × 10⁻¹⁹ C$ |
| Gravitational constant | G | $6.674 × 10⁻¹¹ N·m²·kg⁻²$ |
| Speed of light | c | $2.998 × 10⁸ m·s⁻¹$
| Avogadro's number | Nₐ | 6.022 × 10²³ mol⁻¹ |
| Planck constant | h | 6.626 × 10⁻³⁴ J·s |
| Speed of light | c | 2.998 × 10⁸ m·s⁻¹ |
| Electron mass | m₁ | 9.109 |
| Permittivity of free space | ε₀ | 8.854 × 10⁻¹² C²·N⁻¹·m⁻²|
| Permeability of free space | μ₀ | 4π × 10⁻⁷ T·m·A⁻¹ |

---

# 🧪 Element Properties (Appendix D & Tables 23-1, 23-2)

| Element | Z | Atomic Mass (g/mol) | Density (g⋅cm⁻³)| | Melting (°C) | Boiling (°C) | Specific Heat (J/g·°C) |
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
| Ohm's Law | Relationship between voltage, current, and resistance | $V = I ⋅ R$ |
| Power | Electrical power dissipation | $P = I ⋅ V = I² ⋅ R = \frac{V²}{R}$ |
| Parallel Resistors | Equivalent resistance in parallel | $\frac{1}{R_{eq}} = \frac{1}{R₁} + \frac{1}{R₂} + …$ |
| Coulomb's Law | Force between two charges | $F = k ⋅ \frac{q₁q₂}{r²}$ |
| Electric Field | Field created by a charge | $E = \frac{F}{q} = k ⋅ \frac{q}{r²}$ |
| Capacitor Discharge | Voltage decay over time | V(t) = $V₀e⁻ᵗ⁄ᴿᶜ$ |

## Thermodynamics

| Formula | Description | Expression |
|---------|-------------|------------|
| Work | Thermodynamic work | W = PΔV |
| First Law | Energy conservation | ΔU = Q − W |
| Ideal Gas Law | Equation of state | PV = nRT |
| Entropy (Isothermal) | Entropy change at constant temperature | ΔS = nR ln(V₂/V₁) |
| Entropy (Isobaric) | Entropy change at constant pressure | ΔS = nCₚ ln(T₂/T₁) |
| Carnot Efficiency | Maximum theoretical efficiency | η = 1 − Tᴄ/Tₕ |

## Kinetic Theory & Statistical Mechanics

| Formula | Description | Expression |
|---------|-------------|------------|
| Kinetic Energy per Molecule | Average translational KE | (3/2)kT |
| RMS Speed | Root-mean-square molecular speed | vᵣₘₛ = √(3kT/m) |

## Electromagnetism

| Formula | Description | Expression |
|---------|-------------|------------|
| Faraday's Law | Induced EMF from changing magnetic flux | E = −dΦᴮ/dt, where Φᴮ = BA cos θ |
