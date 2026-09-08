RoboChotu – Assistive Robot System
About the Project
RoboChotu is an assistive social robot system developed to support interactive and therapeutic activities. The system integrates the robot's embedded controller, wireless remote control, tablet-based robot face/interface, and Unity-based components into a unified architecture.
The project consists of four major components:
•	Arduino – Embedded control and robot hardware interface.
•	Remote – Wireless remote-control application/device used to send commands.
•	Tablet – Acts as the robot's interactive face and communication gateway.
•	Unity – Unity-based interactive/visual components of the robot system.
Bluetooth Communication Architecture
The system uses a three-device Bluetooth communication architecture:
Remote → Tablet (Robot Face) → HC-05 → Robot Controller
The remote does not communicate directly with the HC-05. Instead, the tablet runs the Face application and acts as an intermediary/gateway. The tablet communicates with the HC-05 Bluetooth module connected to the robot's controller, while receiving commands from the remote through the Face application.
This architecture allows the robot's control and interactive interface to be integrated into a single system.
Repository Structure
Robochotu/
│
├── arduino/     # Robot controller and embedded code
├── remote/      # Remote-control application/code
├── tablet/      # Tablet / robot face application
├── unity/       # Unity-based interactive components
└── README.md    # Project documentation
Research Paper
This repository contains the software and implementation components associated with the following research work:
Paper Title:
Design and Development of a Low-Cost Social Robot for use in Autism Therapy
Paper: Paper Title
Publication Status: Submitted for review
Conference/Journal: ICET2026
Submission Date: August 2026
The repository is intended to provide the implementation and supporting resources related to the research work and to facilitate reproducibility and further development of the RoboChotu system.
Project Purpose
RoboChotu is designed as a platform for exploring human–robot interaction, assistive robotics, interactive therapy, and educational applications. The modular architecture allows individual hardware and software components to be developed and maintained independently while operating as part of the complete robotic system.
Technologies
•	Arduino / Embedded Systems
•	HC-05 Bluetooth
•	Android / Tablet Application
•	Unity
•	Bluetooth Communication
•	Human–Robot Interaction (HRI)
•	Assistive Robotics
Authors / Contributors
Add the names of the researchers and developers who contributed to the RoboChotu project.
Repository
RoboChotu GitHub Repository:
https://github.com/bukharimuneeba-hue/Robochotu

