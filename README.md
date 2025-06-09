# Enclosed Automated Hydroponic System

**EET 452W Senior Project — Spring 2022**  
**Farmingdale State College, Department of Electrical Engineering**  
**Contributors**: Xhovani Mali, Joe Cueter, Connor Powers

---

## Overview

This project presents a **cost-effective, enclosed hydroponic system** designed for growing plants without soil, using an automated, Arduino-driven control loop. The system monitors and regulates water levels, pH, humidity, temperature, and lighting, creating an optimal environment for various crops.

The project draws from real-world agricultural needs, embedded systems design, and automation principles to create a viable, affordable solution for urban or personal farming applications.

---

## Features

- **Soilless Cultivation** using nutrient-rich water.
- **Timed LED Growth Lighting**
- **Sensor Integration**: pH, moisture, TDS, temperature.
- **Fully Automated Control Loop** via Arduino.
- **Customizable Plant Profiles** stored for dynamic control.
- **Single Power Supply Design** using relays and MOSFETs.
- **Real-Time Data Logging** through USB and Excel.

---

## System Components

| Component                  | Description                                        |
|---------------------------|----------------------------------------------------|
| Arduino Uno               | Central microcontroller for automation            |
| pH Sensor (Gravity)       | Monitors water acidity                            |
| Soil Moisture Sensor      | Tracks internal humidity                          |
| Grove TDS Sensor          | Measures water quality (Total Dissolved Solids)   |
| Thermistor (Grove)        | Monitors ambient temperature                      |
| Timed LED Strip           | Simulates daylight cycles                         |
| Submersible Water Pump    | Cycles nutrient solution                          |
| Air Pump                  | Maintains oxygenation and water movement          |
| Nutrient Dispenser        | Adds nutrients based on sensor feedback           |
| Relay Module              | Controls high-current components from MCU         |

---

## Architecture

The system follows a **closed-loop feedback control model**:
1. **Sensors** collect environmental data.
2. **Arduino** processes inputs and determines actions.
3. **Relays** actuate pumps and dispensers.
4. **User-defined plant parameters** govern behavior dynamically.
5. **Real-time data streaming** supports monitoring/debugging.

> Inspired by Ebb and Flow systems, with a modular build and low maintenance requirements.

---

## Testing & Results

- Sensor calibration verified via Excel data logging.
- System successfully pumped water based on moisture/pH conditions.
- Relays and MOSFETs configured for AC/DC power control.
- Edge case: missing ground on Arduino → resolved via debugging.
---


## Future Improvements

- Wi-Fi or BLE connectivity for mobile monitoring.
- User-friendly UI for parameter tuning.
- Solar power support for sustainability.
- Modular plant tray support for scaling.

---

## Lessons Learned

- Systems integration under constraints.
- Debugging signal errors in real hardware.
- Balancing cost, complexity, and performance.
- Collaboration under time pressure with multiple engineering roles.

---

## References

- [Hydroponic Market Report (MarketsAndMarkets)](https://www.marketsandmarkets.com/Market-Reports/hydroponic-market-94055021.html)
- [Benefits of Hydroponics](https://greenourplanet.org/hydroponics/benefits-of-hydroponics/)
- [Spruce: Ebb and Flow Hydroponics](https://www.thespruce.com/hydroponic-gardens-ebb-and-flow-systems-1939219)

---

## Contact

Created by [Xhovani Mali](https://www.linkedin.com/in/xhovanimali) — always open to chat about embedded systems
