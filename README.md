# Arduino Remote Sensor Vehicle

Obstacle-avoidance vehicle built with Arduino Uno, Adafruit Motor Shield v2, and HC-SR04 ultrasonic sensor.

The vehicle detects obstacles via ultrasonic distance measurement and adjusts motor direction automatically — no remote control required.

**Built:** 2023  
**Stack:** Arduino C · Adafruit MotorShield v2 · I2C · HC-SR04 ultrasonic sensor

---

## How it works

- HC-SR04 measures distance to obstacles continuously
- If distance > 10cm → motors run forward
- If distance < 10cm → motors stop and reverse to avoid collision
- Motor speed and direction controlled via Adafruit Motor Shield over I2C

---

## Hardware

- Arduino Uno
- Adafruit Motor Shield v2
- HC-SR04 ultrasonic sensor
- 2x DC motors

---

*Early embedded hardware project. Current work focuses on FPGA security acceleration for post-quantum cryptography



