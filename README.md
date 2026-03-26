# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
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

<img width="1364" height="713" alt="image" src="https://github.com/user-attachments/assets/6a3a8d82-f5d5-4e87-872b-884412373409" />

<img width="1364" height="716" alt="image" src="https://github.com/user-attachments/assets/61f66f2a-391d-4453-8006-2f3ed0753269" />



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
