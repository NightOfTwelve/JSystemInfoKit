![Logo](/Icon.png)

# SystemInfoKit ![] (https://img.shields.io/travis/jBot-42/SystemInfoKit.svg)
A comprehensive, compact, and well tested system information framework for Cocoa on OS X by the creator of the most complete source on the SMC. 

## Features

### Detailed Device Information

With minimal code, SystemInfoKit can provide detailed device information including device UUID, serial number, model string, and display resolution, CPU specifications, and network information including the ip address, host name, and public IP address.

### Complete SMC Integration

SystemInfoKit's SMC integration is based on [SMCWrapper](https://github.com/FergusInLondon/SMCWrapper). It provides an additional layer of functionality over SMCWrapper including the ability to find all working SMC keys and get human-readable descriptions for keys.

### Built-in System Monitoring Functions

SystemInfoKit provides a comprehensive system monitoring class which can be used to find CPU usage, memory usage, disk usage, network usage, and even detailed information on the battery.

## How To Use

SystemInfoKit is broken up into 3 main modules: JSKDevice, which accesses device information, JSKSMC, which accesses the SMC, and JSKSystemMonitor, which can be used for system monitoring.

### JSKDevice

### JSKSMC

### JSKSystemMonitor

## Contributions

Issues and pull requests are welcome!

## Licensing

SystemInfoKit is released under the GNU GPL v2.0 License. However, it may be used for closed-source projects IF a link to this Github repository is made available along with the message "Powered by SystemInfoKit." and the black version of the SystemInfoKit logo (at least 160px width) in the app's about window.

#### Example:
Powered by [SystemInfoKit](https://github.com/jBot-42/JSystemInfoKit)

<img src="Small Icon.png" alt="Logo" width="160px"/>
