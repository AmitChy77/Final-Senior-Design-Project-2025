<div align="center">UR-ROBOTish
A UR-Inspired Robotic Arm for Vision-Guided Pick-and-Place
Senior Design Project (2024–2025) · Northern Illinois University

SolidWorks · Raspberry Pi · Python · Computer Vision · PD Position Control

Watch the Demo · View the Poster · Explore the CAD Models · Project Highlights
</div><!-- Export a SolidWorks assembly render or robot photograph to assets/robot-arm.png. -->
Project Overview
UR-ROBOTish is a senior-design robotic manipulator inspired by the form and operation of Universal Robots arms. The project combined mechanical design, actuator integration, robot control, and vision-guided manipulation to develop a system for color-based object sorting and pick-and-place tasks.

The arm was designed in SolidWorks, with a Raspberry Pi–based PD position-control system used for joint positioning. The project explored color recognition and pose estimation to connect visual observations with robot actions.
Recognition: Selected among the top five of 30 senior-design teams at Northern Illinois University's College of Engineering and Engineering Technology (CEET) senior-design showcase.

🎬 Robot Demonstration
A demonstration of the completed senior-design project is available on YouTube. Click the video thumbnail to watch it.

▶ Watch the full robot demonstration on YouTube

Note: GitHub README files display the YouTube thumbnail as a linked image; playback opens on YouTube.
🖼 Project Poster
The presentation poster provides an overview of the design concept, mechanical development, and project work.
<!-- Export your PowerPoint poster as a PNG and upload assets/poster-preview.png. -->
[!\[UR-ROBOTish senior-design project poster\]\(assets/poster-preview.png)](CURE-Poster%2048X36.pptx)

[View or download the original PowerPoint poster](CURE-Poster%2048X36.pptx)
⚙️ Mechanical Design
The robot arm was modeled and assembled in SolidWorks, using a Universal Robots–inspired articulated-arm configuration. The CAD files allow visitors to inspect the design and understand its mechanical layout.

[📁 Explore the SolidWorks assembly and part files](UR%20ROBOTish/)

The UR ROBOTish/ directory contains the mechanical-design files. Open the main assembly in SolidWorks with its associated component files available in the same project directory; missing references may need to be resolved if individual parts have been moved.
🧠 Control and Vision Approach
The project combines multiple engineering areas:
Subsystem	Project approach
Mechanical design	UR-inspired robotic arm developed in SolidWorks
Actuation	Servo-driven arm and end-effector/gripper mechanism
Robot control	Raspberry Pi–based joint position control using a PD controller
Perception	Color-based object detection for RGB sorting tasks
Manipulation	Robot positioning, gripping, and placement of objects into corresponding sorting locations


Intended manipulation workflow
Observe colored object
         ↓
Determine object color and target location
         ↓
Estimate a suitable robot pick position
         ↓
Command arm movement and gripper
         ↓
Pick up object → Move to sorting location → Release
This summarizes the system's task-level workflow rather than claiming a specific detection rate, positioning accuracy, or cycle time.
🏆 Project Highlights
- Designed a UR-inspired robotic manipulator from the ground up using SolidWorks.
- Integrated mechanical design, electronics, control, and vision-guided manipulation within a single senior-design project.
- Developed the system around color-based pick-and-place and sorting.
- Received top-five recognition among 30 CEET senior-design teams.
📂 Repository Contents
File / Directory	Description
[`UR ROBOTish/`](UR%20ROBOTish/)	SolidWorks assembly and part/design files
[`CURE-Poster 48X36.pptx`](CURE-Poster%2048X36.pptx)	Original project poster
YouTube demonstration	Watch the robot arm in action
[`Senior Design Demo Video.mov`](Senior%20Design%20Demo%20Video.mov)	Original MOV file stored in this repository
assets/robot-arm.png	SolidWorks assembly render or a photograph of the robot (add to assets/)
assets/poster-preview.png	PNG preview of the project poster (add to assets/)


👤 Project Information
Institution: Northern Illinois University
Program: Mechanical Engineering — Senior Design
Academic year: 2024–2025
Project: UR-ROBOTish
<div align="center">Mechanical design · Robotic control · Computer vision · Mechatronics
</div>
