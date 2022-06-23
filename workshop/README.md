# Predicting harvest cycles

## Goals

In this workshop, we will discuss **about the complexities of agriculture and make a simple prediction about the optimum time to harvest crops**.

| **Goal**              | *Predicting the optimum time to harvest crops using ML models trained by data captured by IoT devices*                        |
| ----------------------------- | --------------------------------------------------------------------- |
| **What you'll need** | *[Azure subscription](https://azure.microsoft.com/en-in/), latest version of [Node.js](https://nodejs.org/en/) and a [Github account](https://github.com/)*|
| **Duration** | *1 hour* |
| **Microsoft Cloud Topics taught** | *Azure IoT Hub, Azure ML* |
| **Slides** | [Powerpoint](slides.pptx) |

## Video

Embed your Train the Trainer video here. Instructions on how to create a great video experience is [available on this page](../video-guidance.md).

## Pre-Learning

- [Introduction to Azure IoT Hub](https://docs.microsoft.com/en-gb/learn/modules/introduction-to-iot-hub/?WT.mc_id=Portal-Microsoft_Azure_Marketplace)
- [Azure Machine Learning](https://docs.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-machine-learning)
- [Resource Groups](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal)

## Prerequisites

- [Azure](https://azure.microsoft.com/en-in/) account
- [Nodejs](https://nodejs.org/en/download/)

## What students will learn

**According to the United Nations Food and Agriculture Organization, over three-quarters of the food humans consume comes from just 12 plants and five animal sources, with just three crops — wheat, rice, and corn — accounting for 51% of the calories consumed in the diet.**

**With the increasing use of harmful fertilizers and global warming, harvest cycles have become harder to predict**

In this workshop, we try to understand what factors affect the growth cycle of a crop and work with sensors which are frequently used to gather data about everything from the pH value of the soil to the temperature.

We will use this data to make a simple prediction about the optimum harvest time.

## Get setup by provisioning the necessary resources on Azure.

In this segment, you will create a resource group and provision the necessary resources in it.

[Manage Azure resource groups by using the Azure portal](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal)

## Add and connect IoT devices to your hub

In this segment, we will create IoT devices and understand the different authentication methods used by IoT hub to connect to the IoT devices.

[IoT concepts and Azure IoT Hub](https://docs.microsoft.com/en-us/azure/iot-hub/iot-concepts-and-iot-hub)

## Send data from IoT devices for analysis

In this segment, we will create a sensor using the Node.js SDK and send data to our IoT hub.

[Quickstart: Send telemetry from an IoT Plug and Play device to Azure IoT Hub](https://docs.microsoft.com/en-us/azure/iot-develop/quickstart-send-telemetry-iot-hub?toc=%2Fazure%2Fiot-hub%2Ftoc.json&bc=%2Fazure%2Fiot-hub%2Fbreadcrumb%2Ftoc.json&pivots=programming-language-nodejs)

## Extract data from hub

In this segment, we will create a route and an endpoint for the telemetry messages sent by our IoT devices.

[Use IoT Hub message routing to send device-to-cloud messages to different endpoints](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-devguide-messages-d2c)

## Develop a model and make a prediction

In this segment, we will create datasets using the files stored in the containers of the Azure Blob Storage and use it to predict harvest times.

[Create data assets](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-create-register-data-assets?tabs=CLI)

## Feedback

Be sure to give [feedback about this workshop](https://forms.office.com/r/MdhJWMZthR)!

[Code of Conduct](../CODE_OF_CONDUCT.md)
