# CFET TCAD Modelling: Monolithic and Sequential

## Overview
This repository contains TCAD simulation files for the modelling and electrical characterization of monolithic and sequential Complementary Field-Effect Transistors (CFETs) using Synopsys Sentaurus.

## Repository Structure

```text
CFET-TCAD/
├── Monolithic_CFET/
│   ├── SProcess/
│   ├── SDevice/
│   └── Inspect/
│
├── Sequential_CFET/
│   ├── SProcess/
│   ├── SDevice/
│   └── Inspect/
│
└── README.md
```

## Simulation Workflow

- **SProcess:** Process-related structure generation.
- **SDevice:** Electrical device simulations.
- **Inspect:** Extraction and analysis of electrical characteristics.

## Characterization

The device performance is evaluated using:
- Drain current vs. gate voltage (\(I_D-V_G\))
- Threshold voltage (\(V_T\))
- Subthreshold swing (SS)
- ON/OFF current and ON/OFF ratio
- Carrier density and mobility

## Software
- Synopsys Sentaurus Process
- Synopsys Sentaurus Device
- Synopsys Sentaurus Visual / Inspect
