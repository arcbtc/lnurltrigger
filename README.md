<h1>NO LONGER MAINTAINED, MAINTAINED REPO <a href="https://github.com/arcbtc/bitcoinTrigger/">HERE</a></h1>

<h3>LNURL Trigger, bitcoin lightning powered relay ⚡</h3>

## LNURL-pay PoS unit for retrofitting any device to accept bitcoin over lightning network

> <i>Join our <a href="https://t.me/makerbits">telegram support/chat</a>.</i>


<p align="center">
<img src="https://i.ibb.co/4WcQR6r/trigger3.gif">
  <img src="https://i.ibb.co/R002brg/trigger1.gif"><br/>
    
  </p>

### Installation

Install Arduino IDE: 

https://www.arduino.cc/en/software

Install ESP32 boards: 

https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/

Install libraries:
- WiFimanager
- ArduinoJson

<img src="https://i.imgur.com/KEg2QsN.png" width="50%">

Upload code!

### Usage

GPIO 04 is set to monitor capacitance, and if pressed on startup triggers portal access point<br/>
Connect to the WiFi captive portal SSID: "⚡lnurltrigger⚡" PASS: "password1"<br/>
Enter your LNBits details, and the pin you wish to set HIGH (default 16)<br/>
LNURLtrigger makes an LNURL-pay in lnbits, which can be printed<br/>
Connect whatever you want turned on (relay,led,etc) to the HIGH pin and GND
<p align="center">
<img width="600px" src="https://i.imgur.com/iSCQQbb.png"><br/>
  <img width="600px" src="https://i.imgur.com/Ssmn01t.png"><br/>
<img align="center" src="https://i.imgur.com/I8T5QVe.gif" width="600px">
</p>
https://www.youtube.com/watch?v=LAh8HryVaeY
