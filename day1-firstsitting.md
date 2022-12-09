What is IoT

• Internet of Things
• Hardware devices (=things) connected to the internet


![image](https://user-images.githubusercontent.com/24469318/206714881-360da912-5dba-44ed-80dd-54a9a6b38d8c.png)


Inorder for IOT system to be useful:
• Secure
• Reliable
• Bi-Directional
• Monitored

Why learn IoT?

- Industry is booming
- Expected to grow 25% annually
- IoT devices are everywhere
- Many new start-ups are IoT based

![image](https://user-images.githubusercontent.com/24469318/206715469-d530c203-f4e3-4eb5-a0f8-2550ed1b74c8.png)

Source: Azure IoT Signals Report Oct 2021
https://azure.microsoft.com/mediahandler/files/resourcefiles/iot-signals/IoT%20Signals Edition%203 English.pdf

## IoT in Azure

- Azure offers a comprehensive array of IoT-related services
- Handles enrollment, security, messaging, management, streaming, monitoring and more
- One of the leading IoT services suites in the world

## AZ-220 Microsoft Azure IoT Developer

- The only Azure certification about IoT
- Covers all the IoT-related services in Azure
- Makes you a real expert in the IoT field
- Helps you find a great job

# The Azure IoT Handbook

A handbook summarizing the contents of this course
A handy way to memorize all the important topics in Azure IoT
. IoT Hub
• IoT Central
• Edge And lots more...
• A great way to prepare for the exam
• Extremely practical in designing IoT systems in Azure

# Who Is This Course For?
• Developers
• Architects
• Anyone who is interested in the cloud and IoT

AZ-220 Exam

• Exam you should take in order to gain the Azure IoTDeveloper certification
• No other pre-requisites exist
• Exam topics are set by Microsoft


• Length:
    Total: 120 mins (incl. preparation, overview, NDA etc.)
• No. of questions: 40-60
• Passing score: 700 / 1000
• Note: It is forbidden to discuss exam details. You sign an NDA.

# Agenda

- Introduction to IoT Hub
- Messaging and communication
- Device provisioning service
- Device management
- IoT Central
- IoT Edge
- Digital Twins
- Stream processing of IoT data
- Health Monitoring
- Security
- Preparing for the exam
- Practice Test


IOT Hub

- Central messaging hub for bi-directional communication with IOT devices
- Can handle million of devices
- Reliable and secure
- Supports multiple messaging patterns
- Has built-in monitoring


Devices connect in order to...
• Send telemetry
• Get software updates
• Send images
• Send sensor data etc...

![image](https://user-images.githubusercontent.com/24469318/206720532-00a23ed9-2e4e-4ac8-a9e7-4bbd788e5bc6.png)

# Device Connection to IOT Hub
- Extremely simple code
- Can use Azure IoT Hub SDK
- Supported in:
•  c
•  python
• NodeJS
•  .NET
• Java

# Communication protocols:
- HTTPS
- AMQP
- MQTT

# Message Routing
• Connecting to IOT Hub is not enough...

![image](https://user-images.githubusercontent.com/24469318/206721166-57f7ece6-fe74-47d2-9c34-d0338c4749bd.png)

• Message from the IOT device should be routed somewhere

![image](https://user-images.githubusercontent.com/24469318/206721297-55859f7b-fd3f-40f4-860b-07733c6b4295.png)


![image](https://user-images.githubusercontent.com/24469318/206721751-50a2d77d-f553-4e7a-a820-30c415a49dc6.png)

**Device-to-Cloud Communication**

The classic communication pattern
Three modes:
    • Telemetry & Data (the most common)
    • Files upload
    • Device Twin


# **Cloud-to-Device Communication**
 The other way around...
Used mainly for:
Send commands to the device

- Software updates
• Uses Direct Call to communicate with specific device(s)

**IOT Hub Security**

• One of the major issues with IOT
• Need to make sure that:
• Only allowed devices can connect to the IOT Hub
• Communication is safe


**Device Authentication**

Devices can authenticate using the following:
• SAS token
• Individual X.509 certificate (per device)
• X.509 CA authentication (all devices)

**Secure Communication**
Secure communication
 • Communication to IOT Hub is done using TLS
  • Can configure the minimum TLS version
    • Note: vl.0 & vl.l are deprecated
    
![image](https://user-images.githubusercontent.com/24469318/206722990-b460b9eb-3565-45a4-aad6-1065a0544d40.png)

![image](https://user-images.githubusercontent.com/24469318/206723234-55e1f807-b2a7-4641-81be-3708149f360a.png)

![image](https://user-images.githubusercontent.com/24469318/206723329-1635af1c-f1b8-47ae-a577-c3d6e8c1625b.png)

![image](https://user-images.githubusercontent.com/24469318/206723389-b8ac3de9-25bd-4e11-92e3-2071f0919074.png)




