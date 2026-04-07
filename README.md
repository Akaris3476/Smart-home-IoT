# Smart Home IoT

This repo consists of 3 parts:
* Arduino: sends telemetry(temperature and lighting level) to local hub and has functions to execute songs
* Local hub: reads serial port, communicates with Arduino, processes received data and sends it to Azure IoT Hub
* Backend API: allows users to get telemetry from CosmosDB, can send commands to enable songs on Arduino

