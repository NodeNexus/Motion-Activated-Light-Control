# ⚙️ Motion Activated Light Control

This project automatically turns on a light when motion is detected using a PIR sensor.  
Ideal for smart corridors, washrooms, or energy-saving automation setups.

---

## ⚙️ Components
| Component | Quantity |
|------------|-----------|
| Arduino Uno | 1 |
| PIR Sensor | 1 |
| LED / Relay | 1 |
| Jumper Wires | As required |

---

## 🧠 Working Principle
- The PIR sensor detects infrared radiation emitted by moving bodies.  
- Arduino reads the signal from the sensor.  
- When motion is detected, Arduino turns on the LED or activates a relay.  
- After motion stops, it automatically turns off the light.

---

## 🔌 Circuit Connections
| Arduino Pin | Connected To |
|--------------|--------------|
| D7 | PIR OUT |
| D8 | LED / Relay IN |
| 5V, GND | Power Supply |

---

## 💻 Usage
1. Upload the `motion_light.ino` code.  
2. Open Serial Monitor to see “Motion detected!” messages.  
3. Adjust PIR sensitivity and delay using onboard potentiometers.

---

## 🌟 Features
- Simple & cost-effective automation  
- No manual switch required  
- Great for energy conservation  

---

## 🔮 Future Improvements
- Add LDR to prevent activation during daylight  
- Integrate with IoT to monitor activity logs  

---

**Developer — NodeNexus (Vaishnav Balpande)**
