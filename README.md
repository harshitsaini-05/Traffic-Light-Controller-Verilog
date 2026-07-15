# FPGA Based Traffic Light Controller with Emergency Priority

## Overview

This project implements a Traffic Light Controller using Verilog HDL. The controller is designed using a Finite State Machine (FSM) and includes an Emergency Vehicle Priority feature. The design was successfully simulated using EDA Playground with Icarus Verilog.

---

## Features

- Finite State Machine (FSM) Based Design
- North-South Traffic Control
- East-West Traffic Control
- Emergency Vehicle Priority
- Reset Functionality
- Synthesizable Verilog HDL Code
- Simulation using EDA Playground

---

## Inputs

| Signal | Description |
|--------|-------------|
| clk | System Clock |
| reset | Active High Reset |
| emergency | Emergency Vehicle Signal |

---

## Outputs

| Signal | Description |
|--------|-------------|
| NS | North-South Traffic Light |
| EW | East-West Traffic Light |

### Light Encoding

| Binary | Light |
|--------|-------|
| 00 | RED |
| 01 | YELLOW |
| 10 | GREEN |

---

## Files

- traffic_light_controller.v
- traffic_light_tb.v
- waveform.png

---

## Simulation Tool

- Verilog HDL
- EDA Playground
- Icarus Verilog
- EPWave

---

## Simulation Waveform 

![Waveform](Screenshot%202026-07-15%20082600.png)

---

## Author

**Harshit Saini**

Internship Project - Codec Technologies
