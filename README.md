# 180-nm VCO-Based ADC for Biomedical Signal Acquisition

Final-year ECE project (Sri Eshwar College of Engineering, Coimbatore) — design and
functional simulation of a five-stage current-starved ring VCO paired with a six-bit
reset-counter frequency-to-digital converter, implemented in 180-nm CMOS at 1.5 V,
targeted at the ECG/EMG input range (0.4 V–1.2 V).

Based conceptually on: D. M. Ellaithy, "Voltage-controlled oscillator based
analog-to-digital converter in 130-nm CMOS for biomedical applications," *Journal of
Electrical Systems and Information Technology*, vol. 10, no. 38, 2023.

## Repository structure

- `docs/` — the manuscript (Word format)
- `schematics/` — Cadence Virtuoso schematics: VCO, 6-bit ripple counter, top-level ADC
- `waveforms/` — transient simulation results: VCO output, counter timing, tuning
  curve, and ADC output at each tested input voltage (0.4–1.2 V)

## Status

- [x] VFC (current-starved ring VCO) designed and simulated
- [x] FDC (6-bit reset counter) designed and simulated
- [x] Integrated ADC functionally verified across ECG/EMG input range
- [x] Voltage-to-frequency tuning curve characterized (sigmoidal response)
- [ ] Power and SNDR/ENOB characterization
- [ ] Physical layout, DRC/LVS, post-layout verification, tapeout

## Team

Mounish V, Mohamed Thoufiq S, Muthukumaran S (advisor), Nareshkumar R P, Rithiv Krishna P
— Department of ECE, Sri Eshwar College of Engineering
