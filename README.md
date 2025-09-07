
<div align="center">
   <img src="https://img.shields.io/badge/ESP32-WROOM-blue?logo=espressif" />
   <img src="https://img.shields.io/badge/Robotics-Learning-green?logo=robot" />
</div>

# 🤖 **RoboCore-32**
### *An ESP32-Powered Robot Controller Board*

<div align="center">
   <img src="Assets/Block Diagrm.PNG" width="400" alt="Block Diagram" />
</div>

---


## ✨ **Why RoboCore-32?**
RoboCore-32 is a custom PCB for **robotics learning, prototyping, and IoT projects**. It features:

- 🟦 **ESP32-WROOM-32** (Wi-Fi + BLE microcontroller)
- ⚡ **TB6612FNG Dual H-Bridge Driver** – control up to **2 DC motors**
- 🔋 **Onboard Power Management**
   - LM2596S-5 → 5V buck regulator (up to ~3A)
   - AMS1117-3.3 → 3.3V LDO regulator
- 🖥️ **USB Programming & Debugging** via FT232RL USB–UART
- 🔌 **Barrel Jack Power Input** with auto switching
- 🧩 **Expansion Headers**
   - I²C JST header for sensors/displays
   - GPIO pin headers (1×02, 1×03, 1×04)
- 🔘 **User Input Button** (Reset/Boot/User configurable)

---

## 🛠️ **Applications**
- 🤖 2-Wheel Robots (line follower, obstacle avoidance)
- 🌐 IoT-enabled robotic platforms (Wi-Fi/BLE control)
- 🎓 Educational robotics & embedded systems
- ⚡ Rapid prototyping for automation

---


## 🧩 **Hardware Overview**

| Section           | Components                         |
|-------------------|------------------------------------|
| **MCU**           | ESP32-WROOM-32                     |
| **Motor Driver**  | TB6612FNG (dual channel, H-Bridge) |
| **Power**         | LM2596S-5 (5V), AMS1117-3.3 (3.3V) |
| **Connectivity**  | USB Micro-B (FT232RL), JST I²C     |
| **Inputs/Outputs**| Multiple GPIO headers, push button |

---


## 🗂️ **Repository Structure**

```text
📂 RoboCore-32
┣ 📁 hardware        # KiCad project files, Gerbers, BOM
┣ 📁 firmware        # Example ESP32 code (Arduino/ESP-IDF)
┣ 📁 docs            # Datasheets, diagrams, images
┗ README.md
```


## 📸 **Images**
<!-- Add PCB renders or real board photos here -->
- Top View

<img src="Assets\Front_Layer.PNG" width="400" alt="Front_Layer" />

- Bottom View

<img src="Assets\Back_Layer.PNG" width="400" alt="Back_Layer" />

- 3D View

<img src="Assets\3D design.PNG" width="400" alt="3D design" />

---



## 📸 Images
(Add PCB renders or real board photos here)

- Top View  
- Bottom View  
- Assembled Prototype  

---

## 🙌 Credits
Designed by **Avishka Vishwajith** as a learning project in robotics and embedded systems.  
Powered by [KiCad](https://www.kicad.org/) and manufactured by PCBWay.  

---

