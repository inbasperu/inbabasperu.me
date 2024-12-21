---
layout: page
title: MIPS 5-Stage Pipeline Processor
description: Advanced pipelined processor implementation on Cyclone V SoC FPGA
img: assets/img/mips_pipeline.jpg
importance: 2
category: hardware
github: https://github.com/the-pinbo/MIPS-5-Stage-Pipeline-Project
---

A comprehensive implementation of a pipelined MIPS processor, following the architecture described in Patterson and Hennessy's "Computer Organization and Design". This project demonstrates advanced concepts in computer architecture and hardware design.

### Key Features

- Complete 5-stage pipeline implementation
- Advanced hazard detection and forwarding
- Static branch prediction
- Custom MUL instruction implementation
- Comprehensive pipeline control system

### Technical Implementation

The processor includes:

- **Pipeline Stages**: IF, ID, EX, MEM, WB with full hazard handling
- **Performance Features**:
  - Data forwarding for reduced stalls
  - Branch prediction for improved throughput
  - Optimized MUL instruction integration
- **Verification**: Extensive testing using Modelsim and real FPGA deployment

### Validation

- Successfully tested with complex programs including:
  - Factorial calculation
  - Fibonacci sequence generation
- Demonstrated correct handling of data hazards
- Verified branch prediction effectiveness
- Confirmed MUL instruction functionality

This project represents a sophisticated implementation of modern processor design principles, combining theoretical computer architecture concepts with practical hardware realization.
