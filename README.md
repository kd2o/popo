<div align="center">



# HASEM Team

### WRO Future Engineers

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#license)
[![Competition](https://img.shields.io/badge/Competition-WRO%20Future%20Engineers-orange)](#challenge)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)](#challenge)

</div>

<p align="center">
  <a href="#challenge">About</a> •
  <a href="#team">Team</a> •
  <a href="#bom">Bill of Materials</a> •
  <a href="#power-consumption">Power Consumption</a> •
  <a href="#robot-design">3D Printed Components</a> •
  <a href="#field-randomizer">Field Randomizer & Simulator</a> •
  <a href="#license">License</a>
</p>

---

<a id="challenge"></a>
## About the Competition

**WRO Future Engineers** is a category within the **World Robot Olympiad (WRO)**, an international robotics competition. It is a self-driving car challenge in which students aged 14 to 19 design, build, and program a model car equipped with electromechanical components — sensors, cameras, and microcontrollers — to autonomously navigate a track and avoid obstacles, without any remote control or human intervention.

### Challenges

| Challenge | Description |
|:---|:---|
| **Open Challenge** | The car completes a set number of laps around the track fully autonomously. |
| **Obstacle Challenge** | The car must avoid colored pillars (red and green) and perform additional tasks such as parallel parking. |

### Evaluation Criteria

Teams are evaluated on:

- Vehicle performance on the track
- Engineering documentation (design process, code, decisions)
- Judges' interview (explaining design choices and problem-solving approach)

---

<a id="team"></a>
<div align="center">

## Team Members

</div>

 </div> <h3>Rayna Rino</h3><img src="other\gif\IMG_6704.gif" width="390" align="right" alt="Rayna Rino"><p><b>Age:</b> 14</p><p><b>Email:</b> rinoorayan14@gmail.com</p><p><b>School:</b> British Scientific School</p><p><b>GitHub:</b> <a href="https://github.com/rayanrinoo">rayanrinoo</a></p><br clear="right"/> <hr> <h3>Othman Jaber</h3><img src="other\gif\IMG_6708.gif" width="390" align="right" alt="Othman Jaber"><p><b>Age:</b> 17</p><p><b>Email:</b> othmanjaber78@gmail.com</p><p><b>School:</b> King Talal Secondary School</p><p><b>GitHub:</b> <a href="https://github.com/othmanjaber">othmanjaber</a></p><br clear="right"/> <hr> <h3>Yazan Hindia</h3><img src="other\gif\IMG_6707.gif" width="390" align="right" alt="Yazan Hindiyeh"><p><b>Age:</b> 14</p><p><b>Email:</b> yazanhindia@gmail.com</p><p><b>School:</b> Mahmoud Darwish School</p><p><b>GitHub:</b> <a href="https://github.com/kd2o">kd2o</a></p><br clear="right"/> 
<hr>
<a id="bom"></a>
<div align="center">

## Bill of Materials

</div>

<table width="100%">
    <thead>
        <tr>
            <th width="25%" align="left">Component</th>
            <th width="30%" align="center">Image</th>
            <th width="45%" align="left">Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><b>Raspberry Pi 5 (8GB)</b></td>
            <td align="center"><img src="other/use/raspberry-pi-5-2gb.webp" alt="Raspberry Pi 5" width="160"></td>
            <td>Main processing unit of the robot; handles high-level control, vision processing, and communication with other components.</td>
        </tr>
        <tr>
            <td><b>Raspberry Pi 5 Active Cooler</b></td>
            <td align="center"><img src="other/use/images (2).jpg" alt="Active Cooler" width="160"></td>
            <td>Active cooling fan and heatsink that keep the Raspberry Pi 5 running at safe temperatures under heavy load.</td>
        </tr>
        <tr>
            <td><b>Arduino Uno</b></td>
            <td align="center"><img src="other/use/515b4656ce395f8a38000000.png" alt="Arduino Uno R3" width="160"></td>
            <td>Microcontroller board used for low-level tasks such as motor control and reading sensor data in real time.</td>
        </tr>
        <tr>
            <td><b>Byte Robot Chassis Kit</b></td>
            <td align="center"><img src="other/use/S03e04229601a4569920aa8a3ce73634eD.jpg_960x960.avif" alt="Robot Chassis" width="160"></td>
            <td>Structural frame of the robot that holds all electronic and mechanical components together.</td>
        </tr>
        <tr>
            <td><b>GA25-370 DC Motor with Encoder</b></td>
            <td align="center"><img src="other/use/images (1).jpg" alt="DC Motor with Encoder" width="160"></td>
            <td>Geared DC motor with a built-in encoder, used to drive the wheels and measure rotation for precise movement.</td>
        </tr>
        <tr>
            <td><b>US-100 Ultrasonic Sensor</b></td>
            <td align="center"><img src="other/use/US-100-1.jpg" alt="Ultrasonic Sensor" width="160"></td>
            <td>Ultrasonic distance sensor used for obstacle detection and avoidance.</td>
        </tr>
        <tr>
            <td><b>Pixy2</b></td>
            <td align="center"><img src="other/use/71F2k2oBIfS.jpg" alt="Vision Sensor" width="160"></td>
            <td>Smart vision sensor capable of color and object detection, used to identify targets.</td>
        </tr>
        <tr>
            <td><b>BNO080</b></td>
            <td align="center"><img src="other/use/images.jpg" alt="IMU Sensor" width="160"></td>
            <td>9-axis IMU sensor providing orientation, rotation, and motion data for stabilization and navigation.</td>
        </tr>
        <tr>
            <td><b>Chassis Assembly Diagram</b></td>
            <td align="center"><img src="other/use/download.jpg" alt="Chassis Diagram" width="160"></td>
            <td>Reference diagram showing how the chassis components are assembled together.</td>
        </tr>
    </tbody>
</table>

---

<a id="power-consumption"></a>
<div align="center">

## Power Consumption

</div>

<table width="100%">
    <thead>
        <tr>
            <th align="left">Component</th>
            <th align="center">Voltage</th>
            <th align="center">Current (typ.)</th>
            <th align="center">Power</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Raspberry Pi 5 (8GB)</td>
            <td align="center">5 V</td>
            <td align="center">~1.0–3.0 A</td>
            <td align="center">~5–15 W</td>
        </tr>
        <tr>
            <td>Raspberry Pi 5 Active Cooler</td>
            <td align="center">5 V</td>
            <td align="center">~0.10 A</td>
            <td align="center">~0.5 W</td>
        </tr>
        <tr>
            <td>Arduino Uno</td>
            <td align="center">5 V (7–12 V input)</td>
            <td align="center">~0.05 A</td>
            <td align="center">~0.25 W</td>
        </tr>
        <tr>
            <td>GA25-370 DC Motor with Encoder (×2)</td>
            <td align="center">6–12 V</td>
            <td align="center">~0.30–0.50 A (each)</td>
            <td align="center">~1.8–6 W (each)</td>
        </tr>
        <tr>
            <td>US-100 Ultrasonic Sensor</td>
            <td align="center">5 V</td>
            <td align="center">~15 mA</td>
            <td align="center">~0.075 W</td>
        </tr>
        <tr>
            <td>Pixy2 Camera</td>
            <td align="center">5 V</td>
            <td align="center">~140 mA</td>
            <td align="center">~0.7 W</td>
        </tr>
        <tr>
            <td>BNO080 IMU</td>
            <td align="center">3.3 V</td>
            <td align="center">~15 mA</td>
            <td align="center">~0.05 W</td>
        </tr>
    </tbody>
</table>

---

<a id="robot-design"></a>
<div align="center">

## 3D Printed Components

### Main Robot Design (Modified from Base Kit)

<img src="other/3d/لقطة شاشة 2026-07-18 030156.png" width="600" alt="Main Robot Assembly Overview">

</div>

The updated robot chassis integrates custom 3D-printed brackets and enclosures designed to securely mount the essential processing and sensing hardware.

<table width="100%">
    <thead>
        <tr>
            <th width="30%" align="left">Component</th>
            <th width="30%" align="center">Preview</th>
            <th width="40%" align="left">Purpose</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><b>Raspberry Pi 5 Enclosure</b></td>
            <td align="center"><img src="other/3d/لقطة شاشة 2026-07-18 025954.png" width="180" alt="Raspberry Pi 5 3D Case"></td>
            <td>A protective case tailored for the Raspberry Pi 5, ensuring stable housing on the chassis while maintaining passive ventilation and full access to the GPIO headers and peripheral ports.</td>
        </tr>
        <tr>
            <td><b>US-100 Ultrasonic Sensor Mount</b></td>
            <td align="center"><img src="other/3d/لقطة شاشة 2026-07-18 025702.png" width="180" alt="US-100 Ultrasonic Sensor Bracket"></td>
            <td>A custom front bracket built specifically to secure the US-100 ultrasonic sensor. It isolates the sensor from chassis vibrations and positions it at an optimal angle for precise obstacle distance mapping.</td>
        </tr>
        <tr>
            <td><b>Pixy2 Camera Enclosure</b></td>
            <td align="center"><img src="other/3d/لقطة شاشة 2026-07-18 025622.png" width="180" alt="Pixy2 Camera Case"></td>
            <td>A dedicated mounting case for the Pixy2 smart vision sensor, protecting the camera board while locking its field of view forward for reliable color-signature tracking.</td>
        </tr>
      <td><b>aktb ant</b></td>
      <td align="center"><img width="180" src="other\3d\omg.png"></td>
      <td>omg bde anam</td>
    </tbody>
</table>

---

<a id="field-randomizer"></a>
<div align="center">

## Field Randomizer & Simulator

<img src="other\لقطة شاشة 2026-07-18 041722.png" width="600" alt="Field Randomizer & Simulator Preview">

</div>

The idea behind this project is a **Field Randomizer & Simulator**, a simulation and indirect generation tool designed for the **World Robot Olympiad (WRO) — Future Engineers category** to help teams and coaches adapt and practice high-level tasks.

<div align="center">

**[Try the Field Randomizer & Simulator](https://wro-future-engineers-randomizer.ai.studio/)**

</div>

---

<a id="license"></a>
<div align="center">

## License

</div>

This project is licensed under the **MIT License**.

```
Copyright (c) 2026 HASEM

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

<div align="center">

<sub>© 2026 HASEM — WRO Future Engineers</sub>

</div>
