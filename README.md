# Suraksha-Kavach
Suraksha Kavach is an innovative safety and security system designed to provide real-time protection for individuals and property. With the increasing concerns about personal safety, workplace security, and emergency response, this project integrates IoT, AI, and cloud computing to create an efficient and intelligent security framework.
Samraksh: IoT Based Women Safety Device
Abstract
Despite the fact that our country is a powerhouse with a developing economy, it nevertheless has a number of crimes against women.
To address this big issue, we offer "Samraksh" as a solution.
This is a safety mechanism designed exclusively for women who are in difficulties, stress, etc.
Our system contains GPS Module, ESP8266, LED, Thingspeak Cloud service, Button & Beep Buzzar.
When a person is in distress, she must hit the button on the system provided.
The location of the device is determined in terms of longitude & latitude along with date and time. Then this data is sent to the Real-Time Cloud Service.
Now trusted person/family can access the location by copy-pasting that longitude & latitude into the Google Map followed by "," as soon as they are alerted by our system.
Introduction
Safety being one of the most concerning issues, it is necessary to find an efficient way to ensure the safety of the people and the society.
Women's safety is considered to be one of the most critical issues in a country like India, where the rate of crime is thought to be higher than the pace of population increase.
NCRB states that as many as 39 crimes are reported every hour in the country. This adverse crime situation has embedded fear in the mind of people. If statistics are to be seen, around 20,532 cases are registered every year.
We come across many headlines reporting cases of molestation, trafficking, ill-treatment, ragging, kidnapping, missing and etc.
After identifying a hazard, existing handheld gadgets for human protection require human safety, such as pressing a button.
Objectives
To build a safety device for women.
To facilitate quick action and hence reduce the harm.
To ensure the security of woman in the society and hence to promote Woman Empowerment.
Problem Statement
Among all of the heinous crimes that have been witnessed recently, ensuring the safety of women has become a challenge, and thus a major source of concern in society.
Methodology
The system comprises of two devices: Device 1 & Device 2, where Device 1 will be with the individual whose position is to be tracked, and Device 2 will be with a trustworthy person or family member, and this device will notify using a beeping buzzer.
The system includes a NEO 6M-GPS Module, as well as an LED, a push button, and a buzzer.
When the push button is pressed LED turns on for indication purposes and an email is sent to the trustworthy person or family members. The location of the device in terms of latitude & longitude is determined along with LED status.
Now, this data from GPS Module along with LED status is uploaded or updated in the cloud by ESP8266 Node MCU for further use. As soon as LED status in the cloud is set to 1 Beeping buzzer in Device 2 will start to Beep for indication purposes. That time display of the data in the cloud is accessed by the trusted person or family members so that they can take further action.
Block Daigram
Device 1 - Using NEO 6M GPS Module Swasthya Final Implementation (GPS)

Device 2 - Using Beep Buzzer Device 2 Samraksh
Requirements
Software Requirements
Arduino IDE
Thingspeak Cloud Service
Hardware Requirements
NEO 6M GPS Module
ESP8266 Node MCU
Power Supply
Push Button
Beep Buzzer
General PCB
Resistor
LED
Data Used
Longitude and Latitude
LED Status (0 & 1)
Date and Time
