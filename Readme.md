# Power Meter Thesis — Project Overview

This repository contains the design, firmware, and dashboard for a low-cost embedded Power Meter developed as a thesis project.

Summary
- Objective: design and implement a compact, accurate power-meter device with real-time web monitoring and data logging.
- Scope: PCB designs (Altium), STM32 firmware (ADC sampling, signal processing, Modbus RS-485), and a Node.js dashboard for visualization.

Quick links
- Video demo: see [Video/Readme.md](Video/Readme.md)
- Dashboard: see [Dashboard](Dashboard)
- Firmware & source: see [Code](Code)
- Schematics & PCBs: see [Altium](Altium)

Getting started
- Build firmware: follow the CMake/Toolchain files in `Code/` and use an ARM toolchain (GCC `arm-none-eabi`).
- Run dashboard: in `Dashboard/` run `npm install` then `node server.js` to start the web UI.

Contributions & contact
- This repo contains thesis artifacts and reference implementations. Open an issue or contact the author for questions or collaboration.
