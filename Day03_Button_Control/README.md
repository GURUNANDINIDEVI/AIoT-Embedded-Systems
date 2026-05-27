# Day 03 - Push Button Controlled LED

## Objective
To design and simulate a push button controlled LED system using Arduino in Tinkercad.

---

## Components Used
- Arduino Uno
- Breadboard
- LED
- Push Button
- 220Ω Resistor
- 10kΩ Resistor
- Jumper Wires

---

## Circuit Connections

### LED Connection
| Component | Arduino Pin |
|------------|-------------|
| LED Positive Leg | Pin 13 |
| LED Negative Leg | Resistor → GND |

---

### Push Button Connection
| Component | Arduino Pin |
|------------|-------------|
| Push Button | Pin 2 |
| Other Button Side | 5V |
| Pull-down Resistor | GND |

---

## Working Principle

The Arduino continuously reads the push button state from digital pin 2.

- When the button is pressed:
  - Pin 2 becomes HIGH
  - LED turns ON

- When the button is released:
  - Pin 2 becomes LOW
  - LED turns OFF

The project demonstrates digital input handling and conditional logic in embedded systems.
