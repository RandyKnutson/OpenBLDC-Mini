# OpenBLDC-Mini v1.0

An open-source, AI-assisted 3-phase motor controller for learning, research, and small vehicles.

**Project Lead:** Randy  
**Coach / AI design partner:** GPT-5  
**License:** CERN-OHL-S v2 (strongly reciprocal open-hardware license)

---

## 🌟 Overview
OpenBLDC-Mini is a 24–48 V, 1–2 kW field-oriented motor controller designed for accessibility and safety.  
It showcases how AI can accelerate hardware design—schematics, firmware, and documentation are all co-developed openly.

---

## ⚙️ Key Specs
| Parameter | Target |
|------------|---------|
| Supply voltage | 24–48 V DC |
| Continuous current | 40–60 A |
| MCU | **STM32G431** (Cortex-M4, FPU, 170 MHz) |
| Gate driver | **DRV8353RS** (3-phase, current sense) |
| Power stage | 6 × 80 V N-MOSFETs, ~5 mΩ |
| Control | FOC with current & speed loops |
| Comms | UART (debug) + CAN (expansion) |
| Protections | OVP, UVP, OCP, OTP |
| Firmware | STM32CubeIDE / HAL |
| PCB size | ~70 × 70 mm, 2-layer prototype |

---

## 🧩 Repository Structure
