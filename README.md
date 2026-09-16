# RaceESC
Custom 2S ESC (for ~1/10 scale RC cars) with I2C, TCS, ABS and more! RaceESC is a compact, lightweight, 40A capable esc  with an I2C connector for other projects (telemetry, etc). This esc will support two way communication with a host microcontroller over i2c, 
allowing telemetry to be shared with it. The ESC will run am32 firmware, with traction control and abs built in, however connecting to a host MCU with an IMU, or a standalone I2C IMU, the ESC can more accurately react to slips using a PID controller.

Features:
- Super compact design (~27x25x10mm)
- High power and efficiency (Low RDS fets, High gate drive voltage, etc)
- 5V/3A integrated BEC
- JST SH I2C connector
- Regular 3 pin wire connector
- Super optimal phase layout
- TCS, ABS, Telemetry
- More to come (software-side)


CAD:
- Simple 2 part enclosure held together with 4 M2x10mm screws
- looks super cool



<img width="613" height="589" alt="CAD" src="https://github.com/user-attachments/assets/e313463c-4ae9-483d-b8ac-e9458d1f49c3" />


Wiring Diagram:
Front:


<img width="613" height="589" alt="Top side wiring diagram" src="https://github.com/user-attachments/assets/a781df4f-d5a6-4790-98a0-1715633f9ebe" />
Back:


<img width="613" height="589" alt="Bottom side wiring diagram" src="https://github.com/user-attachments/assets/01927186-27c0-4c1c-b4d3-2fb928d1cbfb" />





[![View PCB on KiCanvas](https://hack.club/pcb-badge)](https://kicanvas.org/?repo=https://github.com/<OWNER>/<REPOSITORY>/tree/main/pcb)
