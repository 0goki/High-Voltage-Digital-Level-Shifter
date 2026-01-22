# High Voltage Digital Level Shifter

<img width="1200" height="836" alt="sm_black_top" src="https://github.com/user-attachments/assets/35cbbdf6-8c85-434f-909e-3500baba582c" />

An ESP32-based microcontroller with an opto-isolated level shifter designed to take up to 3 separate 5V TTL signals and output up to 12 channels of digital signals at 5-24V without signal inversion. The 12-channel output is also configured with flyback diodes and an isolated ground to serve as a solenoid driver with support for 12 separate solenoids with a total power draw of 24V at 5A.

Designed for Aerotech gantry systems running Automation1 and wired for Position Synchronized Output (PSO).

## Breakout/Daughterboards

<img width="1200" height="237" alt="sm_white_top" src="https://github.com/user-attachments/assets/46c673bb-b144-46be-9756-3017a54b88fc" />

PCB has built-in pogo pin connections to support various breakout/daughterboard options.

[Github page to H-Bridge breakout board.](https://github.com/0goki/-HVDLS-HBridge)

## Bill of Materials

Interactive BOM

[Digikey BOM](http://www.digikey.com/short/v1b47t42)

## Revisions

| Mainboard | Notes |
| ------------- | ------------- |
| MB01202026  | First physical production run. KICAD Nightly 9.99 |

| Breakout | Notes |
| ------------- | ------------- |
| BO01162026 | First physical production run. KICAD Nightly 9.99 |
