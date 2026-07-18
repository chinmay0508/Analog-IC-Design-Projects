# CMOS Differential Amplifier

Single-stage CMOS differential amplifier with a PMOS current mirror active load designed and verified in **Cadence Virtuoso** using the **GPDK180 (180 nm)** CMOS process.

---

## Design Specifications

- **Technology:** GPDK180 (180 nm)
- **Supply Voltage:** 1.8 V
- **Voltage Gain:** ≥ 100 V/V (40 dB)
- **Gain Bandwidth:** ≥ 5 MHz
- **Load Capacitance:** 10 pF
- **Slew Rate:** ≥ 5 V/μs
- **ICMR:** 0.8 V – 1.6 V
- **Power Dissipation:** ≤ 0.3 mW

---

## Design Flow

1. Hand calculations
2. Transistor sizing
3. Cadence Virtuoso implementation
4. DC operating point verification
5. AC analysis
6. Transient analysis
7. Performance verification

---

## Repository Contents

- `images/` – Schematics and simulation results
- `hand_calculations.pdf` – Design calculations
- `design_report.pdf` – Complete design report

---

## Tools

- Cadence Virtuoso
- GPDK180 (180 nm)
