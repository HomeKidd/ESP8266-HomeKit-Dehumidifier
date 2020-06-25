# ESP8266 based  HomeKit [Dehumidifier](http://s.click.aliexpress.com/e/_dYK2ZZ6)
ESP8266 based  HomeKit Dehumidifier using an SHT3x temperature/humidity sensor and a cheap AliExpress XROW600B Dehumidifier with a custom PCB.

------
[![Instagram URL](https://img.shields.io/twitter/url/https/www.instagram.com/homekidd?label=Follow&logo=instagram&style=social)](https://www.instagram.com/homekidd) [![FaceBook URL](https://img.shields.io/twitter/url/https/www.facebook.com/HomeKiid?label=Like&logo=facebook&style=social)](https://www.facebook.com/HomeKiid) [![YouTube URL](https://img.shields.io/twitter/url/https/www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA?label=Follow&logo=youtube&style=social)](https://www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA)
------

[![GitHub All Releases](https://img.shields.io/github/downloads/HomeKidd/ESP8266-HomeKit-Dehumidifier/total?color=green)](https://github.com/HomeKidd/ESP8266-HomeKit-Weather-Station-BME280-Elgato-Eve/releases) 
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/HomeKidd/ESP8266-HomeKit-Dehumidifier?color=yellow&label=Latest%20Release)](https://github.com/HomeKidd/ESP8266-HomeKit-Dehumidifier/releases) 
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CEYEK69ZYG69S&source=url)
<br/>
<br/>


## For more information please read the [Build Instructions](https://github.com/HomeKidd/ESP8266-HomeKit-Dehumidifier/wiki/Build-Instructions) Wiki page!<br/><br/>


**This HomeKit enabled Dehumidifier requires a custom PCB and the exact same [XROW600B Dehumidifier](http://s.click.aliexpress.com/e/_dYK2ZZ6)!** 



**Features:**

* Humidity Measuring
* Set up Target Humidity
* Power Button
* Controlling fan speed
* Water Level _(LED lights up when the Tank is full)_
* Reset button 


<br/>
<br/>
<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Weather-Station-BME280/raw/master/images/homekid_ffmockup_2.jpg" class="center" width="650"/>

<br/>

**Demo:**

<br/>
<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Weather-Station-BME280/raw/master/images/ifos.gif" class="center" width="250"/>

<br/>
<br/>

This project uses the Apple HomeKit accessory server library [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) from [@MaximKulkin](https://github.com/maximkulkin) for [ESP-OPEN-RTOS](https://github.com/SuperHouse/esp-open-rtos).<br/>

Although already forbidden by the sources and subsequent licensing, it is not allowed to use or distribute this software for a commercial purpose.<br/><br/>

<img src="https://freepngimg.com/thumb/apple_logo/25366-7-apple-logo-file.png" width="20"/> 

###### HomeKit Accessory Protocol (HAP) is Apple’s proprietary protocol that enables third-party accessories in the home (e.g., lights, thermostats and door locks) and Apple products to communicate with each other. HAP supports two transports, IP and Bluetooth LE. The information provided in the HomeKit Accessory Protocol Specification (Non-Commercial Version) describes how to implement HAP in an accessory that you create for non-commercial use and that will not be distributed or sold.

###### The HomeKit Accessory Protocol Specification (Non-Commercial Version) can be downloaded from the [HomeKit Apple Developer page.](https://developer.apple.com/homekit/)

###### Copyright © 2019 Apple Inc. All rights reserved.
