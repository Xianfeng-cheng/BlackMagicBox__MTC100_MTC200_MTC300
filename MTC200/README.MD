Black Magic Box is an accessory developed for the BMD series cameras, integrating USB 3.1 HUB functionality, gigabit Ethernet interface, and wireless WiFi capabilities. This series of products adopts a design that separates the control box from the data cable, addressing the issue of poor cable contact due to long-term bending while allowing users to extend the distance freely.
MTC100 only features HUB and Ethernet functionality, MTC200 and MTC300 integrate routing and WiFi capabilities.

The MTC300 offers more development-friendly accessories and interfaces. All three products can be used with BMD cameras that support USB-C port network connections, allowing users to record using SSD drives while also utilizing zoom or focus control sticks. 

Additionally, users can connect this box to a desktop (Mac/Pc) via Ethernet or WiFi to directly browse and download files captured by the camera, as well as control the camera's functions through control buttons, with the corresponding commands customizable by the user.
Aside from being used with BMD cameras, the device can also function as a regular USB-to-network device and can serve as a HUB, compatible with USB 3.1/2.0. 

The MTC300 offers flexible development capabilities, allowing users to develop their own control devices based on the manufacturer's REST API.

This product features an ultra-thin and lightweight design, equipped with silicone buttons that provide an excellent tactile feedback experience.

**Product Features:**
1.	Supports USB 3.1, 3.0, 2.0, and 1.1
2.	Integrated 10/100/1000M transceiver
3.	Embedded MIPS24KEc (580 MHz)  64 KB 
4.	MCM 16 Mbytes DDR1 KGD (MT7628DAN)
5.	2T2R 2.4 GHz with 300 Mbps PHY data rate
6.	Legacy 802.11b/g and HT 802.11n modes
7.	20/40 MHz channel bandwidth
8.	WEP64/128, TKIP, AES, WPA, WPA2, WAPI
9.	Legacy 802.11b/g and HT 802.11n modes
10.	Supports Full Duplex flow control (IEEE 802.3x)
11.	Supports CDC-ECM
12.	Supports LPM (Link Power Management),
13.	U1/U2/U3 at SuperSpeed, and L1/L2 at
14.	Supports REST API 
15.	Supports remote devices developed based on WiFi and REST API
16.	The remote control button functions can be
17.	customized
18.	Support simultaneous use of Zoom or Focus
19.	Demand and SSD
20.	Supports remote control devices developed
21.	based on WiFi and REST API.
22.	Ultra-thin and ultra-light design
23.	Recyclable 3D-printed casing
24.	Supports connection to PC or Mac 
25.	Dimensions：70x43X12.6mm Weight: 42g
26.	Attachments: MTC200, 1/4 screw clamp, 
27.	30cm/11.8in USB 3.1 cable

**Supported Models**
Blackmagic Cinema Camera 6K

Blackmagic Studio Camera 4K Plus

Blackmagic Studio Camera 4K Pro G2 

Blackmagic Studio Camera 4K Plus G2 

Blackmagic Studio Camera 6K Pro

Blackmagic Studio Camera 4K Pro

Besides the models mentioned above, any model that supports network connectivity and REST API is also supported.

**Setup Guide**

Camera Settings:
Note: After initializing the camera or performing a firmware upgrade, it is necessary to reconfigure the settings.

1.Install the official BMD application Then, connect the camera to the computer using a USB cable to enable the web control feature through the setup process.

2. Set the camera to a static IP address
IP:10.0.0.3  Subnet Mask：255.255.255.0  Gateway :10.0.0.1  DNS 8.8.8.8

1.	Connect to the computer via RJ45
Set the computer's IP address to: 10.0.0.100, Gateway: 10.0.0.1.
Open a browser or use a mobile device to enter: 10.0.0.1 to access the system settings interface.

2.	Connect to the computer via Wi-Fi
Use a computer, mobile phone, or tablet to connect to the wireless network SSID: MTC200-XXXX (where XXXX represents the last four digits of the network address).
Open a browser or use a mobile device to enter: 10.0.0.1 to access the system settings interface.

**MTC200/MTC300 Notes**
1.  System Initialization Issue
After inserting the camera into the USB 3.0 Type-C port, please wait for more than 25 seconds before pressing any control buttons. Otherwise, the system self-check may fail, and the system will think that a button has been pressed prematurely. If the self-check fails, youwill need to unplug and reinsert the USB cable.
2. Regarding IP Address Issues
To control the transmission speed of the system, we recommend using a static URL, with the default IP address of 10.0.0.3 for the camera side. If users need to modify it to fit their own subnet, they will need to change the camera's URL and also update the default WEB address of the MTC20/MTC300 and the control script in the REMOTE options to the same IP address as the modified one. 
3.Remote Control Function
The MTC200/MTC300 currently supports camera models that are compatible with REST API. Please refer to the camera manual to check for compatibility.
4.	Connect to the computer via RJ45
Set the computer's IP address to: 10.0.0.100, Gateway: 10.0.0.1.
Open a browser or use a mobile device to enter: 10.0.0.1 to access the system settings interface.
5.	Connect to the computer via Wi-Fi
Use a computer, mobile phone, or tablet to connect to the wireless network SSID: MTC200-XXXX (where XXXX represents the last four digits of the network address).
Open a browser or use a mobile device to enter: 10.0.0.1 to access the system settings interface.

**Troubleshooting**
1.	Hard Drive Not Recognized
Please unplug and replug the drive, or restart the device to complete automatic loading.
2.	Hard Drive Read/Write Frame Loss
Please replace the SSD drive with a model recommended by the BMD manufacturer. You may also try changing the connection cable, as USB 3.0 has higher signal requirements for cables.
3.	Using the Control Stick
The control stick uses the USB 2.0 communication standard, so a regular USB cable can be used.
4.	Buttons Not Responding
During the power-on initialization process, do not press any control buttons. Wait at least 20-25 seconds before pressing any control button; otherwise, the system may mistakenly think there is a fault in the startup process, leading to a failure in loading.
5.	Control Function Definition
The control button functions of the MTC200 can be defined by the user through the Web settings interface. The definitions must adhere to the requirements of CURL and scripting formats, as well as comply with REST API protocol requirements.

