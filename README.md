# LoRa-RPM
**Design and Implementation of a LoRA WAN Network in Healthcare: Empowering Patient Monitoring with a Cloud IoT Platform**

**Abstract**

This project aims to design and implement a LoRA WAN (Long Range Wide Area Network) in healthcare to enhance patient monitoring capabilities using a Cloud-based Internet of Things (IoT) platform. The LoRA WAN technology allows for long-range and low-power communication (Jonathan de Carvalho Silva, 2017), making it ideal for connecting medical devices and sensors across healthcare facilities. Leveraging the Cloud IoT platform enables efficient data connectivity, real-time monitoring, and data analysis, leading to improved patient care and remote healthcare management. Integrating LoRA WAN and the Cloud IoT platform provides a scalable and secure solution for healthcare providers to monitor patients effectively and make informed decisions based on real-time data. This project aims to contribute to advancing patient care in the healthcare sector through enhanced connectivity and data-driven insights.

**Keywords**: Packet Forwarding, Low Energy, Long range, Multihop, Internet of Things, AES, Cloud, Radio Module, Gateway.

LoRa RPM Architecture 
![image](https://github.com/Vinojitha/LoRa-RPM/assets/145708343/1b748f93-2faa-496c-ac9a-deb3624460fb)

The choice of node and gateway device is dependent on the particular needs. The "LILYGO LORA32 T3 V1.6.1" is a specific version of an ESP32-based development board manufactured by LilyGO. This board is designed for various IoT (Internet of Things) and LoRa (Long-Range) applications. 
Here's some key information about this board:

ESP32-based: The LILYGO LORA32 T3 V1.6.1 is based on the ESP32 microcontroller, which is widely used for IoT projects. This microcontroller features a dual-core processor, built-in Wi-Fi and Bluetooth abilities, and several GPIO pins that can connect to sensors and other devices. This board features LoRa (Long-Range) wireless communication capabilities, specifically for LoRaWAN applications. LoRa technology allows for long-range communication with low power consumption, making it suitable for IoT devices that need to transmit data over long distances.

Version Information: The board's name, LilyGO LORA32, includes the hardware version number, V1.6.1, which may vary between models.

Development Environment: To effectively utilize this board and engage with it, the recommended tools are the Arduino IDE or PlatformIO with the ESP32 board support package. These platforms enable you to write code in languages such as C++ and incorporate libraries suitable for a diverse range of IoT and sensor-based projects.
Features: The LilyGO LORA32 T3 V1.6.1 likely includes features such as GPIO pins for connecting sensors, OLED displays for visual feedback, and LoRa modules for long-range communication. The specific features may vary depending on the version.

Applications: This board is versatile for a variety of IoT applications, such as environmental monitoring, asset tracking, and agriculture, due to its combination of ESP32 capabilities and LoRa connectivity.

![image](https://github.com/Vinojitha/LoRa-RPM/assets/145708343/853bdd21-7e71-4b3c-bb9b-38d010648532)

Device and output on the OLED display 


![image](https://github.com/Vinojitha/LoRa-RPM/assets/145708343/9e2ec662-4fc1-487a-ab87-6d68dfc0a668)


Sender and receive serial monitor output through Arduino ide


<img width="464" alt="image" src="https://github.com/Vinojitha/LoRa-RPM/assets/145708343/ea90bec1-9936-46dc-ab40-b270bcb4d631">

