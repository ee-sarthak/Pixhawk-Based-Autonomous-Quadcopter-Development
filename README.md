# 🚁 Pixhawk Autonomous Quadcopter | UAV Assembly & Autonomous Mission Planning

![UAV](https://img.shields.io/badge/Project-Autonomous%20UAV-blue)
![Hardware](https://img.shields.io/badge/Hardware-Pixhawk-green)
![Firmware](https://img.shields.io/badge/Firmware-ArduPilot-orange)
![Software](https://img.shields.io/badge/Software-Mission%20Planner-red)

---

## 📌 Project Overview

This project involved the complete **assembly, configuration, calibration, and testing of a Pixhawk-based autonomous quadcopter**.

The objective was to understand and implement the complete UAV development workflow including:

- UAV hardware assembly and integration
- Pixhawk flight controller configuration
- Sensor calibration
- ArduPilot firmware setup
- GPS-based navigation
- Autonomous waypoint mission execution
- Flight testing and troubleshooting

The project covered the complete pipeline from:

**Drone Assembly → Hardware Configuration → Flight Controller Setup → Mission Planning → Autonomous Flight Testing**

---

# 🛠️ Hardware Implementation

## UAV / Quadcopter Assembly & Integration

- Assembled and integrated a complete quadcopter platform.
- Installed and configured the Pixhawk flight controller.
- Performed electronic wiring and soldering.
- Verified power connections and component functionality.
- Tested motors, ESCs, and communication systems.

---

## 🔩 Components Used

| Component | Purpose |
|-----------|---------|
| Pixhawk Flight Controller | Main UAV control system |
| Quadcopter Frame | Drone mechanical structure |
| Power Module | Power distribution and monitoring |
| GPS Module | Position tracking and navigation |
| BLDC Motors | Propulsion system |
| Electronic Speed Controllers (ESCs) | Motor speed control |
| RC Transmitter & Receiver | Manual flight control |
| LiPo Battery | UAV power source |
| Battery Tester | JST polarity verification |
| Servo Motor Tester | Motor direction verification |

---

# 💻 Embedded Software Configuration

## Mission Planner (ArduPilot)

Mission Planner was used for:

- Flight controller configuration
- Firmware installation
- Sensor calibration
- Parameter setup
- Mission planning
- Flight testing

---

# ⚙️ Pixhawk Setup & Calibration

## Firmware Configuration

Implemented:

- Installed ArduPilot Quadcopter X firmware
- Connected Pixhawk with Mission Planner
- Configured flight controller parameters
- Setup safety settings
- Verified communication between hardware and software

---

## Sensor Calibration

Performed complete calibration:

✅ Accelerometer calibration  
✅ Compass calibration  
✅ RC transmitter calibration  
✅ ESC calibration  
✅ Motor direction testing  

---

# 🛰️ Autonomous Mission Planning

Created and tested GPS-based autonomous missions using Mission Planner.

Implemented:

- Autonomous Takeoff
- GPS Waypoint Navigation
- Autonomous Landing

Mission Workflow:

```
Mission Planner
        |
        ↓
GPS Waypoint Mission
        |
        ↓
Pixhawk Flight Controller
        |
        ↓
Autonomous Flight Execution
```

---

# 🛫 Flight Testing & Validation

## Initial Flight Test

Performed initial flight testing to:

- Verify system functionality
- Validate hardware configuration
- Identify tuning and configuration issues
- Troubleshoot mission execution problems


## Final Flight Test

Successfully achieved:

✅ Autonomous takeoff  
✅ GPS waypoint navigation  
✅ Autonomous landing  
✅ Complete mission execution validation  

---

# 🧠 Skills Demonstrated

## UAV & Hardware

- UAV Assembly & Integration
- Drone Electronics
- Pixhawk Configuration
- Soldering and Wiring
- ESC and Motor Setup


## Embedded Systems

- ArduPilot Firmware
- Mission Planner
- Flight Controller Configuration
- Sensor Calibration
- Parameter Tuning


## Autonomous Systems

- GPS Navigation
- Waypoint Mission Planning
- Autonomous Flight Modes
- Flight Testing
- System Debugging

---

# 📊 Project Results

✔ Successfully built and configured a Pixhawk-based autonomous quadcopter.

✔ Established communication between Pixhawk and Mission Planner.

✔ Completed sensor, radio, ESC, and motor calibration.

✔ Created and tested GPS waypoint missions.

✔ Successfully demonstrated autonomous takeoff, navigation, and landing.

---

# 🚀 Future Improvements

- Integrate companion computer (Raspberry Pi / Jetson)
- Add computer vision-based navigation
- Implement YOLO-based object detection
- Develop real-time UAV monitoring dashboard
- Improve autonomous path planning algorithms

---

# 📂 Repository Structure

```
Pixhawk-Autonomous-Quadcopter/
│
├── README.md
│
├── Hardware/
│   ├── Components.md
│   └── Wiring_Diagram/
│
├── Software/
│   ├── Mission_Planner_Setup.md
│   └── Parameters/
│
├── Flight_Test/
│   ├── Logs/
│   └── Results.md
│
└── Documentation/
    └── Images/
```

---

# 👨‍💻 Author

**Sarthak Ruhela**

UAV | Embedded Systems | Computer Vision | Autonomous Systems