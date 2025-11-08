# 🧊 Scalp Cooling System — Dual‑Patient

[![STM32](https://img.shields.io/badge/MCU-STM32G030C8-03234B?logo=stmicroelectronics)]()
[![C](https://img.shields.io/badge/Firmware-C-blue?logo=c)]()
[![Python](https://img.shields.io/badge/Python-FFD43B?logo=python&logoColor=blue)]()

---

A compact, dual‑patient **scalp cooling controller** that maintains precise scalp temperature during chemotherapy to reduce hair loss.


- [🧊 Scalp Cooling System — Dual‑Patient](#-scalp-cooling-system--dualpatient)
  - [Features](#features)
  - [Hardware](#hardware)
  - [Demo](#demo)


<p align="center"> <img alt="Cooling Prototype" src="assets/cooling_cap_1.png" width="360"> </p>

## Features

- Independent pump control for 2 patients  
- Non‑PID compressor control to maintain a temperature range
- Multi‑level alarms and automatic safety shutdown  
- Real‑time monitoring of temperature, pressure, and flow  
- UART telemetry with live Python plots and CSV data logging

<p align="center"> <img alt="System Diagram" src="assets/cooling_cap_2.png" width="360"> </p>

## Hardware

| Component | Description |
|------------|--------------|
| MCU | STM32G030C8 (ARM Cortex‑M0+) |
| Sensors | Temperature, flow, and pressure |
| Actuators | Compressor, pump, solenoid valves |
| Interface | UART for data streaming |
| Tools | STM32CubeIDE, CubeMX, Python (matplotlib, pandas) |

<p align="center"> <img alt="Cooling Prototype" src="assets/cooling_cap_3.png" width="360"> </p>



## Demo



https://github.com/user-attachments/assets/61aa7489-9105-4390-ae82-b809af393d0d



---

> ⚠️ Firmware code not included due to partner IP agreement.  
> This repository highlights the system design, control strategy, and data handling approach.
