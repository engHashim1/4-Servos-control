# 4-Servos-control
This project uses an Arduino to control 4 servo motors by sweeping them back and forth between 0° and 180°. Each servo is connected to a different PWM pin, and the movement is synchronized using the Servo library.
🔧 4 Servo Motor Control with Arduino

📦 Components Required

    Arduino Uno (or compatible board)

    4x Servo Motors (e.g., SG90 or MG90S)

    External 5V power supply (recommended)

    Jumper wires

    Breadboard (optional)

🖥️ Code Overview

    Includes the Servo.h library

    Attaches each servo to a separate PWM-capable pin

    Sweeps all servos together from 0° to 180°, then back

    Uses delay() for smooth motion

⚙️ Wiring
Servo	Arduino Pin
1	D9
2	D10
3	D11
4	D12

Image in TinkerCad
![لقطة شاشة 2025-07-06 191300](https://github.com/user-attachments/assets/79c19ef1-4bc3-47d4-906d-4930ce49f411)


    ⚠️ Note: Do not power all servos directly from the Arduino. Use an external power supply (5V, 2A or more).

    Schematic:
    ![لقطة شاشة 2025-07-06 191243](https://github.com/user-attachments/assets/252abef6-c4c4-446a-846d-98e04a516eab)

    

📂 How to Use

    Connect the servos to the Arduino as described.

    Upload the code using Arduino IDE.

    Observe the servos sweeping in sync.

📜 License

This project is open-source and free to use under the MIT License.
