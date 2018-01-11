# ESP32_SPIFFS_EasyWebSocket BETA 1.60
Simple library for WebSocket communication with ESP-WROOM-32(ESP32) and smartphone browser.  
This requires the Arduino core for ESP32 library.  
https://github.com/espressif/arduino-esp32  
This use SPIFFS file system.  

My Blog: https://www.mgo-tec.com
# Change log:
(1.60)  
New Release.
Since ESP32_SD_EasyWebSocket Beta ver 1.51.1 has been improved for SPIFFS, the new release version is Beta ver 1.60.  
In the WebSocket handshake, I used the MbedTLS library in Arduino-ESP32 without using the external sha1 file.  
  
  
# 【更新履歴】(Japanese)
(1.60)  
新規リリース。  
ESP32_SD_EasyWebSocket Beta ver 1.51.1 をSPIFFS用に改良したものなので、New Release バージョンは Beta ver 1.60 とします。  
WebSocketハンドシェイクで、外部sha1ファイルを使わず、Arduino-ESP32内にある、MbedTLSライブラリを使いました。  
  
# Credits and license
*Licensed under the GNU LESSER GENERAL PUBLIC LICENSE Version 2.1  
  
Copyright (c) 2018 Mgo-tec  
This library improvement collaborator is Mr.Visyeii.  
Part of WiFiServer.h(for ESP8266) library modified.  
  
This library is used by the Arduino IDE(Tested in ver1.8.2).  
  
Reference Blog --> https://www.mgo-tec.com  
  
This library is free software; you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation; either version 2.1 of the License, or (at your option) any later version.  
  
This library is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  
See the GNU Lesser General Public License for more details.  
  
You should have received a copy of the GNU Lesser General Public License along with this library; if not, write to the Free Software Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA  
  
Reference LGPL-2.1 license statement --> https://opensource.org/licenses/LGPL-2.1  
  
WiFi.h - Included WiFi library for esp32
Based on WiFi.h from Arduino WiFi shield library.
Copyright (c) 2011-2014 Arduino.  All right reserved.
Modified by Ivan Grokhotkov, December 2014
Licensed under the LGPL-2.1
  
SPIFFS.h - Included SD card library for esp32  
Copyright 2015-2016 Espressif Systems (Shanghai) PTE LTD  
Licensed under the Apache License, Version 2.0 (the "License");  
  
Reference Apache License --> http://www.apache.org/licenses/LICENSE-2.0  
  
# My Blog: 
Other usage is Japanese, please visit my blog.  
https://www.mgo-tec.com