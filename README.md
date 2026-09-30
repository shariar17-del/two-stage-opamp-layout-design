# Two-Stage CMOS Op-Amp Custom Layout in 45-nm GPDK with DRC/LVS verification and analog device-matching techniques
Custom IC layout design of a two-stage CMOS operational amplifier using Cadence Virtuoso, including analog layout techniques and DRC/LVS verification

## Overview

This project presents the custom IC layout implementation of a two-stage
CMOS operational amplifier using Cadence Virtuoso and the 45-nm GPDK
technology.

The layout was developed following standard analog IC layout practices,
with particular attention to device matching, symmetry, parasitic-aware
layout, and reliable routing.

The completed layout was successfully verified using:

- Design Rule Check (DRC)
- Layout Versus Schematic (LVS)

## Technology and Tools

- Technology: 45-nm GPDK
- Design Environment: Cadence Virtuoso
- Layout: Virtuoso Layout XL
- Verification: DRC and LVS
- Design Type: Two-Stage CMOS Operational Amplifier

## Layout Techniques

The layout follows analog IC layout practices including:

- Device matching
- Symmetrical placement
- Common-centroid techniques where applicable
- Interdigitation where applicable
- Dummy devices
- Symmetrical and controlled routing
- Proper power and ground distribution
- Parasitic-aware layout considerations

## Physical Verification

The completed layout was verified against the 45-nm GPDK design rules and
schematic.

### DRC
<img width="1812" height="880" alt="two stage opamp alternative2_DRC" src="https://github.com/user-attachments/assets/c4957463-af92-44eb-a196-47131be60abd" />


Status: **PASSED**

The final layout contains no DRC errors.

### LVS
<img width="1600" height="748" alt="Screenshot 2026-09-30 at 2 21 36 PM" src="https://github.com/user-attachments/assets/f30efe6e-dae4-4b03-a9ba-0e9c5469aaca" />

Status: **PASSED**

The extracted layout netlist matches the schematic netlist.
