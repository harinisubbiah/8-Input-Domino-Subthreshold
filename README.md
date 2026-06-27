# 8-Input Domino OR Gate in Subthreshold Region
---
# 📖 Overview

As CMOS technology continues to scale, minimizing power consumption has become one of the most important challenges in modern integrated circuit design. Operating digital circuits in the **sub-threshold** and **near-threshold** regions significantly reduces energy consumption, making these techniques ideal for battery-powered and energy-constrained applications.

This project presents the design and implementation of an **8-input Domino OR gate** using **Dynamic CMOS Logic** in **Cadence Virtuoso**. The circuit is designed to operate under sub-threshold conditions, demonstrating the trade-off between power consumption, propagation delay, and switching performance.

Simulation results validate the effectiveness of Domino Logic for implementing wide fan-in digital circuits while maintaining low power dissipation.

---

# 🎯 Objectives

- Design an 8-input Domino OR gate
- Implement the circuit using Dynamic CMOS Logic
- Operate the design in the Sub-Threshold region
- Evaluate propagation delay
- Measure average power consumption
- Compare performance with conventional CMOS logic
- Analyze switching threshold and device sizing

---

# ✨ Features

- ⚡ Ultra-Low Power Design
- 🧠 Wide Fan-In Domino Logic
- 📉 Sub-Threshold CMOS Operation
- 📊 Power Analysis
- ⏱️ Delay Analysis
- 🔬 Device Sizing Optimization
- 💻 Cadence Virtuoso Implementation
- 📈 Dynamic CMOS Evaluation

---

# 🏗️ Design Flow

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/557a52be-834b-4795-beaf-6873c0af3f5c" />

---

# ⚙️ Domino Logic Architecture

The implemented circuit consists of:

- Precharge PMOS transistor
- Evaluation NMOS transistor
- Dynamic evaluation network
- Static CMOS inverter
- Clock-controlled operation

During the **precharge phase**, the dynamic node is charged HIGH.

During the **evaluation phase**, the pull-down network conditionally discharges the dynamic node based on the OR logic inputs.

The output inverter restores a full rail-to-rail logic level while enabling cascading of multiple Domino Logic stages.

---

# 💻 Technology Used

| Category | Technology |
|-----------|------------|
| Design Tool | Cadence Virtuoso |
| Technology Node | GPDK 180 nm |
| Logic Family | Domino Logic |
| Design Style | Dynamic CMOS |
| Supply Voltage | 0.35 V |
| Simulation | Analog Design Environment (ADE) |

---
# 🔬 Schematic
<img width="1327" height="617" alt="schematic" src="https://github.com/user-attachments/assets/23be3626-0af4-4279-9ddd-ac7d73e0cd89" />

Major design blocks include:

- Dynamic evaluation network
- Clocked PMOS precharge transistor
- NMOS evaluation transistor
- CMOS output inverter
- Wide fan-in pull-down network

Special attention was given to transistor sizing to improve switching characteristics while maintaining ultra-low power operation.

---

# 📈 Key Findings

- Successfully implemented an 8-input Domino OR gate operating in the sub-threshold region.
- Demonstrated significant reduction in power consumption compared to conventional operating regimes.
- Verified the feasibility of wide fan-in Domino Logic for ultra-low power applications.
- Observed the expected power-delay trade-off associated with sub-threshold operation.
- Improved switching behavior through transistor sizing optimization.

---


# 👨‍💻 Contributors

- S. Deepika Sri -[https://github.com/SDeepikaSri]
- A. Mirunalini -[[https://github.com/miruanand]

---

# 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Authors
**Harini S**
---
