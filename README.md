# Indoor Air Quality and Garbage Monitoring System

Healthy indoor Environments System of Smart Commercial Buildings Using Masked Authenticated Messaging (MAM) of the IOTA protocol.

## Indoor Air Quality Monitoring System v1

The project consists of 3 files and must be executed on the Raspberry Pi:
- sensor.js: Simple test between the Raspberry Pi board and the DHT11 humidity sensor. 
- mam_sensor.js: The DHT11 sensor data is read and published to the Tangle using MAM.
- mam_receive.js: Extract the stored data from the Tangle using MAM and display the data.

## Indoor Air Quality Monitoring System v2

The project consists of 5 files:
- sensorArduino.ino: This code is to capture the data of the three sensors: DHT11 humidity and temperature sensor, MQ-2 LPG gas sensor, and MQ-7 CO gas sensor. This file and it´s libraries are located in the Arduinosensor folder.
- listportsArduino.js: It shows us the available ports of the Arduino UNO board.
- sensorArduino.js: The DHT11, MQ-2 and MQ-7 sensors data are read and displayed.
- mam_sensorArduino.js: The DHT11, MQ-2, and MQ-7 sensors data are read and published to the Tangle using MAM.
- mam_receiveArduino.js: Extract the stored data from the Tangle using MAM and display the data.

## Garbage Monitoring System

The project consists of 3 files:
- trashcan.ino: This code is to capture the data of the SRF05 sensor. This file is located in the trashcan folder
- nodemcu_mqtt_mam.js: The SRF05 sensor data are read and published to the Tangle using MAM.
- nodemcu_mam_receive.js: Extract the stored data from the Tangle using MAM and display the data.
