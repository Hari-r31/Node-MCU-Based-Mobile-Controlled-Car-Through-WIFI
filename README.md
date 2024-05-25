
# NodeMCU Based Mobile Controlled Car Through WIFI

This project enables you to control a car wirelessly using a NodeMCU board and a mobile device connected to the same Wi-Fi network. The NodeMCU board acts as a web server, allowing you to send commands to control the car's movements.

## Prerequisites

- NodeMCU board (ESP8266)
- Motor driver (e.g., L298N)
- DC motors (for the car's movement)
- Wi-Fi network credentials (SSID and password)

## Setup

1. **Hardware Setup**:
   - Connect the NodeMCU board to the motor driver and DC motors according to the pin configurations specified in the code.
  
2. **Software Setup**:
   - Open the provided Arduino sketch file (`NodeMCU_Car_Control.ino`) in the Arduino IDE.
   - Replace `your_SSID` and `your_PASSWORD` with your Wi-Fi network credentials.
   - Upload the sketch to your NodeMCU board.

3. **Control Interface**:
   - Once the NodeMCU is connected to the Wi-Fi network, you can control the car using a web interface.
   - Open a web browser on any device connected to the same Wi-Fi network.
   - Enter the IP address of the NodeMCU board in the address bar.
   - You will see a simple web page with buttons for controlling the car's movements (forward, backward, left, right, stop).
   - Click on the buttons to send commands to the NodeMCU board and control the car accordingly.

## Usage

- Click on the respective buttons on the web interface to control the car's movements.
- The NodeMCU board receives these commands via HTTP requests and activates the corresponding motor pins to control the car.
- You can modify the control logic and interface as needed to suit your project requirements.

## Contributors

- Hari Sai Kumar Thatholu
- Harisaikumar06@gmail.com

Feel free to contribute to this project by submitting pull requests or reporting issues.

---
