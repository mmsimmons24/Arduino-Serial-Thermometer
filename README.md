# Arduino-Serial-Thermometer
This Arduino Uno Rev3 microcontroller will read the current room temperature using a MCP9700 temperature sensor IC, and display it in the Arduino IDE serial monitor window.
Credit to startingelectronics.org for the project idea and schematic.
## Components:
* 1 Arduino Uno Rev3 Microcontroller Or Compatible Board (Buy It From: https://store-usa.arduino.cc/products/arduino-uno-rev3?selectedStore=us)
* Arduino IDE Software (https://www.arduino.cc/en/software)
* 1 USB Type-B Cable
* 1 800 Tie Point Breadboard (400 Tie Point / Half-Size Can Be Used)
* 2 100n Non-polarized Capacitors (C1 and C2 on the schematic)
* 1 MCP9700 Linear Active Thermistor IC (U1 on the schematic)
* Jumper Wires / Wire Links (Male-to-Male)
## Building the Circuit:
* (I recommend having the schematic and images pulled up alongside the instructions, as it will be easier to follow along)
* Insert the MCP9700 into the breadboard as shown in the images provided
* Insert C1 into the breadboard by connecting one leg to VOUT, leaving the other leg not connected to anything (for now)
* Insert C2 into the breadboard by connecting one leg to the unconnected leg of C1, leaving the other leg not connected to anything (for now)
* With a wire link or jumper wire, connect VDD to the unconnected leg of C2 (green wire link in images)
* With a wire link or jumper wire, connect GND to the negative strip on the power rail (yellow wire link in images)
