<p align="left">
  <img src="https://img.shields.io/github/repo-size/HariharanS-22/TurboX2?style=flat"/>
  <img src="https://img.shields.io/github/last-commit/HariharanS-22/TurboX2?style=flat"/>
  <img src="https://img.shields.io/github/issues/HariharanS-22/TurboX2?style=flat"/>
  <img src="https://img.shields.io/badge/License-Custom-darkblue?style=flat"/>
  <img src="https://img.shields.io/badge/Made%20with-ESP32-blue?style=flat&logo=esphome"/>
</p>

# 🚀 TurboX2 – Hybrid Bicopter with Self-Balancing Bot


<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=10umfN6Dcz_4xiwXa5b4UARDC6E-SHyCr" alt="Turbo X2" width="600"/>
</p>

**Turbo X2** is a dual-mode robotic system, combining the vertical flight capabilities of a bicopter with the stability and control of a self-balancing bot. This hybrid robot can switch seamlessly between aerial and ground modes using an RC transmitter (Flysky i6) , making it versatile for real-world terrain and tactical operations.

## 📸 Project Overview

- **Modes**: Aerial (Bicopter) and Ground (Balancing Bot)  
- **Control**: ESP32-based real-time PID control with IMU feedback  
- **Switching**: Remote-controlled via PPM input (FlySky i6)  
- **Simulation**: Self-balancing dynamics simulated using Simulink  
- **Design**: Hybrid frame modeled in SolidWorks  

## 👥 Team & Contributors

Meet the minds behind **TurboX2** – a fusion of creativity, engineering, and innovation:

- 🚀 [**Hariharan**](https://github.com/HariharanS-22) – Systems Architect & Embedded Developer  
- 🛠️ [**Pragadeesh**](https://github.com/pragadeesh-raja) – Mechanical Designer & CAD Modeler    
- 🧠 [**MadhavShankar**](https://github.com/madhav-codes) – Control Systems & PID Tuning Specialist  
- 📡 [**Jagakishan**](https://github.com/jagakishan-dev) – Communications & PPM Integration Expert

## 🔧 Hardware

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1pqOx0gAKF7ZjbxHlEJdzCmSw-QjJL4KW" alt="Hardware Setup" width="535"/>
</p>

<div align="center">

<table>
  <tr>
    <th>Component</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td>ESP32 WROOM</td>
    <td>Main controller</td>
  </tr>
  <tr>
    <td>MPU6050</td>
    <td>IMU for angle and acceleration</td>
  </tr>
  <tr>
    <td>920 kV BLDC Motors</td>
    <td>Aerial thrust</td>
  </tr>
  <tr>
    <td>MG995 Servos</td>
    <td>Thrust vector control</td>
  </tr>
  <tr>
    <td>30A ESCs</td>
    <td>Motor speed control</td>
  </tr>
  <tr>
    <td>200 RPM Johnson Motors</td>
    <td>Ground motion</td>
  </tr>
  <tr>
    <td>L298N Motor Driver</td>
    <td>Drive controller for bot</td>
  </tr>
  <tr>
    <td>11.7V LiPo Battery</td>
    <td>Power source</td>
  </tr>
  <tr>
    <td>FlySky i6 Transmitter</td>
    <td>RC signal input via PPM</td>
  </tr>
</table>

</div>


## 🧠 Features

-  **Seamless Mode Switching**  
  Toggle between bicopter and balancing bot using Channel 6 (PPM-based).

-  **Dual PID Control Systems**  
  - Balancing Bot: Real-time upright stability with MPU6050  
  - Bicopter: Thrust stabilization and yaw control

-  **Serial PID Tuning**  
  Adjust PID constants in real-time via Serial Monitor without code re-upload.

-  **Simulation + CAD Integration**  
  Simulink for behavior testing, SolidWorks for mechanical design validation.

## ⚙️ Circuit Layout

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1T7gHhglWt0NQtGYPnN-itPNp36M5N1lw" alt="Circuit" width="400"/>
</p>



## 🧪 Simulations & Design

- 📐 **Simulink**  
  Inverted pendulum model used to simulate balancing bot dynamics.

- 🛠️ **SolidWorks**  
  Custom hybrid chassis designed to hold both flight and ground components efficiently.

## ⚖️ License

This project is released under a **Custom License**.  See [`LICENSE`](./LICENSE) for more details.

Public viewing is allowed, but **forking and reuse require prior permission**.


