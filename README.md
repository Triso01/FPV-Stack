Note:
  Designing my own FPV Stack, it WILL have errors, so do NOT use it in your Drone!
  The 4 in 1 ESC will be continued later, I don not have the experience to finish it yet.
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

ESCs:
Based on EFM88B21, FD6288 and PSMN1R4-40YLDX.
  - Bluejay (Layout A), BLHeli_S compatible
  - Dshot bidirectional

<img width="1665" height="1103" alt="image" src="https://github.com/user-attachments/assets/bf539ac3-1e6f-46c2-8df4-b04c4e2060f5" />
<img width="1004" height="1028" alt="image" src="https://github.com/user-attachments/assets/2f4bb294-4d52-4ce5-b6f7-dd154d7c89fd" />
<img width="595" height="915" alt="image" src="https://github.com/user-attachments/assets/ee599d2b-b64c-4e09-8b0a-3f4d7016ce60" />
<img width="772" height="1034" alt="image" src="https://github.com/user-attachments/assets/d8b385d6-878d-4705-b879-7fcaa9624515" />
<img width="586" height="920" alt="image" src="https://github.com/user-attachments/assets/4e06024a-95bd-42e9-b338-4f85c3afe31e" />

ESC distribution board:
10V Buck, 3,3V LDO and the ampmeter

<img width="1682" height="1150" alt="image" src="https://github.com/user-attachments/assets/db60be26-f4ce-484b-8443-52aec6242ec7" />
<img width="1393" height="1200" alt="image" src="https://github.com/user-attachments/assets/74cd6e27-873b-4b8a-b57e-195bceefee8b" />
<img width="1347" height="1208" alt="image" src="https://github.com/user-attachments/assets/891c05cf-ec29-4131-bbb6-71624fa22584" />
<img width="1345" height="1201" alt="image" src="https://github.com/user-attachments/assets/c8f3d0ea-838a-43b0-8c44-21e1876569fa" />
<img width="1401" height="1212" alt="image" src="https://github.com/user-attachments/assets/85441016-78fc-4269-abc8-b97e6d8267e0" />



[Will be finished, when I have more experience]:
4in1 ESC:
Based on EFM8BB21, FD6288Q and 24 PSMN1R4-40YLDX.
The PCB size is not final yet, it WILL change.
  - Bluejay (Laout A), BLHeli_S compatible
  - Dshot bidirectional compatible
  - Current Sensor: INA168 with a 0.5mOhms shunt
  - LMR14010 10V Buck to provide Gate voltage
  - AP2204K LDO 10V -> 3.3V
(You can see "pictures" when opening the PCB Files with KiCad)


Now the expensive things (duhhh):

PCBs:
<img width="1534" height="794" alt="image" src="https://github.com/user-attachments/assets/fa026ec6-8ed2-4e17-a240-8ec0853c7238" />

Parts:
1. Select the columns like this
2. Click "Create BOM"
<img width="1499" height="921" alt="Bildschirmfoto 2026-09-21 um 22 52 28" src="https://github.com/user-attachments/assets/c3568974-c09d-41dd-9552-13fafc309793" />

3. Click on "Add to Cart"
<img width="1375" height="1022" alt="image" src="https://github.com/user-attachments/assets/56a1acbb-66d6-4fd9-8db6-033a1b2a1f35" />

