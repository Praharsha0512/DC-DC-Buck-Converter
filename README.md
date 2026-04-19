#  Buck Converter (B2-G5)

This project focuses on the design and implementation of a **Buck (Step-Down) DC-DC Converter** using the **TL494 PWM controller** and **TC4428A gate driver**. The aim is to obtain a regulated output voltage and verify the operation in both **Continuous Conduction Mode (CCM)** and **Discontinuous Conduction Mode (DCM)**.

---

##  Specifications

- **Input Voltage:** 20 V  
- **Output Voltage:** 7.5 V  
- **Switching Frequency:** 20 kHz  
- **Output Current:** 1 A  

---

##  Overview

The following steps were carried out:

### 1. MATLAB Simulink Simulation
- Designed the buck converter in **MATLAB/Simulink**
- Verified:
  - Inductor current waveform
  - Switch voltage waveform in Continuous Conduction Mode(CCM)
- Reduced switching frequency to observe Discontinuous Conduction Mode(DCM) behaviour

---

### 2. Hardware Implementation

- Built the circuit using components and PWM generator
- Used:
  - **TL494** for PWM generation
  - **TC4428A** as gate driver
  - **IRFZ44N MOSFET** as switch
- Verified PWM signal using oscilloscope before connecting to power circuit
- Observed real-time waveforms on an oscilloscope to validate functionality
- Fine-tuned the duty cycle to achieve the required output voltage range
---

## Files in Repositry
- powerproject.slx – Simulink model of the converter

## Images

Hardware Setup
 <img width="636" height="582" alt="converter" src="https://github.com/user-attachments/assets/605e25a2-c6b9-4948-bff7-465cbdf36db4" />
 <img width="560" height="464" alt="gate_driver" src="https://github.com/user-attachments/assets/222bedc7-7e15-4fdd-84b8-190cbe8daa70" />








