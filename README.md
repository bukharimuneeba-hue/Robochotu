# RoboChotu – Assistive Robot System

## About the Project
RoboChotu is an assistive social robot system developed to support interactive and therapeutic activities. The system integrates the robot's embedded controller, wireless remote control, tablet-based robot face/interface, and Unity-based components into a unified architecture.

The project consists of four major components:
* **Arduino:** Embedded control and robot hardware interface.
* **Remote:** Wireless remote-control application used to send commands.
* **Tablet:** Acts as the robot's interactive face and communication gateway.
* **Unity:** Unity-based interactive and visual face components.

---

## Bluetooth Communication Architecture
The system uses a three-device Bluetooth communication architecture:

$$\text{Remote} \longrightarrow \text{Tablet (Robot Face)} \longrightarrow \text{HC-05} \longrightarrow \text{Robot Controller (Arduino)}$$

> **Note:** The remote does not communicate directly with the HC-05 module. Instead, the tablet runs the Face application and serves as an intermediary/gateway. It receives command strings from the remote app and routes motor locomotion instructions to the HC-05 connected to the Arduino Mega, while handling facial expressions and audio locally.

---

## Repository Structure

```text
Robochotu/
│
├── arduino/      # Robot controller and embedded firmware
├── remote/       # Remote-control Android application
├── tablet/       # Tablet-based robot face Android application
├── unity/        # Unity 3D interactive facial assets and animations
└── README.md     # Project documentation
