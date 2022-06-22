# Send data from IoT devices

Data received by IoT hub is stored in the form of JSON documents called **Device twins**. **Device twins** are JSON documents that store device state information including metadata, configurations, and conditions. Azure IoT Hub maintains a device twin for each device that you connect to IoT Hub.


## Creating and connecting sensor devices

1. You can create new devices using the **Azure IoT Node.js SDK**. The code for the 3 sensors: **moisture_sensor**, **soil_sensor** and **temperature sensor** can be found [here](./code/).

2. The **deviceConnectionString** variable in line 17 of each file should be set to the respective primary connection strings.

3. Use the following command to run the code samples and send data to your IoT hub.
`node <filename>`