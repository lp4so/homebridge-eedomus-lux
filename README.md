# homebridge-eedomus-luxmeter
Supports http ambient light sensor devices on the Homebridge platform. Additional hardware required.
This is a modified version of the https://github.com/crashtestoz/homebridge-http-lux plugin.
This version only supports the light sensor. MAX lightlevel is set to 800.

# Installation

1. Install homebridge using: npm install -g homebridge
2. Install this plugin using: npm install -g homebridge-eedomus-luxmeter
3. Update your configuration file. See sample-config.json in this repository for a sample.

# Configuration


Configuration sample file:

 ```
 "accessories": [
     {
         "accessory": "HttpLux",
         "name": "Ambient Light Level",
         "url": "eedomus API URL to light sensor",
         "http_method": "GET"
     }
 ]

```

```


This plugin acts as an interface between eedomus and homebridge.