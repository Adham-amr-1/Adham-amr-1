<!-- HEADER BANNER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:f75c7e&height=220&section=header&text=Adham%20Amr%20Mohamed&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Embedded%20Systems%20Engineer&descAlignY=58&descSize=20" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Embedded+Control+Systems;Embedded+IoT+%26+Automotive+Systems;Motor+Control+%7C+Real-Time+Firmware;Network+%26+Light+Current+Engineer&font=Fira+Code&center=true&width=620&height=45&color=f75c7e&vCenter=true&size=22" alt="Typing SVG"/>
</p>

<p align="center">
  <a href="mailto:adhamamrts@outlook.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=microsoftoutlook&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/adham-amr-6aa10221a/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://t.me/Adhooom_1"><img src="https://img.shields.io/badge/Telegram-Message-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/></a>
  <a href="https://github.com/Adham-amr-1?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Graduation%20Project-93%25%20Excellent-success?style=flat-square"/>
  <img src="https://img.shields.io/badge/MIE%202026-Finalist-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Experience-2%2B%20Years-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-brightgreen?style=flat-square"/>
</p>

---

## 👋 About Me

I am a fresh graduate **Embedded Systems Engineer** (Communication and Electronics Engineering, Helwan University, 2026) with 2+ years of hands-on work in firmware and R&D on **STM32, AVR and ESP32**. I build bare-metal drivers, real-time control loops and IoT systems, and I test them on real hardware.

| | |
|---|---|
| 🎯 **Fields** | Embedded Systems · Embedded Control Systems · Embedded IoT · Automotive Systems |
| 🏢 **Now** | Network and Light Current Engineer at Future Smart System, Cairo |
| 🚗 **Built** | AI-enhanced Adaptive Cruise Control (led a 4-member team) |
| 🎓 **Trained** | Embedded Linux (Yocto), AVR, IoT Diploma, AI (NTI), Wireless IoT (ITI) |
| ☕ **Fun fact** | My perfect day starts and ends with a cup of coffee |

---

## 🚀 Featured Project: AI-Enhanced Adaptive Cruise Control

A dual-layer embedded ACC system validated on real hardware and aligned with **ISO 15622:2018** and **ISO 26262:2018**.

```mermaid
flowchart LR
    A[Camera] --> B[Object and Lane Detection]
    B --> C[Kalman Filter Sensor Fusion]
    C --> D["MPC Controller<br/>Raspberry Pi 5 (OSQP)"]
    D -- "Custom 8-byte UART" --> E["PID Controller<br/>ESP32"]
    F[Quadrature Encoder] --> E
    E --> G[MCPWM Motor Drive]
    D --> H[Telemetry and FOTA]
```

<table>
  <tr>
    <td width="50%">

**🧠 Optimization layer (Raspberry Pi 5)**
- MPC model derived from first principles
- OSQP solver with hard safety constraints
- Object detection, lane detection, sensor fusion

    </td>
    <td width="50%">

**⚙️ Actuation layer (ESP32)**
- Tustin-discretized PID with anti-windup clamping
- MCPWM output with quadrature encoder feedback
- Modular C++ OOP driver library for sensors and control

    </td>
  </tr>
</table>

**Features:** automatic speed control · cut-in braking · lane curvature monitoring · remote telemetry · FOTA updates

🏆 Finalist graduation team, Made in Egypt (MIE) Competition 2026

<a href="https://github.com/DriveX-Innovation/AI-Enhanced_ACC_with_Integrated_Telemetry_and_FOTA"><img src="https://img.shields.io/badge/View%20Repository-f75c7e?style=for-the-badge&logo=github&logoColor=white"/></a>

---

## 🔧 More Projects

<table>

### ⚡ BLDC Sinusoidal PWM
STM32 Cortex-M4, Embedded C. SPWM drive with smoother torque and lower acoustic noise than trapezoidal control.

[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github)](https://github.com/Adham-amr-1/Control-BLDC-Sinusoidal_PWM)

### 🔁 BLDC Trapezoidal PWM
STM32 Cortex-M3, Embedded C. 6-step commutation with reliable startup and stable operation under varying load.

[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github)](https://github.com/Adham-amr-1/Control-BLDC-Trapezoidal_PWM)


### 🚙 Autonomous RC Car
AVR ATmega32, Embedded C. Obstacle avoidance with GPIO, timer-based ultrasonic sensing and PWM motor control. Verified in Proteus and on hardware.

[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github)](https://github.com/Adham-amr-1/Embedded-RC-Car-Updated-Version)

### 📡 Multi-Directional Distance Detection
One MCU controlling multiple ultrasonic sensors with optimized processing and GPIO usage.

[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github)](https://github.com/Adham-amr-1/Multi_Ultrasonic_in_one_MC)

</table>

---

## 💼 Experience

### 🏢 Network and Light Current Engineer | Future Smart System (Aug 2026 to Present)
- Install and configure **Access Control Systems** and **CCTV Systems**
- Build networks on site: cabling, connections and device configuration
- Program **routers, switches and Raspberry Pi** to match client requirements
- Set up advertising screens connected to cameras
- Disassemble, repair and upgrade PCs and laptops, including part replacement

### 🤖 Robotics Coach | WiroPlus (Dec 2024 to Jan 2026)
- Delivered electronics and robotics curricula to **50+ students**, with 4+ hardware projects per semester
- Increased student engagement by **~25%** through project-based learning

### 🏎️ Electric and Embedded Systems Member | E-Rally (Oct 2024 to Sep 2025)
- Bare-metal STM32 firmware with PWM and GPIO drivers for an EV rally motor drive
- 6-step commutation, verified with oscilloscope measurements and signal tracing

### 🌐 R&D Volunteer and RAS Project Supervisor | IEEE Helwan (Sep 2023 to Sep 2025)
- Led firmware projects at IEEE events and mentored participants across Egypt
- Supervised student teams building firefighting robots and sensor automation in C and Arduino

<details>
<summary><b>🏧 Earlier: ATM Maintenance Technician | Raya IT (Internships 2022 and 2023)</b></summary>

- Maintained and repaired 20+ ATM machines, diagnosing board-level, component-level and firmware faults
- Trained and guided 5+ junior technicians during field operations

</details>

---

## 🛠 Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=c,cpp,python,matlab,bash,linux,git,github,docker,vscode,raspberrypi,arduino&theme=dark" />
</p>

| Area | Skills |
|------|--------|
| **Microcontrollers** | STM32 (Cortex-M3/M4) · AVR ATmega32 · ESP32 (ESP-IDF) · Arduino |
| **Firmware** | Bare-metal · HAL design · Peripheral drivers · Interrupts · Timers · ADC · PWM · FreeRTOS |
| **Embedded Linux** | Device drivers · Yocto · Linux system programming · Raspberry Pi 5 |
| **Protocols** | UART · SPI · I2C · MQTT · HTTP · Wi-Fi · Bluetooth |
| **Control** | BLDC control · PID · MPC (OSQP) · Power electronics |
| **Standards** | ISO 26262 · ISO 15622 |
| **Tools** | STM32CubeIDE · ESP-IDF · Proteus · MATLAB/Simulink · KiCad · Oscilloscope · Logic Analyzer |
| **Field skills** | Access Control · CCTV · Structured Cabling · Router and Switch Config · PC Hardware Repair |

---

## 🌱 Currently Learning

<p>
  <img src="https://img.shields.io/badge/PCB%20Design-in%20progress-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Secure%20IoT%20Projects-in%20progress-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AutoCAD%20Electrical-in%20progress-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/CAN%20Bus-in%20progress-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/IoT%20Diploma-ongoing-blueviolet?style=for-the-badge"/>
</p>

---

## 🏆 Awards

- 🥇 Finalist Graduation Team, Made in Egypt (MIE) Competition, Jul 2026
- 🏎️ Best Electric Sub-Team Member of the Month, E-Rally, Jul 2025
- 🌟 Best R&D Volunteer First Phase S'25, IEEE HSB, Oct 2024
- 🤖 2nd Place and Best Code, Sumo-Robot Competition, Dec 2023

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Adham-amr-1&show_icons=true&theme=radical&hide_border=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Adham-amr-1&layout=compact&theme=radical&hide_border=true" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Adham-amr-1&theme=radical&hide_border=true" />
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Adham-amr-1&theme=react-dark&hide_border=true" width="95%"/>
</p>

---

## 📫 Let's Work Together

Open to junior **embedded, firmware and automotive** roles. I am also available for network and light current projects.

<p align="center">
  <a href="mailto:adhamamrts@outlook.com"><img src="https://img.shields.io/badge/Email%20Me-D14836?style=for-the-badge&logo=microsoftoutlook&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/adham-amr-6aa10221a/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Adham-amr-1&style=for-the-badge&color=f75c7e" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f75c7e,50:203a43,100:0f2027&height=120&section=footer" width="100%"/>
