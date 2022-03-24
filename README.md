# Awesome IoT Central [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Useful resources for creating solutions with [IoT Central](https://aka.ms/iotcentral) that make you say "Wow, this is amazing!"

## guidance
- [iot-central-integration-guide](https://github.com/iot-for-all/iot-central-integration-guide) - integration patterns and samples for using IoT Central as part of your overall IoT architecture
- [iot-central-aad-setup](https://github.com/iot-for-all/iot-central-aad-setup) - guidance on setting up an Azure Active Directory application to work with IoT Central 

## learning paths
- [companion-experiences-learning](https://github.com/iot-for-all/companion-experiences-learning) - walks through building companion experiences with IoT Central 
- [device-observability-onthe-edge](https://github.com/iot-for-all/Device-Observability-onthe-Edge) - walks through setting up diagnostics (observability) for an IoT Edge device 

## connecting devices
- [iot-central-high-availability-clients](https://github.com/iot-for-all/iot-central-high-availability-clients) - show coding a device to failover between IoT Hubs
- [iot-central-web-mqtt-device](https://github.com/iot-for-all/iot-central-web-mqtt-device) - simple device ran in a web browser able to do bi-directional communication with IoT Central
- [iot_central_python_sample](https://github.com/iot-for-all/Iot_Central_Python_Sample) - simple sample device written in Python able to do bi-directional communication with IoT Central
- [mock-devices](https://github.com/codetunez/mock-devices) - simulates 1 to 1000 devices, gateways, nested devices, and [Azure IoT Edge](https://github.com/Azure/iotedge) with interactive bi-directional communication with IoT Central 
- [starling](https://github.com/iot-for-all/starling) - simulates tens of thousands of devices connecting to and communicating with IoT Central and displays health metrics using Prometheus and Grafana
- [iotc-paad](https://github.com/iot-for-all/iotc-paad) - app that uses your phone as a device in IoT Central
- [iotc-cpm-sample](https://github.com/iot-for-all/iotc-cpm-sample) - a sample application written in React-Native to connect Bluetooth Low-Energy (BLE) devices to Azure IoT Central
- [iotc-edgemodule-vm-deploy](https://github.com/iot-for-all/iotc-edgemodule-vm-deploy) - an ARM Template to deploy IoT Edge enabled VM pre-configured for an IoT Central edge module
- [iot-central-batch-telemetry-with-python](https://github.com/iot-for-all/iot-central-batch-telemetry-with-python) - sample showing batching telemetry messages using Python device SDK
- [iotc-micropython-client](https://github.com/iot-for-all/iotc-micropython-client) - a micropython SDK for connecting devices to IoT Central
- [iotc-python-client](https://github.com/iot-for-all/iotc-python-client) - a Python SDK for connecting devices to IoT Central
- [iotc-file-upload-device](https://github.com/iot-for-all/iotc-file-upload-device) - shows how a device can upload a file to the cloud using IoT Central
- [node-red-connector-for-azure-iot-central](https://techcommunity.microsoft.com/t5/azure-iot/node-red-connector-for-azure-iot-central/m-p/1605502) - connect devices using Node-RED

## testing devices
- [iotc-twinviewer](https://github.com/iot-for-all/iotc-twinviewer) - tool to view current state of the device twin
- [azure-iot-cli-extension](https://github.com/Azure/azure-iot-cli-extension#microsoft-azure-iot-extension-for-azure-cli) - command line tool for debugging device/cloud messaging
- [saas-to-paas-and-back](https://github.com/iot-for-all/Saas-to-Paas-and-back) - ***PRIVATE*** demonstrates moving devices by sending it a new DPS id_scope

## companion experiences
- [contoso-drive-support](https://github.com/iot-for-all/contoso-drive-support) - an IoT Central companion experience that demonstrates how to build a custom web app for a support technician operating a fleet management solution
- [contoso-drive-simulator](https://github.com/iot-for-all/contoso-drive-simulator) - an IoT Central companion experience that demonstrates how to build a web app that does device simulation (use with the Contoso-Drive Support application)
- [iot-central-aad-app](https://github.com/iot-for-all/iot-central-aad-app) - authenticate and use IoT Central control and data plane APIs
- [iotc-go](https://github.com/iot-for-all/iotc-go) - demonstrates using the IoT Central APIs in a Golang command-line tool
- [iotc-query](https://github.com/iot-for-all/iotc-query) - demonstrates using the query APIs currently in private preview
- [iotc-migrator](https://github.com/iot-for-all/iotc-migrator) - companion experience for moving device between IoT Central applications or to a pure PaaS solution

## transformation
- [Azure/iotc-device-bridge](https://github.com/Azure/iotc-device-bridge) - runnable as an Azure Function or Container, it transforms and sends unidirectional data using HTTP in cloud-to-cloud integrations with IoT Central
- [iotc-device-bridge](https://github.com/iot-for-all/iotc-device-bridge) - transforms and does bi-directional communication using AMQP in cloud-to-cloud integrations with IoT Central
- [iotc-industrial-adt](https://github.com/iot-for-all/iotc-industrial-adt) - A sample integration between OPCUA and Azure Digital Twins through IoT Central. It provides a mapping configuration tool and learning paths to setup required resources.
- [iot-central-transform-with-device-bridge](https://github.com/iot-for-all/iot-central-transform-with-device-bridge) - ***PRIVATE*** a more complete sample of using iotc-device-bridge to transform and send data to IoT Central
- [iot-central-transform-with-iot-edge](https://github.com/iot-for-all/iot-central-transform-with-iot-edge) - ***PRIVATE*** uses Azure IoT Edge to transform and send data to IoT Central
- [iotc-weather](https://github.com/iot-for-all/iotc-weather) - sends collected weather data from a MySQL database to an IoT Central application

## compute
- [iot-central-compute](https://github.com/iot-for-all/iot-central-compute) - a simple way to do compute and data transformation on data sent to Azure IoT Central using Azure Functions


## miscellaneous
- [Overview of Azure IoT Central](https://docs.microsoft.com/en-us/azure/iot-central/core/overview-iot-central)
- [Overview IoT Plug and Play](https://docs.microsoft.com/en-us/azure/iot-pnp/overview-iot-plug-and-play)
- [Digital Twins Definition Language](https://github.com/Azure/opendigitaltwins-dtdl)
- [Connect Azure IoT Edge Devices to an Azure IoT Central](https://docs.microsoft.com/en-us/azure/iot-central/core/concepts-iot-edge)
- [Repo with samples](https://github.com/iot-for-all/iotc-python-client) - Python SDKs and samples
- [Releases](https://pypi.org/project/iotc/) - Python SDKs and samples
- [Device Sample](https://github.com/iot-for-all/Iot_Central_Python_Sample) - Python SDKs and samples
- [Docs](https://docs.microsoft.com/en-us/azure/iot-central/core/tutorial-connect-device-python) - Python SDKs and samples
- [Repo with samples](https://github.com/lucadruda/iotc-nodejs-device-client) - Node.js SDKs and samples
- [Releases](https://www.npmjs.com/package/azure-iotcentral-device-client) - Node.js SDKs and samples
- [Docs](https://docs.microsoft.com/en-us/azure/iot-central/core/tutorial-connect-device-nodejs) - Node.js SDKs and samples
- [Repo](https://github.com/lucadruda/iotc-java-device-client) - Java SDKs and samples
- [Samples](https://github.com/lucadruda/iotc-samples/tree/master/java) - Java SDKs and samples
- [Releases](https://search.maven.org/artifact/com.github.lucadruda/iotc-java-device-client) - Java SDKs and samples
- [Repo (React Native)](https://github.com/lucadruda/iotc-react-native-device-client) - Mobile device
- [Releases](https://www.npmjs.com/package/react-native-azure-iotcentral-client) - Mobile device
- [Android Sample (Java)](https://github.com/Azure/iotc-android-sample) - Mobile device
- [Azure IoT Edge on Kubernetes Connected to IoT Central](https://microsoft.github.io/iotedge-k8s-doc/examples/iotcentraltutorial.html) - Edge
- [Azure IoT Central Edge Hands On Labs With Edge Enabled MarketPlace Linux VM](https://github.com/rangv/azureiotcentraledgelinux) - Edge
- [Azure IoT Edge on CentOS Connected to IoT Central](https://rangv.github.io/azureiotedgewithcentralcentos/) - Edge
- [Industrial IoT Gateway Installer](https://github.com/Azure/Industrial-IoT-Gateway-Installer) - Edge
- [Azure IoT Edge for Linux on Windows (EFLOW) with IoT Central](https://github.com/rangv/AzureIoTCentralEFlow) - Edge
- [Develop with Sphere and Azure RTOS](https://docs.microsoft.com/en-us/learn/modules/develop-secure-iot-solutions-azure-sphere-iot-central/) - Sphere tutorial
- [Repo](https://github.com/Azure/iot-central-firmware) - device firmware
- [IoT Show](https://aka.ms/iotshow) - videos
- [Notification Bridge](https://github.com/lucadruda/iotc-notification-bridge)
- [Node-RED node](https://flows.nodered.org/node/node-red-contrib-azure-iot-device)
