# Experiment 4: Develop an USB-powered gas detector with an LED display using Arduino.

## Setup Instructions
- Nothing to do here.


## Circuit Setup
- Connect the analog output `A0` pin of the MQ-4 smoke sensor to analog pin `A0` on the Arduino Uno.
- Connect the digital output `DO` pin of the MQ-4 smoke sensor to digital pin `10` on the Arduino Uno (Do it only if you want to control LED digitally otherwise disconnect this pin. If you use this, connect LED to digital pin `7`).
- Connect the ground `GND` pin of the MQ-4 smoke sensor to the ground `GND` pin on the Arduino.
- Connect the power `VCC` pin of the MQ-4 smoke sensor to the `5V` pin on the Arduino Uno.