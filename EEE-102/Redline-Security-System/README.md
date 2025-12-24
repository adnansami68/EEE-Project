# 🚨 RedLine Security System

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Course](https://img.shields.io/badge/Course-EEE%20102-blue)
![University](https://img.shields.io/badge/University-BUBT-green)

> **A Low-Cost, Laser-Based Intrusion Detection System**

The **RedLine Security System** is an electronic security prototype designed to protect restricted areas using laser technology. It creates an invisible boundary using a laser beam and a photosensor (LDR). When this beam is interrupted by an intruder, the system immediately triggers an alarm to alert the user.

---

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Components Required](#-components-required)
- [Circuit Diagram](#-circuit-diagram)
- [Working Principle](#-working-principle)
- [Applications](#-applications)
- [Contributors](#-contributors)

---

## 🧐 Project Overview
Unauthorized access is a major concern for homes, offices, and sensitive industrial zones. The **RedLine Security System** provides a simple yet effective solution.

* **Goal:** To design a compact, energy-efficient security system.
* **Method:** Utilizes light-dependent switching (Laser & LDR).
* **Outcome:** Instant audible alert upon intrusion detection.

---

## 🌟 Key Features
* ⚡ **Instant Response:** Zero-delay alarm trigger.
* 🔋 **Low Power Consumption:** Operates efficiently on a standard 9V battery.
* 💰 **Cost-Effective:** Built with affordable and readily available components.
* 🛠️ **Easy Installation:** Can be deployed in doorways, windows, or cabinets.

---

## 🛠 Components Required

| Component | Quantity | Specification |
|-----------|:--------:|---------------|
| **Laser Module** | 1 | Standard Red Laser (5V/3V) |
| **Sensor** | 1 | LDR (Light Dependent Resistor) or Photodiode |
| **Transistor** | 1 | BC 547 (NPN) |
| **Resistor** | 1 | 10k Ohm |
| **Power Source** | 1 | 9V Battery with Clip |
| **Output** | 1 | Buzzer & LED Indicator |
| **Misc** | - | PCB Board, Switch, Connecting Wires |

---

## 🔌 Circuit Diagram

*(Replace the link below with your actual image path)*

![Circuit Diagram](./circuit_diagram.png)

> **Note:** The circuit aligns the laser source directly with the LDR. The 10kΩ resistor acts as a base resistor to control the transistor's switching state.

---

## ⚙️ Working Principle

The system operates on the physics of **Photo-Conductivity**:

1.  **Normal State (Secure):** The laser beam continuously hits the LDR. The LDR's resistance drops, allowing current to flow to the ground, keeping the Transistor (BC547) in the **OFF** state.
2.  **Intrusion State (Alert):** When an object/person blocks the laser beam, the LDR falls into shadow. Its resistance increases properly.
3.  **Trigger:** This change allows voltage to flow to the Transistor's base, turning it **ON**.
4.  **Alarm:** The conducting transistor completes the circuit for the Buzzer and LED, triggering the alarm.

---

## 🏠 Applications
This project is suitable for:
* ✅ **Home Security:** Door and Window protection.
* ✅ **Restricted Areas:** Server rooms, chemical labs.
* ✅ **Safety:** Perimeter fencing for hazardous machinery.
* ✅ **Asset Protection:** Museum exhibits or vault safety.

---

## 👥 Contributors

This project was developed as part of the **EEE 102** coursework at the **Bangladesh University of Business and Technology (BUBT)**.

**Team Members:**
* **Md. Adnan Sami** (ID: 20255103068)
* **Md. Yousuf Ali** (ID: 20255103059)
* **Siam Khan** (ID: 20255103069)
* **Tanber Hasan Rimon** (ID: 20255103073)
* **Tanvir Ahmed** (ID: 2025510381)
* **Fahim Islam** (ID: 20255103072)

---
*Created with ❤️ by the RedLine Security Team*
