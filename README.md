# ![Dashboard](static/img/launcher-icon-1x.png) PiFire
## Raspberry Pi Zero W based Smoker Grill Controller

### About this Fork

* Objective is to publish all meaningful data to an MQTT broker, including autodiscovery information to automatically create a HomeAssistant device, sensors, and useful attributes.
* This fork is intended only for testing and development with with the goal of merging back into the PiFire project when complete
* High level architecture:
	* Implement as a new Notification class, similar to the influxdb notification
 	* Should be optional, and even if MQTT is selected the Homeassistant auto-discover information should also be optional
  	* Leverage the already existant data structures including the "current", "sensor", ... data structures which already have all or most data we would need.

***Warning:*** *The creator of this project takes no responsibility for any damage that you may do to your personal property including modifications to your smoker grill if you choose to use this project.  The creator also takes no responsibility for any resulting harm or damages that may come from issues with the hardware or software design.*  ***This project is provided for educational purposes, and should be attempted only by individuals who wish to assume all risks involved.***

### Licensing

This project is licensed under the MIT license.

```
MIT License

Copyright (c) 2020 - 2023 Ben Parmeter and Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
