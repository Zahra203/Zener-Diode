# Zener-Diode
A simple electronics project demonstrating how a **Zener diode** can be used as a **voltage regulator** to maintain a constant output voltage, even when the input voltage varies.   The project was simulated in **Proteus** and implemented as a hardware prototype.
---

## 📜 Introduction

The **Zener diode** acts as a shunt voltage regulator by operating in reverse bias.  
Any excess current that does not go to the load is shunted through the Zener, which clamps the voltage to its rated value.

In this project, an **8V Zener diode** was used to regulate output voltage between **9V and 14V inputs**.

---

## 🎯 Objective

Construct a working model of a voltage regulator using an **8V Zener diode** and demonstrate its voltage-stabilizing capability.

---

## 🛠️ Materials Required

- Zener diode (8V)
- Battery (voltage source)
- Breadboard
- Resistors:
  - 100 kΩ (load resistor)
  - 1 kΩ (current limiting resistor)
- Voltmeter
- Connecting wires
- **Software:** Proteus

---

## 📋 Prerequisites

- Zener diode must be connected in **reverse bias**.
- A **current limiting resistor** should be placed in series with the Zener diode.

---

## ⚙️ Procedure

1. Simulated the circuit in **Proteus**.
2. Used an **8V Zener diode** to maintain constant voltage.
3. Connected a **1 kΩ resistor** in series with the Zener diode and a **100 kΩ load resistor** in parallel.
4. Wired the battery such that:
   - Positive terminal → Negative terminal of Zener
   - Negative terminal → Positive terminal of Zener
5. Measured the output voltage using a voltmeter while varying the input voltage.

---

## 📊 Output

| Applied Voltage | Output Voltage |
|-----------------|----------------|
| 9V              | 8V             |
| 11V             | 8V             |
| 13V             | 8V             |
| 14V             | 8V             |

---

## 📐 Circuit Diagrams

- **Proteus Simulation**
- **Hardware Prototype**

*(Add images/screenshots here)*

---

## 📝 Conclusion

The **Zener diode** effectively regulated voltage to a constant **8V** regardless of input voltage changes.  
This demonstrates the principle of shunt voltage regulation and the practical use of Zener diodes in electronic circuits.

---

## 💡 Skills Demonstrated

- Applied Electronics
- Circuit Design & Simulation
- Voltage Regulation Techniques
- Zener Diode Operation
- Hardware Prototyping
- Electrical Measurements

---

