# 🏢 Elevator Control System — PLC Simulation Project

A complete **elevator automation system** developed in **CoDeSys** using **PLC programming (SFC + ST)**.  
The project integrates control logic, real-time simulation, and a **Human–Machine Interface (HMI)** to emulate a fully functional single-cabin elevator with safety and emergency handling.

---

## 🧠 Overview

The system manages:
- Automatic door operation and motion sequencing  
- User call scheduling through a memory-based service policy  
- Fault and emergency routines ensuring passenger safety  
- A synchronized **simulation layer** that reproduces physical behavior

The control logic is structured around **Generalized Actuators (GAs)** , modular blocks that handle motion, door opening/closing, and diagnostics via a common **DO–DONE–FAULT** interface.

---

## ⚙️ Main Features

- **Initialization phase** to align sensors and set the reference position  
- **Dynamic call management** (internal & external panels) with ordered queue logic  
- **Emergency stop handling** with safe deck landing and restart on user reset  
- **HMI visualization** showing live door movement, cabin position, and sensor states  
- **Simulation module** that models timing, speed, and sensor signals in real time  

---

## 🧰 Tools

- **CoDeSys v3.x**  
- **Languages:** Sequential Function Chart (SFC), Structured Text (ST)  
- **HMI Designer:** integrated in CoDeSys  
- **Simulation:** ST-based virtual plant emulation  

---

## 📄 Full Report

The complete documentation, including design logic, simulation, and HMI integration, is available here:

➡️ [**Elevator_managment_project.pdf**](./Elevator_managment_project.pdf)

---

## 🏫 Academic Context

Developed for the course **Control System Technologies**  
**University of Bologna – Department of Electrical, Electronic and Information Engineering (DEI)**  
**Student:** *Abess Ouardi* — *January 2025*

---

## 🏷️ Keywords
`plc` • `codesys` • `automation` • `sfc` • `structured-text` • `hmi` • `simulation` • `industrial-control`
