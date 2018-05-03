# Connecting to Azure IoT Hub

The Telstra Cat-M1 Development Board is capable of using the MQTT protocol to connect directly to an Azure IoT Hub.

* Please refer to this [article](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-create-through-portal)  to learn how to create a unit of Azure IoT Hub
* Please refer to this [article](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-mqtt-support#using-the-mqtt-protocol-directly) to learn about how to connect to connect to the public device endpoints of IoT Hub using the MQTT protocol on port 8883. Understand how to configure values to send in the CONNECT packet.

> Note: I have modified the [IoT_POP_Test.ino](https://github.com/faister/TIC2018/blob/master/TELSTRA%20-%20RELEASE%20LIBRARIES%20AND%20EXAMPLES%2005.04.2018/TEL-IOT5%20-%20Arduino%20PRE-RELEASE%20LIBRARIES%20AND%20EXAMPLES%2005.04.2018/Telstra%20Examples/3.%20MQTT%20Validation/IoT_POP_Test/IoT_POP_Test.ino) to make things easier for you to just enter your values in the respective placeholder.
