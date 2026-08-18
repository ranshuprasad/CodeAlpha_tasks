CodeAlpha Robotics & Automation Internship

Overview

This repository contains my CodeAlpha Robotics & Automation Internship task submissions, including a research report on service robots and an automated smart home lighting system design.

The work demonstrates research, robotics concepts, automation-system design, sensors, microcontrollers, control logic, and technical documentation.

Projects

Task 1 — Service Robots Research Report

Topic: Service Robots: Transforming Domestic, Agricultural, and Military Operations

This report explores three major areas of service robotics:

Domestic service robots

Agricultural service robots

Military and defence service robots

Enabling technologies

Benefits and challenges

Economic and market impact

Future outlook

The report includes figures, comparison tables, analysis, conclusion, and references.

File: Task-1-Service-Robots-Research-Report.pdf

Task 3 — Automated Smart Home Lighting System

System: Sensor-Based Automatic Lighting with Manual Override

The design uses:

Arduino UNO — central controller

PIR sensor — detects human motion

LDR sensor — measures ambient light

Relay module — switches the lighting load

LED lamp — controlled output

Manual switch / mobile control — manual override

5 V power supply — low-voltage electronics

Working Principle

The system combines ambient light and human presence:

The LDR measures the surrounding light level.

If the environment is bright, the light remains OFF.

If the environment is dark, the Arduino checks the PIR sensor.

When motion is detected in darkness, the relay switches the light ON.

After motion stops, a configurable delay can switch the light OFF.

Manual control can override the automatic operation.

The report contains the system architecture/control-flow diagram, component table, operating logic, advantages, applications, safety notes, and conclusion.

File: Task-3-Smart-Home-Lighting-System.pdf

Repository Structure

codealpha-robotics-automation/
│
├── README.md
├── Task-1-Service-Robots-Research-Report.pdf
└── Task-3-Smart-Home-Lighting-System.pdf

Skills Demonstrated

Robotics and automation fundamentals

Service robotics research

Sensor-based automation

Arduino-based control systems

PIR and LDR sensor integration

Relay-controlled output

Control-flow and system architecture design

Technical report writing

Engineering documentation

Safety considerations for automated systems

Safety Note

The Task 3 design separates the low-voltage controller from the lighting load using a relay. Any household AC-mains wiring, testing, or installation should be performed by a qualified electrician. For student prototyping, a low-voltage lamp or certified isolated training load is recommended.

Internship

Program: CodeAlpha Robotics & Automation Internship
Tasks included: Task 1 and Task 3
