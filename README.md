# home-assistant


  <h4>
  <div align="center">
  <a href="https://travis-ci.org/BertrumUK/home-assistant"><img src="https://travis-ci.org/BertrumUK/home-assistant.svg?branch=Master2"/></a>
  <a href="https://github.com/BertrumUK/home-assistant/commits/Master2"><img src="https://img.shields.io/github/last-commit/BertrumUK/home-assistant.svg?style=plasticr"/></a>
  </h4>
</div>

Running Hassbian on a Raspberry Pi 3 with all physical connections moved off the Pi onto 3 NodeMCU's and 2 Wemos D1 Mini's. Using the Open MQTT RF/IR code (https://github.com/1technophile/OpenMQTTGateway) to provide 433meg RF,IR to my digibox and room temperature/humidity - thanks Florian :)

Have multiple RF 433Mhz sockets controlling lights and bedroom fan. Soon to be moved on Sonoff's once I get new living room lights.

Using the multisensor code from Bruh (https://github.com/bruhautomation/ESP-MQTT-JSON-Multisensor) on the NodeMCU's and Wemos to gather temperatures around the house and provide motion sensing on the 3 house entry points. 

Have Nest Thermostat in the hallway also pulling in the hallway temps. Amazon Dot in the living room provides voice control into HA using emulated hue.

An old Android phone running IP Webcam provides a camera feed of the front of the house.

Configuration files now tested with [Travis](https://travis-ci.org/BertrumUK/home-assistant).


![Screenshot of Home View](https://github.com/BertrumUK/home-assistant/blob/Master2/Screenshots/main%20page.png)
![Screenshot of Home View](https://github.com/BertrumUK/home-assistant/blob/Master2/Screenshots/travel.png)
![Screenshot of Home View](https://github.com/BertrumUK/home-assistant/blob/Master2/Screenshots/weather.png)
![Screenshot of Home View](https://github.com/BertrumUK/home-assistant/blob/Master2/Screenshots/automations.png)
![Screenshot of Home View](https://github.com/BertrumUK/home-assistant/blob/Master2/Screenshots/network.png)
![Screenshot of Home View](https://github.com/BertrumUK/home-assistant/blob/Master2/Screenshots/devices.png)
![Screenshot of Home View](https://github.com/BertrumUK/home-assistant/blob/Master2/Screenshots/fitbit.png)
![Screenshot of Home View](https://github.com/BertrumUK/home-assistant/blob/Master2/Screenshots/media%20devices.png)
![Screenshot of Home View](https://github.com/BertrumUK/home-assistant/blob/Master2/Screenshots/tv%20remote.png)

