# Hi there, I'm Cheewakorn 👋

🦅 **Computer Engineering Student** specializing in **Tactical UAVs, Edge AI Hardware, and Autonomous Tracking Systems**.  
I build end-to-end intelligent physical platforms — combining **flight controller avionics (SpeedyBee F405 / ArduPilot)**, **on-sensor NPU inference (Hailo-8L / Sony IMX500)**, **precision PTZ robotics (RS-485 / Pelco-D)**, and **real-time Computer Vision (YOLO11)**.

---

### 🛠️ Hardware & Tech Stack

#### 🚀 Flight Control, Robotics & Avionics
![F405 FC](https://img.shields.io/badge/SpeedyBee_F405-Flight_Controller-yellow?style=for-the-badge)
![ArduPilot](https://img.shields.io/badge/ArduPilot-Firmware-black?style=for-the-badge&logoColor=white)
![INAV](https://img.shields.io/badge/INAV-Fixed_Wing_%26_Multirotor-blue?style=for-the-badge)
![MAVLink](https://img.shields.io/badge/MAVLink-UART_Telemetry-orange?style=for-the-badge)
![Mission Planner](https://img.shields.io/badge/Mission_Planner-GCS-006699?style=for-the-badge)
![Pelco-D](https://img.shields.io/badge/RS485-Pelco--D_PTZ-red?style=for-the-badge)

#### 🧠 Edge AI, NPUs & Computer Vision
![Hailo-8L](https://img.shields.io/badge/Hailo--8L-13_TOPS_NPU-brightgreen?style=for-the-badge)
![IMX500](https://img.shields.io/badge/Sony_IMX500-AI_Camera_NPU-blueviolet?style=for-the-badge)
![YOLO11](https://img.shields.io/badge/YOLO11-Ultralytics-00FFFF?style=for-the-badge&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

#### 💻 Compute, GUI & Engineering Design
![Raspberry Pi 5](https://img.shields.io/badge/Raspberry_Pi_5-Compute-C51A4A?style=for-the-badge&logo=raspberry-pi&logoColor=white)
![Pi Zero 2 W](https://img.shields.io/badge/Pi_Zero_2_W-Companion-8A2BE2?style=for-the-badge&logo=raspberry-pi&logoColor=white)
![PySide6 Qt](https://img.shields.io/badge/PySide6-Qt_GUI-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![AutoCAD](https://img.shields.io/badge/AutoCAD-Mechanical_CAD-E51010?style=for-the-badge&logo=autodesk&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-PCB_Design-314CB0?style=for-the-badge&logo=kicad&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

---

### 🎯 Flagship Projects

#### 🦅 1. [Autonomous UAV Interceptor Guidance System](https://github.com/titleww/autonomous-uav-interceptor)
> **Autonomous Vision-Guided UAV Interceptor with On-Sensor Edge AI**
* **Companion Computing & AI:** Integrated Raspberry Pi Zero 2 W with Sony IMX500 AI Camera (12MP) executing **YOLO11** natively on the camera's hardware NPU (`.rpk`), achieving high-speed target detection with zero host CPU load.
* **Flight Avionics & Guidance:** SpeedyBee F405 flight controller running **ArduPilot / INAV**, paired with a 60A 4-in-1 ESC and M3115/900KV brushless motors on a 6S LiPo power bus.
* **Autonomous Guidance Laws:** Implements closed-loop **Proportional Navigation (PN)** and **PID trajectory algorithms** sending dynamic flight vectors over MAVLink (UART).
* **Video & Safety:** Analog composite TV-out overlay through F405 OSD to a Foxeer 4.9GHz VTX. Includes 3-stage parachute servo recovery failsafe.

#### 🎯 2. [Edge AI Optical PTZ Sky Tracking System](https://github.com/titleww/edge-ai-ptz-tracker)
> **Real-Time High-Altitude Target Acquisition & Precision PTZ Tracking**
* **Hardware Acceleration:** Raspberry Pi 5 accelerated by the **Hailo-8L M.2 AI HAT+ (13 TOPS NPU via PCIe)** running real-time YOLO for aerial object classification.
* **Closed-Loop PTZ Servo Control:** Custom PID controller driving an industrial **BIT-PT520 PTZ base** over **RS-485 (Pelco-D protocol)**, eliminating camera hunting and mechanical oscillation.
* **Mission Control Client:** Low-latency H.264 RTSP video streaming paired with an asynchronous WebSocket server and a standalone **PySide6 (Qt)** Windows Mission Control dashboard.

#### 🌊 3. [ThanPhai (ทันภัย)](https://github.com/Peem-Atikorn/ThanPhai)
> **Multi-hazard disaster early warning web platform** aggregating real-time hydrological and meteorological data with AI querying.

---

### 🚀 Engineering Highlights
- 🔭 **Current Focus:** Hardware-software co-design: Low-latency Edge AI pipelines on dedicated NPUs (Hailo-8L / IMX500) integrated with UAV autopilots.
- ⚙️ **CAD & Prototyping:** Custom 2D/3D component modeling in **AutoCAD**, custom sensor carrier and power distribution **PCB layouts** with schematic & BOM generation.
- 💬 **Ask me about:** ArduPilot / MAVLink integration, Hailo-8L NPU deployment, Pelco-D PTZ control, and F405 power isolation.

---

### 📫 Connect with Me
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cheewakornartdeelang@gmail.com)
