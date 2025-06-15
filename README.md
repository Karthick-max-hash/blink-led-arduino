# blink-led-arduino


This is a basic Arduino project that blinks an LED on and off using digital pin 13. It was built using Tinkercad Circuits for simulation and code testing.

---

## 🚀 What It Does

- Turns an LED ON for 1 second
- Turns it OFF for 1 second
- Repeats the cycle continuously

---

## 🔗 Tinkercad Simulation

You can view and simulate the circuit online here:  
👉 [Open in Tinkercad] <https://www.tinkercad.com/things/hFFdTymmwFy-blinking-led>

---

## 🔌 Circuit Details

| Arduino Pin | Component | Description        |
|-------------|-----------|--------------------|
| D13         | LED (+)   | Long leg of LED    |
| GND         | LED (–)   | Short leg via 220Ω resistor |

---

## 📄 Arduino Code

```cpp
void setup() {
  pinMode(12, OUTPUT);
}

void loop() {
  digitalWrite(12, HIGH);  // Turn LED on
  delay(1000);             // Wait 1 second
  digitalWrite(12, LOW);   // Turn LED off
  delay(1000);             // Wait 1 second
}


##Requirements
Arduino UNO
LED
220Ohm resistor
Jumper wires
Breadboard(optional)
