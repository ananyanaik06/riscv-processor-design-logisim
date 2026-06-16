# RISC-V Processor Design in Logisim

## Overview

This project explores the design and implementation of a RISC-V processor using Logisim Evolution. The project progresses from a multi-cycle processor architecture to a pipelined design and finally integrates a dynamic branch prediction subsystem for improved performance.

## Features

### Multi-Cycle RISC-V Processor

* 4-stage multi-cycle processor implementation
* Instruction Fetch (IF)
* Instruction Decode (ID)
* Execute (EX)
* Memory and Writeback support
* Complete control-path implementation

### Pipelined Processor

* Two-stage pipelined architecture
* Overlapping instruction execution
* Hazard handling mechanisms
* Forwarding support for improved throughput

### Dynamic Branch Predictor

* 64-entry Branch History Table (BHT)
* 2-bit saturating counters
* Branch prediction and update logic
* Branch misprediction recovery
* Performance monitoring support

## Repository Structure

```text
.
├── circuits/
│   ├── multicycle_riscv_design.circ
│   ├── two_stage_pipelined_processor.circ
│   └── branch_predictor.circ
│
├── docs/
│   └── Branch_Predictor_report.pdf
│
└── README.md
```

## Requirements

To run and inspect the processor designs, install:

* Logisim Evolution

The circuit files included in this repository use the `.circ` format and can be opened directly using Logisim Evolution.

## Running the Project

1. Install Logisim Evolution.
2. Clone this repository:

```bash
git clone https://github.com/ananyanaik06/riscv-processor-design-logisim.git
```

3. Open any of the `.circ` files from the `circuits/` directory using Logisim Evolution.
4. Simulate and test the processor designs using the built-in simulation tools.

## Files

| File                               | Description                         |
| ---------------------------------- | ----------------------------------- |
| multicycle_riscv_design.circ       | Multi-cycle RISC-V processor        |
| two_stage_pipelined_processor.circ | Pipelined RISC-V processor          |
| branch_predictor.circ              | Dynamic branch prediction subsystem |
| Branch_Predictor_report.pdf        | Design report and analysis          |

## Concepts Implemented

* RISC-V Processor Design
* Multi-Cycle Architecture
* Instruction Pipelining
* Hazard Detection
* Forwarding
* Branch Prediction
* Computer Architecture
* Digital Logic Design

## Future Improvements

* Full 5-stage pipeline implementation
* Cache memory integration
* Advanced branch prediction techniques
* Performance benchmarking framework

## Author

Ananya Naik
