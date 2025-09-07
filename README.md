# 🚦 Smart Traffic Light System using FATEK PLC

A **traffic light control system** for vehicles and pedestrians, implemented using a **FATEK 24S-MA PLC**.  
The project demonstrates safe and efficient traffic management through **manual** and **automated control modes**, designed and tested with LEDs to simulate real-world signals.  

---

## 🧩 Features

- **Dual Operation Modes**  
  - Automatic: Time-sequenced control of vehicle and pedestrian signals  
  - Manual: Push-button input to override signals when needed  

- **Safe Traffic Flow**  
  - Avoids signal conflicts between vehicles and pedestrians  
  - Ensures safety with precise timing  

- **Simulation with LEDs**  
  - Red, Yellow, Green lights simulated using LEDs  
  - Provides real-world visualization without external hardware risks  

---

## ⚙️ System Architecture

### Hardware
- **FATEK 24S-MA PLC**  
- Push-button switches (pedestrian & manual control)  
- LEDs (Red, Yellow, Green for both vehicles & pedestrians)  
- Resistors, breadboard, and wiring for simulation  

### Software
- **WinProladder** – used to design and upload ladder logic  
- **Ladder Diagram** – defines timing, sequencing, and control  

---

## 🛠️ Implementation

1. **Signal Timing**  
   - Vehicle cycle: Green → Yellow → Red  
   - Pedestrian cycle: Walk → Stop  
   - Adjustable timers for each phase  

2. **Control Logic**  
   - Automatic sequencing using PLC timers and relays  
   - Manual mode enabled via push-button inputs  

3. **Simulation**  
   - LEDs connected to PLC outputs to represent signal states  
   - Validated both automated and manual control modes  

---

## 🚀 Getting Started

### Requirements
- FATEK 24S-MA PLC  
- WinProladder software (for ladder programming)  
- LED + resistors + push buttons  
- Power supply & wiring  

### Steps
1. Install **WinProladder** on your PC.  
2. Connect PLC via communication cable.  
3. Open the provided ladder diagram file (`traffic_lights.pcd`).  
4. Download the program to the PLC.  
5. Connect LEDs and push buttons as per circuit diagram.  
6. Run in either **Automatic** or **Manual** mode.  

---

## 📸 Demo & Diagram
<img width="365" height="781" alt="tarffic light plc" src="https://github.com/user-attachments/assets/a372d612-3df5-458b-a8ff-5198ea047af7" />


## 🎯 Outcomes
- Demonstrated **safe and efficient traffic light sequencing**.  
- Verified **dual-mode control** (manual override + automatic mode).  
- Built a foundation for scaling to real-world intersections with sensors and advanced logic.  

---

## 🔖 Tags
`#PLC` `#IndustrialAutomation` `#SmartTraffic` `#FATEK`  
`#LadderLogic` `#WinProladder` `#EmbeddedSystems` `#TrafficControl`
