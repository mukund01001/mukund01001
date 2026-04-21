<div align="center">

# ⚡ Mukund Rathi
### B.Tech ECE · IIIT Kottayam · CGPA 8.3
#### VLSI · Computer Architecture · Embedded IoT · AI/ML on Hardware

<p align="center">
  <a href="https://www.linkedin.com/in/mukund-rathi" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:rathimukund.01@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/mukund01001" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://www.hackerrank.com/profile/rathimukund_01" target="_blank">
    <img src="https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black"/>
  </a>
</p>

---

*"Bridging silicon and intelligence — from RTL to real-world deployment."*

</div>

---

## 🧭 About Me

I'm an **Electronics & Communication Engineering** undergraduate at **IIIT Kottayam**, working at the intersection of **VLSI design, computer architecture, and intelligent embedded systems**. I architect hardware accelerators in Verilog/HLS, validate them with industry-standard EDA flows, and deploy ML on edge SoCs — from RTL to silicon-level verification.

Currently researching **Hardware AI Accelerators and FPGA/VLSI design** at the **I²CS Research Lab** under Dr. Kala S, with hands-on experience across the full ASIC/FPGA design stack: RTL design → functional simulation → DFT → synthesis → post-synthesis validation.

---

## 🏆 Highlights

| Award | Event | Year |
|---|---|---|
| 🥇 **Winner** (1 of 460+ teams) | DVCon India 2025 — FPGA-Based AI Accelerator Design Contest | Aug 2025 |
| 🥈 **Rank 5** (of 252 finalists / 1356+ participants) | AI-Powered FPGA Design & Simulation Hackathon — NIT Jamshedpur | Dec 2025 |
| 🤖 **Regional Finalist** | NXP AIM India 2025 — Autonomous Warehouse Navigation Challenge | Jul 2025 |
| 🎓 **Samsung Fellowship** | ISWDP — Selected from 2,700+ applicants | Feb 2025 |
| 🔬 **SRIP 2025 Selectee** | 200 selected out of 7,000 applicants — IIIT Bangalore | May 2025 |
| 💡 **SIH Finalist** | Smart India Hackathon 2024 — IoT Landslide Detection | Aug 2024 |
| ⭐ **5-Star Gold Badge** | HackerRank Python (Highest Rank) | Jun 2024 |

---

## 🛠️ Technical Stack

### VLSI & Digital Design
```
RTL / HDL          : Verilog, SystemVerilog, Vitis HLS, MATLAB HDL Coder
Verification       : UVM, SVA, Constrained-Random Verification (CRV), Functional Coverage
DFT / Test         : Scan-Based DFT, ATPG, Fault Analysis (Atalanta, Fault tool)
EDA Tools          : Synopsys VCS / Design Compiler / Verdi · Cadence Genus / Modus
                     Xilinx Vivado · Mentor QuestaSim · ModelSim · LTSpice
Open-Source EDA    : OSS-CAD-SUITE (Yosys, Icarus Verilog)
Interfaces         : AXI4-FULL, AXI4-Lite, BRAM, Pipelining, Loop Unrolling
```

### Computer Architecture & FPGA
```
Architectures      : RISC-V (bare-metal), ARM Cortex, Custom Accelerator Design
Acceleration       : Tiled Matrix Multiplication, MCA Engines (II=1), BRAM Tiling
SoC Integration    : AXI Interconnect, Bare-Metal Drivers, RTL-to-Bitstream Flow
Programming        : Embedded C, RISC-V Assembly, GCC Toolchain, QEMU, GNU Debugger
```

### Embedded Systems & IoT
```
Platforms          : Arduino, ESP32, Raspberry Pi, ARM Cortex-M
Protocols          : MQTT, I2C, SPI, UART, Zigbee, Interrupt Handling, RTOS basics
Cloud IoT          : AWS IoT Core, Azure IoT Hub
Scripting          : Python, Bash, Shell Scripting, Tcl, Linux (Ubuntu, Raspbian)
```

### AI / ML & Data Science
```
Frameworks         : TensorFlow, Scikit-learn, NumPy, Pandas, Matplotlib
Models             : Transformers (DistilBERT), U-Net, YOLO, Prophet, Isolation Forest
ML for Hardware    : RTL Feature Engineering, Post-Synthesis Timing Prediction, SHAP/LIME
Explainability     : Ensemble Learning, 46 Engineered RTL Features, R² ≈ 0.94
Anomaly Detection  : Time-Series Forecasting, Sensor Spoofing Simulation
```

### Robotics & Visualization
```
Robotics           : ROS2, Nav2, Gazebo Simulation, Foxglove Studio
Vision             : YOLO Object Detection, QR Code Recognition, OpenCV
3D Visualization   : Streamlit, three.js, Digital Twin Dashboards
Developer Tools    : Git, Docker, VS Code, GCP, MongoDB, React, Node.js
```

---

## 💼 Experience

### 🔬 Summer Research Intern — IIIT Bangalore (CEEMS Lab & NCL)
**Guided by Dr. Jyotsna Bapat, Dr. Sasirekha, Dr. Vinod · May – July 2025 · Bengaluru, KA**

- Engineered a **full-stack Embedded IoT & Digital Twin platform** for smart campus water management — Python backend ingesting live data from **24 meters via 3 DCUs** using MQTT and I2C.
- Deployed **ML models** (Prophet + Isolation Forest) for automated leak detection, anomaly alerting, and predictive water-demand forecasting on time-series sensor data.
- Built an interactive **3D Digital Twin dashboard** (Streamlit + three.js) with real-time floor-plan overlays, graphical popups, and virtual valve actuation simulation.
- Engineered **attack & anomaly simulators** to stress-test robustness against spoofing, replay, clogging, sensor freeze, and missing-data scenarios using synthetic packet generators.

---

## 🚀 Projects

### 🥇 [FPGA-Based AI Accelerator on RISC-V SoC](https://github.com/mukund01001/FlowTransformer_Quantization_Analysis)
`DVCon India 2025 Winner — 1st of 460+ teams · Feb 2025 – Dec 2025`

> *Full hardware acceleration of a Transformer-based NIDS on a RISC-V SoC.*

- **Accelerator Design:** Tiled matrix-multiplication accelerator in **Verilog / Vitis HLS** targeting QKV & FFN layers of a Transformer — pipelined MCA engines (II=1), loop unrolling, partitioned BRAM for high data reuse.
- **SoC Integration:** Mapped onto **Vega AT1051 RISC-V SoC** via three parallel **AXI4-FULL** channels + unified **AXI-Lite** control plane; developed bare-metal C driver; full RTL simulation, synthesis, and post-synthesis validation flow.
- **Results:** ~2.4 GOPS throughput · **7× latency reduction** · **2000× matmul speedup** · **80× end-to-end MHA speedup** vs. CPU baseline using burst AXI + BRAM tiling.

---

### 🥈 [AI-Powered FPGA Design — RTL Timing Prediction](https://github.com/mukund01001)
`Rank 5 / 1356+ participants — NIT Jamshedpur VLSI FOR ALL Hackathon · Nov 2025 – Jan 2026`

> *ML pipeline to predict post-synthesis critical-path delay directly from RTL.*

- Engineered **46 RTL features** (logic depth, fanout, LUT utilisation, etc.) across 20+ designs (adders, FIFOs, FSMs, multipliers).
- Achieved **3.28% MAPE, R² ≈ 0.94** using ensemble learning; applied **SHAP/LIME** explainability to identify logic depth and fanout as the primary timing drivers.

---

### 🤖 [Warehouse Treasure Hunt & Object Recognition](https://github.com/mukund01001)
`NXP AIM India 2025 Regional Finalist · July 2025`

> *Autonomous warehouse navigation robot built on ROS2.*

- Built a **ROS2 + Nav2** autonomous navigation stack with **YOLO** object detection, QR code recognition, and shelf localization inside a Gazebo-simulated warehouse.
- Implemented custom shelf-detection logic, recovery behaviors, and heuristic exploration; visualized with **Foxglove Studio**; achieved on-time completion of all challenge objectives.

---

### 📡 [IoT-Driven Landslide Detection & Alert System](https://www.linkedin.com/in/mukund-rathi)
`Smart India Hackathon 2024 Finalist · Sept 2024`

- Deployed real-time landslide monitoring using **Arduino + MPU6050 (accel/gyro) + Soil Moisture Sensor** with ML classification for early evacuation alerts in disaster-prone zones.

---

### 🌕 [Crater & Boulder Detection — Lunar Exploration (ISRO Hackathon)](https://www.linkedin.com/in/mukund-rathi)
`Bharatiya Antariksh Hackathon · Aug 2024`

- Automated detection of craters/boulders in ISRO OHRC lunar images using **U-Net + YOLO** (TensorFlow + OpenCV); generated **GIS-compatible shapefiles** for mission planning.

---

### ☁️ [Microsoft Azure IoT Hub Application](https://github.com/mukund01001)
`May 2024`

- Raspberry Pi simulator streaming temperature/humidity telemetry to **Azure IoT Hub**; data stored to CSV and visualized with Excel line & area charts.

---

## 📜 Certifications & Courses

| Certificate | Issuer | Date |
|---|---|---|
| TTTC 3-Day Hands-On Workshop on VLSI Test (DFT, ATPG, Scan) | IEEE Computer Society (TTTC), C2S | Jan 2026 |
| RISC-V Bare-Metal Programming Foundations | VLSI System Design (VSD) | Jun 2025 |
| VLSI System on Chip Design | Maven Silicon | Feb 2025 |
| MicroPython for Beginners | National Institute of Electronics & IT | Mar 2025 |
| Python (Advanced) | Kaggle | Jun 2024 |
| MATLAB Onramp / HDL Coder | MathWorks | Jul 2024 |
| Software Engineering Simulation | Goldman Sachs (Forage) | 2024 |

---

## 🔬 Research & Leadership

### I²CS Research Lab — IIIT Kottayam *(Jan 2025 – Present)*
Researching **Hardware AI Accelerators** and FPGA/VLSI design under **Dr. Kala S** (Lab Head).
- Attended hands-on workshop on **Digital Design Flow** using Synopsys EDA tools (VCS, Verdi, Design Compiler).
- Participated in and **hosted** a workshop on **MATLAB HDL Coder & FPGA Implementation** with MathWorks.

### Placement & Training Cell — IIIT Kottayam *(Jul 2024 – Aug 2025)*
Contacted **450+ companies** for campus placements via LinkedIn and email campaigns; coordinated multiple campus drives.

### Elix (Electronics Club) — Tech & PR Lead *(Sep 2024 – Aug 2025)*
- Led talks and hands-on sessions on **VLSI & Embedded Systems**; boosted event participation by **4× via PR campaigns**.

### Chitrachaya — Photography & Cinematography Club Lead *(Nov 2023 – Present)*
Managing a **team of 50+ photographers/videographers** covering every campus event; community of 250+ members.

### Volunteering
- **IEEE ICITIIT-2024** — Assisted in managing 300+ authors and professionals at international conference.
- **PETA India** *(Jul 2020 – Mar 2021)* — Community animal rescuer and PR volunteer during COVID.

---

## 📊 GitHub Stats

<div align="center">

![Mukund's GitHub Stats](https://github-readme-stats.vercel.app/api?username=mukund01001&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mukund01001&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

</div>

---

<div align="center">

**📫 Let's collaborate on VLSI, Hardware Accelerators, Embedded IoT, or AI-on-Edge projects!**

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mukund-rathi)
[![Email](https://img.shields.io/badge/Send%20an%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rathimukund.01@gmail.com)

</div>
