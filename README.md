# 🤖 CodeAlpha Robotics & Automation Internship

<p align="center">
  <strong>Robotics • Automation • Sensors • Embedded Systems</strong>
</p>

<p align="center">
  CodeAlpha Internship Task Submissions
</p>

---

## 📌 Overview

This repository contains my **CodeAlpha Robotics & Automation Internship** task submissions.

The projects demonstrate:

- Robotics and automation fundamentals
- Service robotics research
- Sensor-based automation
- Arduino-based control systems
- System architecture and control logic
- Technical report writing
- Engineering documentation
- Safety considerations for automated systems

---

# 📚 Projects

## 🤖 Task 1 — Service Robots Research Report

### Topic

**Service Robots: Transforming Domestic, Agricultural, and Military Operations**

This research report examines service robotics across three major application areas:

- 🏠 Domestic service robots
- 🌾 Agricultural service robots
- 🛡️ Military and defence service robots

The report also discusses enabling technologies, benefits, challenges, economic impact, and future developments. The report covers technologies such as LiDAR/SLAM, computer vision, connectivity, RTK-GPS, multispectral imaging, machine learning, autonomous navigation, and ruggedised military systems. :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3}

### Report Contents

- Executive Summary
- Introduction
- Domestic Service Robots
- Agricultural Service Robots
- Military Service Robots
- Enabling Technologies
- Comparative Analysis
- Economic and Market Impact
- Robotics-as-a-Service (RaaS)
- Future Outlook
- Conclusion
- References


---

# 💡 Task 3 — Automated Smart Home Lighting System

## System

**Sensor-Based Automatic Lighting with Manual Override**

The project presents an automated smart-home lighting system designed to switch lights according to **ambient light and human presence**, while retaining manual control. :contentReference[oaicite:4]{index=4}

---

## 🔧 Components Used

| Component | Function |
|---|---|
| **Arduino UNO** | Central controller |
| **PIR Sensor** | Detects human motion |
| **LDR + Resistor** | Measures ambient light |
| **1-Channel Relay Module** | Switches the lighting load |
| **LED Lamp** | Lighting output |
| **AC–DC 5 V Supply** | Powers low-voltage electronics |
| **Wall Switch / Mobile Control** | Manual override |

These components and their roles are documented in the Task 3 report. :contentReference[oaicite:5]{index=5}

---

## ⚙️ Working Principle

The system combines **ambient light detection** and **human presence detection**.

### 1. Detect Ambient Light

The **LDR sensor** continuously measures the surrounding brightness.

If the environment is sufficiently bright, the light remains OFF unless manual override is used.

### 2. Detect Human Motion

If the environment is dark, the Arduino checks the **PIR sensor** for motion.

### 3. Turn the Light ON

When:

```text
Environment = DARK
        AND
Motion = DETECTED
