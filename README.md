# Bitpong

Analog front-end for ultrasonic piezo transducers

_Author: Peter Volgyesi <peter.volgyesi@vanderbilt.edu>_\
_Copyright (C) 2020 Vanderbilt University_

## Variants and revisions

### Bitpong RevA

_TBD_

- **PCB manufacturer**:
- **Parts**:

#### Issues w/ Bitpong RevA

## Design considerations

### Piezo Transducer

Piezo Disc 7 x 0.2 mm with wire leads, 300 kHz\
Manufacturer part number: SMD07T02R412WL\
<https://www.steminc.com/PZT/en/piezo-7x-02mm-wire-lead-300-khz>

- Piezo Material: SM412
- Resonant frequency: 300 KHz±10 KHz
- Electromechanical coupling coefficient Kp:≥55%
- Resonant impedance Zm: ≤10.0 Ω
- Static capacitance Cs: 3000pF±15%@1kHz

Aluminium Plate: 36"x36"x0.063"\
<https://www.mcmaster.com/89015K52-89015K52>

### Receiver Signal Path

Parts:

- AD8608: Low Noise, CMOS, Rail-to-Rail, Input/Output Precision Quad Op Amp
- TLV2771: Single 2.7-V High Slew Rate Rail-to-Rail Output Operational Amplifier

Application Notes:

- https://www.analog.com/media/en/reference-design-documentation/reference-designs/CN0350.pdf
- https://www.ti.com/lit/an/sloa033a/sloa033a.pdf

### Receiver Signal Path

Parts:

- LT3469: Piezo Microactuator Driver with Boost Regulator

Application Notes:

- https://www.analog.com/media/en/dsp-documentation/evaluation-kit-manuals/dc630A.pdf

### TX/RX Switching

### Connectors:

For input/output analog signals, use BNC connectors (easy instrumentation)
Cable assemblies (RG316, 24"): Digikey 115101-01-24.00
