# Send data from IoT devices

Data received by IoT hub is stored in the form of JSON documents called **Device twins**. **Device twins** are JSON documents that store device state information including metadata, configurations, and conditions. Azure IoT Hub maintains a device twin for each device that you connect to IoT Hub.


## Creating and connecting sensor devices

1. You can create new devices using the **Azure IoT Node.js SDK**. The code for the 3 sensors: **moisture_sensor**, **soil_sensor** and **temperature sensor** can be found [here](./code/sensors/).

2. The **deviceConnectionString** variable in line 17 of each file should be set to the respective primary connection strings.

3. Please do note that it is **crucial** to keep the connection strings private. If you want to share this code publicly then please use an [environment variable](https://en.wikipedia.org/wiki/Environment_variable#:~:text=An%20environment%20variable%20is%20a,in%20which%20a%20process%20runs.)

4. Use the following command to run the code samples and send data to your IoT hub.
`node <filename>`

## Overview of the data sent by the sensors

### Temperature sensor

| **Data**              | *Description*                        |
| ----------------------------- | --------------------------------------------------------------------- |
| **Temperature** | *The temperature recorded by the sensor in Celsius*|

### Moisture sensor

| **Data**              | *Description*                        |
| ----------------------------- | --------------------------------------------------------------------- |
| **Humidity** | *Relative humidity in %*|
| **Rainfall** | *Amount of rainfall over a period of time in mm*|

### Soil sensor

| **Data**              | *Description*                        |
| ----------------------------- | --------------------------------------------------------------------- |
| **Nitrogen** | *Ratio of Nitrogen content in soil*|
| **Phosphorus** | *Ratio of Phosphorous content in soil*|
| **Potassium** | *Ratio of Potassium content in soil*|
| **pH** |  *ph value of the soil*|

Now that we can send data to the hub, we can move onto learning [how to extract the data.](./4-extract-data-from-IoT-hub.md)
