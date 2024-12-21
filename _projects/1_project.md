---
layout: page
title: PDM to Ethernet Frame Generator
description: FPGA-based audio processing and network transmission system
img: assets/img/pdm_ethernet.jpg
importance: 1
category: hardware
github: https://github.com/the-pinbo/PDM-to-Ethernet-Packet-Generator
---

An FPGA implementation that bridges digital audio processing with high-speed network communication. This project demonstrates real-time signal processing and network protocol implementation in hardware.

### Key Features

- Implemented 100 Mbps Ethernet PHY controller with RMII interface
- Real-time PDM audio processing from MEMS microphone
- 256-point FFT implementation for spectral analysis
- Hardware-optimized FIFO and clock domain crossing solutions

### Technical Details

The system architecture consists of three main components:

- **Audio Processing Pipeline**: PDM decimation, resolution enhancement, and FFT computation
- **Network Interface**: Custom Ethernet frame generation and RMII protocol implementation
- **System Integration**: Clock domain management and FIFO-based data synchronization

### Results

The system successfully achieves:

- Real-time audio capture and processing
- Reliable 100 Mbps data transmission
- Live spectrum visualization
- Efficient hardware resource utilization

This project showcases the integration of digital signal processing with networking protocols in an FPGA environment, addressing real-world challenges in embedded systems design.
