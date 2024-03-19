# Arduino-Serial-Thermometer
This Arduino Uno Rev3 microcontroller will read the current room temperature using a MCP9700 temperature sensor IC, and display it in the Arduino IDE serial monitor window.
Credit to https://startingelectronics.org for the project idea and schematic.
<img src="https://github.com/mmsimmons24/Arduino-Serial-Thermometer/main/serial_thermometer_images_and_videos/circuit1.JPG" />
## Components:
* 1 Arduino Uno Rev3 Microcontroller Or Compatible Board (Buy It From: https://store-usa.arduino.cc/products/arduino-uno-rev3?selectedStore=us)
* Arduino IDE Software (https://www.arduino.cc/en/software)
* 1 USB Type-B Cable
* 1 800 Tie Point Breadboard (400 Tie Point / Half-Size Can Be Used)
* 2 100n Non-polarized Capacitors (C1 and C2 on the schematic)
* 1 MCP9700 Linear Active Thermistor IC (U1 on the schematic)
* Jumper Wires / Wire Links (Male-to-Male)
## Building the Circuit:
(I recommend having the schematic and images pulled up alongside the instructions, as it will be easier to follow along)
* Insert the MCP9700 into the breadboard as shown in the images provided
* Insert C1 into the breadboard by connecting one leg to VOUT, leaving the other leg not connected to anything (for now)
* Insert C2 into the breadboard by connecting one leg to the unconnected leg of C1, leaving the other leg not connected to anything (for now)
* With a wire link or jumper wire, connect VDD to the unconnected leg of C2 (green wire link in images)
* With a wire link or jumper wire, connect GND to the negative strip on the power rail (yellow wire link in images)
* With a wire link or jumper wire, connect the row where C1 and C2 are connected to the negative strip on the power rail (red wire link in images)
* With a jumper wire, connect the negative strip on the power rail to the GND pin on the Arduino board (black jumper wire in images)
* With a jumper wire, connect the row where VDD and C2 are connected to the 5V pin on the Arduino (red jumper wire in images)
* With a jumper wire, connect VOUT to the A0 pin on the Arduino (blue jumper wire in images)
* Lastly, connect the Arduino to the computer via USB cable 
### Connecting the Arduino to Computer
Click this link if you do not know how to set up your Arduino to your computer https://docs.arduino.cc/software/ide-v2/tutorials/getting-started-ide-v2/
## Operating the Circuit: 
After verifying and uploading the code to the Arduino, open the serial monitor window in the Arduino IDE. The temperature will be displayed and it will update at just about every second. Applying heat to the MCP9700 sensor will cause the temperature to increase and it will display in the serial monitor. 
