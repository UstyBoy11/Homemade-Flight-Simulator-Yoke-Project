# Project Statement:

**Objective:** Create a functional, DIY flight simulator yoke controller that leverages the PS5 DualSense controller's built-in gyroscope and motion sensors to provide intuitive pitch and roll input for flight simulation software on PC or console platforms.

**Purpose:** Instead of buying the Thrustmaster Boeing Yoke for $700, I need to develop an affordable, customizable alternative to commercial flight yokes by mechanizing and integrating consumer gaming hardware with a physical mechanical frame. This project aims to deliver an immersive flight simulator experience for enthusiasts and hobbyists at a fraction of commercial yoke cost.

**Key Goals:**
- Have a functional ATC Push-to-Talk and AP Disconnect button wired inside the yoke.
- Design a mechanical frame that replicates the form factor and ergonomics of a real aircraft yoke
- Model components in Fusion 360 and export STL files for 3D printing in the FlashForge Orca Slicer Program
- Calibrate and map PS5 controller gyroscope data to flight simulator axes (pitch, roll)
- Achieve responsive, lag-free control suitable for realistic flight simulation
- Create a modular design allowing for future enhancements (force feedback, throttle quadrant, pedals)

---

# Constraints:

## Technical Constraints
- **Hardware Limitation:** PS5 DualSense controller gyroscope has ~±60° motion range and limited precision at extreme angles
- **Connectivity:** Wireless Bluetooth connection introduces latency (~10-20ms); must implement smoothing/filtering to minimize control lag
- **Processing Power:** Real-time motion data processing must run on available compute platform (PC/PS5) without significant frame rate impact
- **Sensor Calibration:** Gyroscope drift requires periodic recalibration or implementation of drift compensation algorithm

## Design Constraints
- **Form Factor:** Physical yoke must maintain ergonomic grip and comfortable 2-hand operation
- **Weight & Balance:** Total assembly should be < 3 kg to remain portable and stable on typical desk/table
- **Space Requirements:** Compact enough to fit in a standard gaming setup (~60cm width max)
- **Durability:** Frame must withstand repeated pull/push forces without structural failure (estimated 10,000+ cycles)
- **3D Printer Limitations:** Design must account for available 3D printer build volume and material properties; complex geometry must be designed for multi-part assembly and printing

## Budget Constraints
- **Material Cost:** Target ≤$150 USD for frame materials and mechanical components (primarily 3D printer filament and hardware)
- **Controller Requirement:** Assumes user already owns PS5 DualSense controller (not included in budget)
- **No Commercial Yoke Motors:** Cannot use pre-built yoke assemblies; must build from scratch using 3D printed parts and repurposed materials
- **Available Tools:** Leverages existing 3D printer and Fusion 360 CAD software (no additional software licenses required)

## Software/Integration Constraints
- **Compatibility:** Must work with popular flight simulators (X-Plane, MSFS 2020, etc.) via standard joystick input mapping
- **Development Platform:** Code/configuration must be accessible to non-experts for setup and calibration
- **No Custom Firmware:** Cannot modify PS5 controller firmware; must work within standard HID protocol

## Time Constraints
- **Development Timeline:** Project should reach functional prototype stage within 4-8 weeks

---
## Materials
- Tape
- Super Glue
- Plumbing Pipe
- 2x Chopsticks
- PS5 Controller
- 8x Rubber Bands
- FlashForge Adventurer 5M Pro 3D-Printer
- 2x Simple Push Button
- Arduino MEGA 2560