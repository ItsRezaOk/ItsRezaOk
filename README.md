# Reza Choudhury

Entry-level software engineer working across **full-stack applications, embedded systems, and machine learning optimization**.

I like building things that connect software to the real world. Hardware. Runtime constraints. Signals. Users. Business problems. Systems where the code actually has to hold up.

My strongest work so far has been in Python, C, C++, JavaScript, and systems-level programming. I’ve built full-stack applications, worked with embedded hardware, optimized ML inference on ZedBoard, and helped turn a biomedical signal acquisition prototype into something closer to a real lab-ready system.

## What I’m focused on

- Full-stack software engineering
- Embedded systems and hardware/software integration
- Machine learning inference optimization
- C, C++, Python, JavaScript, and Java
- Performance debugging and systems-level problem solving
- Building useful products, not just technically interesting demos

## Featured work

### ML Inference on Embedded Hardware — ZedBoard

**C · C++ · VHDL · ARM NEON · FPGA · CNN inference · quantization**

This project focused on making CNN inference faster on hardware-constrained embedded systems.

I worked through the full path from software inference to hardware acceleration: C++ inference code, tiling, ARM NEON SIMD kernels, quantized MAC designs, DMA-fed BRAM buffers, fixed-point dequantization, ReLU, max-pooling, and hardware/software tradeoffs.

Specifics:

- Reduced full-model CNN runtime from **3012 ms to 784 ms**
- Achieved a **3.84x full-model speedup**
- Improved individual convolution layers by up to **4.25x**
- Co-developed an INT8 CNN hardware accelerator with **4 parallel MAC processing elements**
- Reached **561 ms end-to-end inference latency**
- Achieved **51.85x speedup** over the prior hardware baseline
- Extended a C++ inference framework to support Vision Transformers
- Added **3 new layers**, modified **1 existing layer**, and implemented **GELU**
- Tested a **642,728-parameter** Vision Transformer baseline
- Reached **39.62% top-1** and **75.99% top-10** validation accuracy
- Compared low-precision MAC designs: **4-bit pipelined MAC at 408.2M MAC/s** versus **8-bit pipelined MAC at 352.4M MAC/s**

The biggest lesson from this project: ML performance is not magic. It comes down to memory layout, numeric representation, hardware limits, layer-by-layer validation, and finding the exact point where the output starts to drift.

### CyVital — Biomedical Signal Acquisition Platform

**Python · pytest · real-time plotting · GUI architecture · biomedical signals**

CyVital is a biomedical signal acquisition platform built for Iowa State labs. The goal was to support real-time visualization and interaction with ECG, EMG, pulse oximetry, and reaction-speed signals using a custom PCB and Python GUI.

Specifics:

- Refactored a **2,000+ line** monolithic Python codebase into modular, sensor-specific components
- Improved plotting-module reliability with **223 pytest cases**
- Reached **80% code coverage**
- Brought graph latency down to **52 ms**
- Designed around a target cost of **$200 per unit**
- Compared against commercial systems around **$10,000**

This project taught me that software architecture matters a lot once a prototype has to become something real people can use.

### Full-Stack Fitness Application

**Android · Java · backend communication · APIs · navigation flows**

Built an Android fitness application that transformed user fitness inputs into algorithm-driven workout outputs.

The project involved mobile UI work, navigation flows, backend communication, API-based data handling, and logic that generated workout recommendations from user goals.

This was one of the projects that pushed me from “I can write code” toward “I can build a complete system with inputs, outputs, state, and user flow.”

### Embedded Hardware Control

**C · hardware documentation · iRobot · low-level I/O**

Worked with autonomous iRobot hardware control by writing embedded C code directly from technical hardware documentation.

This helped me understand how software talks to physical systems: registers, sensors, commands, I/O behavior, and the importance of reading the documentation instead of guessing.

### Low-Level Systems Work

**ARM Assembly · registers · stack · memory · algorithms**

Implemented and explored algorithms at a low level using ARM Assembly.

This gave me a better feel for what higher-level code is actually doing underneath: stack frames, memory movement, register use, branching, and manual control flow.

## Experience

### IT Intern — Connecticut State Colleges and Universities

Summer 2025

Worked on enterprise IT systems for an institution serving over **65,000 students** and **6,700 employees**.

Specific work included:

- Device imaging
- Deployment workflows
- Endpoint troubleshooting
- Windows 11 rollout support
- Hardware swaps
- ServiceNow exposure
- Technical operations meetings

I supported a statewide Windows 11 deployment across **12 Connecticut State campuses** and worked around technical leadership including the CTO, CIO, and President.

This experience helped me understand how software, hardware, people, and operations connect inside a large organization.

### Brand Ambassador — MKTG / Diageo

2025–Present

Outside of engineering, I work live promotional and sales events for major brands including Smirnoff, Crown Royal, Don Julio, Captain Morgan, and Casamigos.

One highlight was setting an event record at a Captain Morgan off-premises event in Ames, selling **100+ bottles** with one teammate.

This work made me better at talking to people, reading the room, explaining value quickly, and staying composed in customer-facing environments. Those skills matter in engineering too.

## Technical skills

**Languages:** Python, C, Java, JavaScript, C++  
**Frameworks / Libraries:** React, PyTorch, TensorFlow, JAX, JUnit, Express.js, Pandas, NumPy  
**Tools:** Android Studio, PostgreSQL, MySQL, Linux, AWS Console, TensorBoard, Postman  
**Systems / Hardware:** ZedBoard, VHDL, ARM NEON, embedded C, hardware-constrained ML inference, iRobot hardware control

## What I’m looking for

I am looking for entry-level software engineering roles where I can grow around strong engineers and work on real technical systems.

The areas I am most interested in are embedded software, full-stack development, machine learning systems, hardware/software integration, performance optimization, and product-focused engineering.

I do not want to just collect technologies on a resume. I want to understand systems deeply, build useful software, and become the kind of engineer who can debug across layers instead of only working at the surface.

## Links

- LinkedIn: [linkedin.com/in/itsrezaok](https://www.linkedin.com/in/itsrezaok)
- GitHub: [github.com/ItsRezaOk](https://github.com/ItsRezaOk)
