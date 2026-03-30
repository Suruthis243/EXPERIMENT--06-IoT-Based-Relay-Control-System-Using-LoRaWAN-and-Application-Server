# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## NAME : SURUTHI S
## REG NO: 212224220114
## DATE : 09/03/2026
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection

### AT+FDR
<img width="1228" height="631" alt="image" src="https://github.com/user-attachments/assets/bcb47cc8-c5c9-4733-a1e8-1d1cff7e8075" />

### AT+NJM
<img width="1328" height="670" alt="image" src="https://github.com/user-attachments/assets/e53bf9ce-28fb-4be8-ba4f-bd0185d9a0b2" />


### AT+ADR

<img width="747" height="381" alt="Screenshot 2026-03-30 184345" src="https://github.com/user-attachments/assets/fef0fa67-214d-4b63-8947-57f0ef586750" />

### AT+TDC
<img width="677" height="335" alt="Screenshot 2026-03-30 185140" src="https://github.com/user-attachments/assets/baf615b2-503d-4c62-9e5f-04b540c0e02f" />

### AT+CLASS

<img width="827" height="420" alt="Screenshot 2026-03-30 185533" src="https://github.com/user-attachments/assets/15d7cedd-f7b6-40e2-afe9-79ed8111bb83" />


### AT+DEUI

<img width="890" height="442" alt="Screenshot 2026-03-30 190531" src="https://github.com/user-attachments/assets/4801715c-9531-46a2-8f15-01ddac2dbf92" />

### AT+APPEUI

<img width="838" height="370" alt="Screenshot 2026-03-30 191235" src="https://github.com/user-attachments/assets/45a09d87-cf6d-4532-9fd2-fcf857eb92a6" />


### ATZ

<img width="880" height="445" alt="Screenshot 2026-03-30 191736" src="https://github.com/user-attachments/assets/909063f0-8955-4ed2-9d4d-9fc6002ac17d" />



### 2. Network Server – Recent Events

<img width="1919" height="1124" alt="Screenshot 2026-03-19 175456" src="https://github.com/user-attachments/assets/a1d20d9d-00ea-468e-af36-f2a7a071ddc7" />

<img width="1903" height="1128" alt="Screenshot 2026-03-19 175430" src="https://github.com/user-attachments/assets/42df72a1-056e-4645-9c27-48478986f348" />



### 3. Dashboard Command Sending

<img width="1733" height="676" alt="image" src="https://github.com/user-attachments/assets/2ae95ce5-335a-405c-9261-b9c0bb4584f5" />




<img width="1919" height="997" alt="Screenshot 2026-03-19 175539" src="https://github.com/user-attachments/assets/b437fdda-677e-4847-967b-403959626225" />


### 4. Relay Status Dashboard Output
### Bulb ON → Relay ON  

<img width="422" height="416" alt="image" src="https://github.com/user-attachments/assets/d006b339-51ef-4888-8b3c-fac79b97b339" />

### Bulb OFF → Relay OFF
<img width="642" height="894" alt="image" src="https://github.com/user-attachments/assets/b9cb50b9-e10f-4262-9e5e-80b56f7e09e7" />


## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
