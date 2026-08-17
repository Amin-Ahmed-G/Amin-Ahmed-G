# Amin Ahmed G

#### `Robotics Engineer` · `ROS 2 / Nav2` · `DDS/RTPS Security` · `Industrial Automation`

[![GitHub](https://img.shields.io/badge/GitHub-0B0F14?style=for-the-badge&logo=github&logoColor=E6EDF3)](https://github.com/Amin-Ahmed-G)
[![Portfolio](https://img.shields.io/badge/Portfolio-0B0F14?style=for-the-badge&logo=Firefox&logoColor=22D3EE)](https://amin-ahmed-g.github.io/Protofolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B0F14?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/amin-ahmed-g/)
[![Gmail](https://img.shields.io/badge/Gmail-0B0F14?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:aminahmedg2005@gmail.com)

---

### Who I Am

Final-year **Robotics and Automation Engineering** student at Anna University, currently working at the intersection of two disciplines most engineers keep in separate boxes: **autonomous robotics software** and **the security of the middleware those robots depend on**.

I build things. I break them on purpose to understand the failure modes. Then I document what I learn in code.

My current work sits across three layers of the same stack:

- **Software** — ROS 2 multi-robot systems, Nav2 stack, AMCL-based localization, pure-pursuit control
- **Security** — DDS/RTPS traffic analysis, passive network intrusion detection for ROS 2 environments (written in Rust)
- **Hardware/OT** — PLC programming in CODESYS (IEC 61131-3), embedded sensor design (PCB layout → Gerber → fab), industrial motor and process control

This isn't a resume of tutorial projects. These are real systems where I encountered real problems — localization drift, TF tree conflicts, undocumented RTPS behavior — and solved them.

---

### Technical Stack

**Robotics & Autonomous Systems**

[![ROS2](https://img.shields.io/badge/ROS_2_Jazzy-0B0F14?style=flat-square&logo=ros&logoColor=22D3EE)](#)
[![Nav2](https://img.shields.io/badge/Nav2-0B0F14?style=flat-square&logoColor=22D3EE)](#)
[![Gazebo](https://img.shields.io/badge/Gazebo_Harmonic-0B0F14?style=flat-square&logoColor=22D3EE)](#)
[![AMCL](https://img.shields.io/badge/AMCL_%2F_SLAM-0B0F14?style=flat-square&logoColor=22D3EE)](#)
[![tf2](https://img.shields.io/badge/tf2_%2F_URDF-0B0F14?style=flat-square&logoColor=22D3EE)](#)

**Security & Systems**

[![Rust](https://img.shields.io/badge/Rust-0B0F14?style=flat-square&logo=rust&logoColor=F97316)](#)
[![DDS/RTPS](https://img.shields.io/badge/DDS_%2F_RTPS-0B0F14?style=flat-square&logoColor=F97316)](#)
[![Wireshark](https://img.shields.io/badge/Packet_Analysis-0B0F14?style=flat-square&logo=wireshark&logoColor=F97316)](#)
[![CycloneDDS](https://img.shields.io/badge/CycloneDDS-0B0F14?style=flat-square&logoColor=F97316)](#)

**Industrial & Embedded**

[![CODESYS](https://img.shields.io/badge/CODESYS_%2F_IEC_61131--3-0B0F14?style=flat-square&logoColor=94A3B8)](#)
[![C++](https://img.shields.io/badge/C%2B%2B_17-0B0F14?style=flat-square&logo=cplusplus&logoColor=94A3B8)](#)
[![Python](https://img.shields.io/badge/Python_3-0B0F14?style=flat-square&logo=python&logoColor=94A3B8)](#)
[![EasyEDA](https://img.shields.io/badge/PCB_Design-0B0F14?style=flat-square&logoColor=94A3B8)](#)
[![Linux](https://img.shields.io/badge/Linux_%2F_Ubuntu-0B0F14?style=flat-square&logo=linux&logoColor=94A3B8)](#)

---

### Featured Work

| Project | What It Actually Does | Stack |
|---|---|---|
| [**RoboShield**](https://github.com/Amin-Ahmed-G/robotshield) ⭐ 4 | Passive RTPS traffic watchdog for ROS 2. Inspects DDS network traffic for anomalies without sitting inline. Built because ROS 2 assumes a trusted local network by default — an assumption that breaks the moment a robot leaves a lab. | `Rust` `DDS/RTPS` `CycloneDDS` |
| [**AMR Leader-Follower**](https://github.com/Amin-Ahmed-G/amr_leader_follower) | Leader on Nav2/SLAM, follower on AMCL with a custom pure-pursuit controller. Debugged against actual localization drift and TF tree conflicts in Gazebo Harmonic — not a clean-demo build. | `ROS 2` `Nav2` `AMCL` `tf2` |
| [**Differential-Drive Nav Robot**](https://github.com/Amin-Ahmed-G/two_wheel_robot) | LiDAR + camera platform built to test whether navigation logic generalizes across drive kinematics. Validates the stack, not just the hardware. | `ROS 2` `SLAM` `LiDAR` |
| [**Café Butler Robot**](https://github.com/Amin-Ahmed-G/cafe-butler-robot) | Autonomous order delivery robot with multi-table navigation, timeout handling, and partial-delivery fallback logic. Service-logic edge cases built in from the start. | `ROS 2` `Python` `Nav2` |
| [**Gesture-Controlled Robot**](https://github.com/Amin-Ahmed-G/ros2_gesture_control_bot) | Real-time hand-gesture teleoperation over ROS 2 topics — computer vision pipeline feeding velocity commands directly to the drive node. | `ROS 2` `Python` `MediaPipe` |
| [**Motor Control PLC**](https://github.com/Amin-Ahmed-G/motor-control-plc) | Industrial motor control in CODESYS — start/stop latching, emergency override, timer-based activation — structured in Ladder Diagram per IEC 61131-3. | `CODESYS` `Ladder Logic` |
| [**ESP32 Temperature PCB**](https://github.com/Amin-Ahmed-G/temp-sensor-pcb) | Custom-designed temperature monitoring board: LM35 sensor, AMS1117-3.3 regulator, USB power input, fabrication-ready Gerber files. Full hardware loop from schematic to silkscreen. | `EasyEDA` `LM35` `AMS1117` |

---

---

### Why This Combination

Robotics engineers typically don't know OT security. Security engineers typically don't know how DDS pub/sub topologies actually behave under load or in degraded network conditions. Industrial automation engineers typically know neither ROS 2 nor network-layer threat modeling.

The convergence of autonomous mobile robots with industrial control environments creates a gap that none of those three communities fully occupies. That gap is where I intend to work.

---

**Open to:** Robotics software engineering · Autonomous systems · ROS 2 / Nav2 development · Robotics/ICS security research

[@Amin-Ahmed-G](https://github.com/Amin-Ahmed-G) · [LinkedIn](https://www.linkedin.com/in/amin-ahmed-g/) · [aminahmedg2005@gmail.com](mailto:aminahmedg2005@gmail.com) · Anna University · Robotics and Automation Engineering
 
