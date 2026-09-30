# tTwo-Stage CMOS Op-Amp Custom Layout in 45-nm GPDK with DRC/LVS verification and analog device-matching techniques
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

Status: **PASSED**

The final layout contains no DRC errors.

### LVS

Status: **PASSED**

The extracted layout netlist matches the schematic netlist.
