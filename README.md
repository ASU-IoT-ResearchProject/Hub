
# Security Monitor of IoT Systems and Smart Homes

This is a collection of apps to monitor and manage IoT devices (or any device the user wants to monitor) connected to a users home network.

Minimum Hardware needed:
- Raspberry Pio 3b+ or newer
- MicroSD Card (4gb+ recommended)
- Ethernet cable/connection to router
- Monitor, keyboard, and mouse for initial setup (if ssh does not work)
- A MicroSD card adapter (to mouse raspberry pi image to)
- Android 9+ or iPhone 8+ (to run companion app)



# Documentation/Setup

Documentation and setup guides for the app can be found at the following links

### Setup Guides

For those who want to just setup the apps for home use

[Raspberry Pi App Setup](https://github.com/ASU-IoT-ResearchProject/Hub/blob/main/RaspberryPiApp.docx)

[Backend Apps (optional setup)](https://github.com/ASU-IoT-ResearchProject/Hub/blob/main/BackendApps.docx)

To add, phone app guide

### Developer Guides

For those who want to see the source code and modify it.

[Visual Studio Setup + Source Code Download](https://github.com/ASU-IoT-ResearchProject/IoTRaspberryPi/blob/master/VisualStudioSetup.docx)

More coming soon

# Source code links

### Raspberry Pi App

This app reads nfdump files and send them to the server under the users identity. It collects blocked ips from it every minute and updates IPTables to block traffic from those ips/sites

[Raspberry Pi App](https://github.com/ASU-IoT-ResearchProject/IoTRaspberryPi)

### Phone Apps

This is a Xamarian Forms cross platform app that runs the companion phone app to view the data, cross reference it, and manage your devices.
It can block devices and IPs/Websites from accessing your network.

[Phone Apps](https://github.com/ASU-IoT-ResearchProject/IoTCrossPlatform)

### Self Hosted Webserver

These 2 apps are if a user wants to host the data themselves.

[Webserver App](https://github.com/ASU-IoT-ResearchProject/IotBackendAPI)

[Helper App](https://github.com/ASU-IoT-ResearchProject/IoTBackendHelper)



# Authors

### Latest Version

- [Keith Erkert](https://github.com/KeithErkert)    
    email - keith@erkert.dev

### Original Version/Planning

- [Andrew Lamontagne](https://github.com/metallicafan212)    
    email amlamont@asu.edu

- John Cummings
    email jacummi3@asu.edu

- [Mitchell Hoikka](https://github.com/mhoikka)
    email mhoikka@asu.edu

- Jereming Chen
    email jchen400@asu.edu

### Faculity Advisors

- Kuai Xu
    email kuai.xu@asu.edu

# App Screenshots

### Overview shows stats over the user choosen period and the devices active during that time
![Stats](https://i.imgur.com/XZhNtMj.png)
### Timeline of data usage (more options) of devices
![Stats](https://i.imgur.com/ZUdxGsv.png)
### Piechart showing distrutions of traffic by devices on network
![Stats](https://i.imgur.com/amZJ6dF.png)
### Page to inspect a devices activity
![Stats](https://i.imgur.com/jbJpO7j.png)
![Stats](https://i.imgur.com/HHOvx3h.png)
![Stats](https://i.imgur.com/tVfZRus.png)
### Inspect a IP you device interacted with, you can block the ip from here
![Stats](https://i.imgur.com/s7mOFv6.png)
![Stats](https://i.imgur.com/eKZy3uq.png)
### Manage network rules from here
![Stats](https://i.imgur.com/yn6LGRA.png)
