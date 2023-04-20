# Software Specification for ESP8266 Telegram Bot Message Trigger

## Overview
The objective of this software is to trigger a message to be sent via a Telegram bot when movement is detected using an IR sensor connected to an ESP8266 microcontroller. The system will use a specific Telegram bot to send messages to designated users. The system should be designed to be easily configurable, allowing the user to customize various settings such as the Telegram bot token, chat ID, and sensor sensitivity.
## Requirements
### Hardware Requirements
- ESP8266 microcontroller
- IR sensor
- Breadboard or PCB for circuit prototyping
- Wires for connections
### Software Requirements
- Arduino IDE (version 1.8.15 or later)
- ESP8266 Board Manager (version 2.7.4 or later)
- ArduinoJson library (version 6.18.5 or later)
- Telegram API
## System Architecture
The system will consist of the ESP8266 microcontroller connected to an IR sensor. When movement is detected by the IR sensor, the ESP8266 will send a message via a Telegram bot to designated users.


## Testing