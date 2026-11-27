UR-ROBOTish: Six-Axis Robotic Arm
Overview
UR-ROBOTish is a six-axis robotic arm developed for a senior design project at Northern Illinois University (2024–2025). The project combines mechanical design, robotic control, and computer vision to perform color-based pick-and-place and object sorting. The arm was designed and assembled in SolidWorks, with Raspberry Pi–based PD position control used for joint positioning.
Features
- Six-axis articulated robotic arm designed in SolidWorks
- Color-based object recognition and sorting
- Pick-and-place manipulation using a robotic gripper
- PD position control for joint movement
- Raspberry Pi–based control system
- Complete CAD assembly and part files included in the repository
Hardware
- Robot: Custom six-axis robotic arm
- Mechanical design: SolidWorks assembly and components
- Controller: Raspberry Pi
- Actuation: Joint actuators and a gripper mechanism
- Vision: Camera-based color recognition
Software Stack
- CAD: SolidWorks
- Control: Proportional–Derivative (PD) position control
- Computer vision: Color-based object detection
- Main processing platform: Raspberry Pi
Demo
Click the image below to watch the robot demonstration on YouTube.

Watch the full demonstration on YouTube
Project Poster
<!-- Export the poster PowerPoint to PNG and upload it as assets/poster-preview.png. -->
[View the original project poster (PowerPoint)](CURE-Poster%2048X36.pptx)
Mechanical Design (SolidWorks)
The full robot-arm design, including assembly and component files, is stored in the UR ROBOTish folder.

[View the SolidWorks CAD files](UR%20ROBOTish/)
<!-- Optional: Upload a SolidWorks assembly screenshot as assets/robot-arm.png, then uncomment:
![SolidWorks assembly of UR-ROBOTish](assets/robot-arm.png)
-->
To explore the design:
1. Open the [`UR ROBOTish`](UR%20ROBOTish/) directory.
2. Download the assembly and corresponding component files.
3. Open the main assembly file in SolidWorks, keeping the referenced parts accessible.
System Workflow
1. Detect an object and identify its color.
2. Select the corresponding sorting destination.
3. Move the robotic arm toward the pick location.
4. Grasp the object and transfer it to the target location.
5. Release the object to complete the sorting task.
Repository Contents
- [`UR ROBOTish/`](UR%20ROBOTish/) — SolidWorks assembly and mechanical design files
- [`CURE-Poster 48X36.pptx`](CURE-Poster%2048X36.pptx) — Senior design project poster
- [`Senior Design Demo Video.mov`](Senior%20Design%20Demo%20Video.mov) — [Original demo video file](https://www.youtube.com/watch?v=0eG_HPvna9Y)
Project Recognition
Selected among the top five of 30 senior design teams at Northern Illinois University's College of Engineering and Engineering Technology (CEET) senior design showcase.
Project: UR-ROBOTish
Institution: Northern Illinois University
Academic Year: 2024–2025
