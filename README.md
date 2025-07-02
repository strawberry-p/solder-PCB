## Function
This is a PCB that converts a binary number input into a single logic high line on the output. It can be used to drive a stepper motor with less MCU pins.
## Images
### Schematic
<img width="478" alt="solder_schematic" src="https://github.com/user-attachments/assets/f57331a2-931e-4f55-ac7f-21dd2e64f1e8" />
The schematic has an unpopulated section of an additional layer. Since the solder kit doesn't have this many transistors and I lacked PCB space, I decided to use hex inverter ICs (which I can get for cheap) for the same inverter->inverter function.

I decided to make my own symbol for the IC (according to the datasheets) so that I don't mess up the wiring:
![Inverter IC symbol](https://github.com/user-attachments/assets/d2c80c7a-6f64-4b9a-b53e-7902a9605078)

## PCB
<img width="408" alt="finished_pcb" src="https://github.com/user-attachments/assets/4582aa74-3897-4093-b4bd-259a111520a5" />
The PCB has a lot of broken out pins for the single-line output. It also has LEDs for easier testing, and footprints for the ICs I will buy myself.
