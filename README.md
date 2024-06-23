# ESP-32-RC-Surveillance-Car-with-Object-Detection

## Pin connections:

| L298N | ESP32 |
| ----- | ----- |
| ENA   | IO2   |
| IN1   | IO12  |
| IN2   | IO13  |
| IN3   | IO27  |
| IN4   | IO26  |
| ENB   | IO2   |

| Pan Servo    | ESP32          |
| ------------ | -------------- |
| BROWN (GND)  | (POWER-GND)    |
| RED (5V)     | (POWER-SUPPLY) |
| ORANGE (PWM) | IO14           |

| Tilt Servo   | ESP32          |
| ------------ | -------------- |
| BROWN (GND)  | (POWER-GND)    |
| RED (5V)     | (POWER-SUPPLY) |
| ORANGE (PWM) | IO15           |

| L298N | LEFT-MOTOR                 |
| ----- | -------------------------- |
| OUT3  | Left-sides of both motors  |
| OUT4  | Right-sides of both motors |

| L298N | RIGHT-MOTOR                        |
| ----- | ---------------------------------- |
| OUT1  | Left-sides of both motors          |
| OUT2  | Right-sides of both motors       k |
