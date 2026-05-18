# PCB Files for the Embedded EIS Prototype

This repository contains the printed circuit board (PCB) design files associated with the embedded electrical impedance spectroscopy (EIS) prototype described in the manuscript:

**Generalized EIS Measurement Method in Li-Ion Batteries**

## Repository contents

### Gerbers

The `Gerbers/` folder contains the manufacturing files required for PCB fabrication, including:

- top and bottom copper layers,
- solder mask layers,
- silkscreen layers,
- solder paste layers,
- board profile,
- V-cut file,
- drill file.

These files can be used by a PCB manufacturer to reproduce the board layout used in the experimental prototype.

### 3D model

The `3D/` folder contains a STEP model of the PCB:

- `PCB_EIS_3D.step`

This file can be used for mechanical inspection, enclosure design, or 3D visualization of the prototype.

## Bill of materials

The complete bill of materials (BOM) is not included in this repository. It can be requested from the corresponding author if required for academic or research purposes.

## Notes

The files are provided to improve reproducibility and to document the hardware implementation of the proposed embedded EIS system. The user is responsible for verifying manufacturing rules, component availability, and assembly constraints before fabrication.
