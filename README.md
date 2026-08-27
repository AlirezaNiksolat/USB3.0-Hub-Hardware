# USB 3.0 Hub – Hardware Design

A standalone **4-Port USB 3.0 Hub hardware design** featuring high-speed USB connectivity, independent port power management, and a dedicated DC power architecture.

The project is designed as a reference for developing USB 3.x hub devices with multiple downstream ports, controlled VBUS distribution, and support for high-speed differential signaling.

---

## Overview

This project implements a multi-port USB hub architecture consisting of:

- **1× USB 3.0 Upstream Port**
- **4× USB 3.0 Downstream Ports**
- USB 3.x SuperSpeed data channels
- USB 2.0 backward-compatible data channels
- Independent power switching for each downstream port
- Per-port enable and fault monitoring
- External DC power input supporting **9 V to 24 V**

The design combines high-speed data connectivity with a dedicated power distribution system to provide a complete standalone USB hub solution.

---

## Key Features

- 4-Port USB 3.0 Hub Architecture
- 1× Upstream USB 3.0 Interface
- 4× Downstream USB 3.0 Interfaces
- SuperSpeed TX/RX Differential Pairs
- USB 2.0 D+ / D− Data Channels
- Independent VBUS Power Control
- Per-Port Enable and Fault Monitoring
- Dedicated USB Power Switches
- External DC Input: **9 V – 24 V**
- On-board DC/DC Power Conversion
- Local Decoupling and Power Filtering
- Status LED Indicators
- Designed with high-speed signal integrity considerations

---
