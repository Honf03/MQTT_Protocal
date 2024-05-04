
# MQTT Protocal 

This project uses the MQTT protocol to communication between the hardware device and the smartphone. The Arduino acts as the main processing unit for the device, with inputs including the DHT11 sensor and soil moisture sensor, and outputs including the LCD_1602 display and a relay connected to a water pump motor. Additionally, the ESP32 is utilized to send messages to the MQTT broker.

HiveMQ is a data transport platform that is MQTT protocol-based, and I have chosen to utilize it for receiving and sending data between the two devices.


For the smartphone application, I have used MIT App Inventor to create the app.

The device can be controlled via the smartphone app without the need for both devices to be connected to the same network.


