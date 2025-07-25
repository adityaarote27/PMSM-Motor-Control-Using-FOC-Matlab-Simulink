# ⚡ PMSM Motor Drive Using FOC Field-Oriented Control and PI Controller - MATLAB/Simulink

This repository contains a full Simulink model of a **Permanent Magnet Synchronous Motor (PMSM)** drive system controlled using **Field-Oriented Control (FOC)**. The project demonstrates inverter control, motor feedback sensing, and closed-loop speed regulation.

---

## 🎯 Objective

To design and simulate a PMSM motor control system using FOC, enabling precise torque and speed control through:
- Vector transformations (Clarke & Park)
- Current & speed feedback
- PWM inverter switching

---

## 🧠 Key Features

- ✅ **PMSM Motor Model** – with electrical and mechanical dynamics  
- ✅ **Three-Phase Inverter** – built with IGBTs for realistic switching  
- ✅ **Current Sensor** – three-phase current feedback (i<sub>a</sub>, i<sub>b</sub>, i<sub>c</sub>)  
- ✅ **Encoder & Position Feedback** – providing rotor position and speed  
- ✅ **FOC Controller** – implementing Park/Clarke transforms and PI controllers  
- ✅ **Speed Reference Input** – dynamic tracking of reference RPM  

---

## 🛠️ Tools & Technologies

- MATLAB & Simulink  
- Simscape Electrical  
- Power Electronics Modeling  
- Embedded Control Systems  

---

## 📈 Outputs Observed

- Three-phase current waveforms  
- Rotor speed tracking vs reference  
- Torque generation  
- Inverter gate signal profiles  

---

## 🖼️ System Diagrams

### 🔲 System Overview
![System Overview](./images/system_overview.png)

### 🔲 Inverter Model
![Three Phase Inverter](./images/inverter.png)

### 🔲 FOC Controller Block
![FOC](./images/foc_block.png)

### 🔲 Current Sensor
![Current Sensor](./images/current_sensor.png)

### 🔲 PMSM Feedback System
![Motor Encoder & Feedback](./images/encoder_feedback.png)

> 📁 *Images should be placed in a `/images` folder in the root of the repo.*

---

## 🚀 Applications

- Electric Vehicle Powertrain  
- Robotics and Motion Control  
- Industrial Drives  
- Motor Control Unit (MCU) Testing

---

## 📌 Author

**Aditya Arote**  
Electrical Engineer | EV Systems Learner | Embedded Enthusiast

[LinkedIn](https://www.linkedin.com)


