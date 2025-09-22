# 🌡️ Thermostat Events Application

A **C# console application** that simulates a smart thermostat system with **event-driven temperature monitoring**, **cooling mechanism control**, and **emergency handling capabilities**.

---

## 📖 Overview

This application demonstrates an **event-driven architecture** for a thermostat system that monitors temperature readings and responds to different thresholds.  
The system automatically controls a cooling mechanism and handles emergency situations when temperatures reach critical levels.

---

## 🚀 Features

- **Real-time Temperature Monitoring**  
  Continuously monitors temperature readings from simulated sensor data.

- **Event-driven Architecture**  
  Uses C# events to handle temperature threshold notifications.

- **Multi-level Alert System**  
  - ⚠️ **Warning Level (27°C and above):** Activates cooling mechanism  
  - 🔥 **Emergency Level (75°C and above):** Triggers emergency shutdown procedures  

- **Automatic Cooling Control**  
  Intelligent cooling mechanism that turns on/off based on temperature readings.

- **Color-coded Console Output**  
  Visual feedback with different colors for different alert levels.

- **Emergency Response**  
  Automatic device shutdown and emergency notification system.

---

## 🛠️ System Architecture

The application follows **SOLID principles** and uses **dependency injection** through interfaces.

### Core Components
- **Device** → Main device controller that manages the overall system  
- **Thermostat** → Orchestrates the interaction between heat sensor and cooling mechanism  
- **HeatSensor** → Monitors temperature and raises events when thresholds are reached  
- **CoolingMechanism** → Controls the cooling system (on/off operations)  
- **TemperatureEventArgs** → Custom event arguments for temperature-related events  

### Key Interfaces
- **IDevice** → Device management and emergency handling  
- **IThermostat** → Thermostat control operations  
- **IHeatSensor** → Temperature monitoring and event handling  
- **ICoolingMechanism** → Cooling system control  

## 📸 Screenshot

Here’s an example of the application running:
<img width="771" height="842" alt="image" src="https://github.com/user-attachments/assets/0d3d0200-5276-4493-8624-c952606eec31" />


