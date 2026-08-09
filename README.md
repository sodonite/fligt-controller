Flight Controller
This is a custom flight controller engineered specifically for rocket stabilization and control. Powered by an STM32F722 microcontroller, it incorporates an ICM-45686 IMU alongside a BMP580 barometer, with an integrated microSD card slot dedicated to flight telemetry logging. The board supports 2S LiPo battery configurations featuring onboard charging functionality, as well as dedicated PWM output channels for servo actuation.

Designed in KiCad, the entire project is completely open source.

PCB:<img width="371" height="488" alt="image" src="https://github.com/user-attachments/assets/9676677e-f571-4e0e-9c3a-19242fe02fea" />
3D Image:<img width="452" height="581" alt="image" src="https://github.com/user-attachments/assets/0807d444-c123-4ac9-8128-19c4b004c9cc" />
<img width="466" height="616" alt="image" src="https://github.com/user-attachments/assets/f4064c92-67aa-47a0-b086-8fb80246945c" />
Schematic:<img width="889" height="561" alt="image" src="https://github.com/user-attachments/assets/82fcc713-342e-4948-aab7-0edb141dc195" />
<img width="859" height="493" alt="image" src="https://github.com/user-attachments/assets/ff77705b-2ccb-49a4-87ce-129ed83273d2" />
Technical Specifications
Brain: STM32F722RET6 microcontroller.
IMU: ICM-45686 high-precision motion sensor.
Barometer: BMP580 altitude tracker.
Actuation: Multi-channel servo output via PWM.
Data Logging: Onboard MicroSD card slot.
Power Management:
BQ25883: 2-cell LiPo battery charger via USB-C.
TPS63070: 5V Buck-Boost regulator for servos.
LMR51430: 3.3V Buck regulator for the MCU and sensors.
D2: RGB LED (Common Anode) — Visual status indicator for system initialization, ready-to-fly state, and critical error reporting (IMU, battery, SD card, and power rails).




