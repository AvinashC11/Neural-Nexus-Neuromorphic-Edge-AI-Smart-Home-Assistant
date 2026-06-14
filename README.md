# Neural-Nexus-Neuromorphic-Edge-AI-Smart-Home-Assistant

# BioPulse: Neuromorphic Edge AI for Ultra-Low Power Smart Living

> **Hackathon Track:** Smart Infrastructure / Sustainability & Edge AI
> **Tagline:** Mimicking biological neural efficiency to redefine smart home automation at microwatt scales.

---

## 💡 The Problem & The Solution

### The Problem
Traditional smart home automation frameworks rely on a **continuous polling architecture**. Sensors constantly stream data to an edge processor or cloud backend, forcing CPUs to remain in high-power active states. This causes:
* Excessive background power draw (vampire power).
* Massive data clutter from redundant, unchanged environmental states.
* Vulnerability to privacy breaches by pushing granular, raw household telemetry to the cloud.

### Our Solution (`BioPulse`)
`BioPulse` introduces a **Neuromorphic Event-Driven Architecture** built directly on bare-metal microcontroller hardware. Instead of constantly crunching numbers, the system treats each environmental sensor as an **artificial neuron with an integrated leak-and-fire dynamic**. 

Small environmental fluctuations are passively leaked away. Only when local physical variations create an accumulation of "membrane potential" (Event Spikes) does the neuromorphic layer calculate a composite **Network Action Potential**. If this potential crosses an dynamically adjusted threshold, it wakes the onboard **Deterministic AI Decision Engine** to fuse context, log anomalies, and take instant corrective actions via localized actuators.

---

## 🛠️ Key Features & Innovation Points

*   🧠 **Neuromorphic Leak-and-Fire Accumulators:** Eliminates standard looping conditions. Sensors only report state changes when their mathematical "charge" builds up faster than its decay rate.
*   📈 **Adaptive Homeostasis (Self-Learning):** The system tracks ambient baseline averages across localized temporal windows, shifting its trigger thresholds autonomously between day, night, and active cooking/sleeping phases.
*   🌐 **Zero-Cloud Edge Privacy:** 100% of the digital signal processing, sensor fusion, and anomaly isolation runs locally on a sub-$3 microcontroller. Zero bytes of data leave the room.
*   ⚡ **True Event-Driven Emulation:** Keeps system peripherals and deep-analytical logic clock-gated until a biological-style spike forces an operational wake-up call.

---

## 🏗️ Tech Stack
*   **Hardware Platform:** Arduino UNO Core (ATmega328P architecture)
*   **Emulation & Prototyping:** Autodesk Tinkercad Environment
*   **Firmware Language:** Bare-metal Embedded C / C++ (Optimized No-Library Matrix Fusion)
*   **Sensing Array:** Analog Gas (MQ135), Digital Infrared Motion (PIR), Analog Thermistor, Photo-resistor (LDR)
*   **Actuation Suite:** Micro Servo (Ventilation/Locking), Low-Side Driven Relay, Piezo Buzzer, Diagnostic LEDs

---

## 📂 Project Structure
