Designing my own FPV Stack, it WILL have errors, so do NOT use it in your Drone!

Flight Controller:

- No Analog OSD, made for BetaFPV P1 or optionally Walksnail and DJI
- BEC: 5V 3A; 9V 3A
- IMU (Gyro): ICM-20602
- STM32F405
- Buzzer Pads
- 1 UART free to use e.g. for GPS

ESC Connector Pinout:

| [1]  | [2] | [3]  | [4]  | [5] | [6] | [7] | [8] |
|------|-----|------|------|-----|-----|-----|-----|
| VBAT | GND | CUR  | TEL  | M1  | M2  | M3  | M4  |

VTX Connector Pinout:

| [1] | [2] | [3]  | [4]   | [5] | [6] |
|-----|-----|------|-------|-----|-----|
| 5V  | GND | U1_TX| U1_RX | GND | NC  |


![image](https://github.com/user-attachments/assets/02fa92fd-d398-48e4-8216-80786e9df85d)
<img width="584" height="582" alt="image" src="https://github.com/user-attachments/assets/95b8818a-ba3e-47fb-bd1b-9800295ced86" />
<img width="610" height="625" alt="image" src="https://github.com/user-attachments/assets/ebda9fc6-6bac-4da4-9b9d-f76fffa52b85" />
<img width="957" height="978" alt="image" src="https://github.com/user-attachments/assets/4df28cf1-1bec-48e5-b79f-035111ed15a6" />
<img width="957" height="991" alt="image" src="https://github.com/user-attachments/assets/1c575da3-5469-4c99-a1cd-5d12f89e317c" />




4in1 ESC:
Based on EFM8BB21, FD6288Q and 24 PSMN1R4-40YLDX.
The PCB size is not final yet, it WILL change.
  - Bluejay (Laout A), BLHeli_S compatible
  - Dshot bidirectional compatible
  - Current Sensor: INA168 with a 0.5mOhms shunt
  - LMR14010 10V Buck to provide Gate voltage
  - AP2204K LDO 10V -> 3.3V


<img width="620" height="689" alt="image" src="https://github.com/user-attachments/assets/55224fea-45c3-49e9-b421-0231f3f5e597" />
<img width="646" height="733" alt="image" src="https://github.com/user-attachments/assets/5f0d59b5-1658-475f-b793-8542059c555a" />
<img width="885" height="979" alt="image" src="https://github.com/user-attachments/assets/eab35526-971d-4d9d-8865-9f55a408255b" />
<img width="886" height="1021" alt="image" src="https://github.com/user-attachments/assets/1eff501b-d4e1-49ca-bb0a-cfbdb499e4b7" />



