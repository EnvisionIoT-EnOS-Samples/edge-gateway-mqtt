# enos-edge-gateway-mqtt

## Introduction
This is the sample codes to simulate an edge gateway, authenticate to its associated subdevice and batch post measurement point using enos-mqtt-sdk-nodejs SDK only.


## Techology stack
- NodeJS
- EnOS Platform
- https://github.com/EnvisionIot/enos-device-sdk-nodejs/tree/master/packages/enos-mqtt-sdk

## Prerequitsites

### Get the device broker url and port, save to .env file
Follow the instructions below to get the device broker url and port:
- https://www.envisioniot.com/docs/enos/en/latest/getting_started_with_enos/planning.html?highlight=environment%20information#getting-environment-information

### Create an edge gateway product and device, save the edge product, edge gateway key and secret to .env file
Follow the instructions below to create an edge gateway product and device. Use EnOS_Edge_Standard_Model when associating the product with a model.
- https://www.envisioniot.com/docs/device-connection/en/latest/howto/device/manage/creating_product.html
- https://www.envisioniot.com/docs/device-connection/en/latest/howto/device/manage/creating_device.html

### Create a product and subdevice, save the product, subdevice key and secret to .env file
Follow the instructions below to create a product and subdevice.
- https://www.envisioniot.com/docs/device-connection/en/latest/howto/device/manage/creating_product.html
- https://www.envisioniot.com/docs/device-connection/en/latest/howto/device/manage/creating_device.html

### Associate the subdevice to the edge gateway
Follow the instructions below to create an edge gateway product and device:
- https://www.envisioniot.com/docs/device-connection/en/latest/howto/device/manage/managing_devices.html#adding-sub-devices-to-a-gateway-device

## How to run
To run the demo, run the following command in a new terminal.
```bash
node index.js
```
