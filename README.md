# PiHeadquarters

PiHeadquarters or How to Take Control of your House with Raspberry Pi and Docker :whale:

#### _Workshop/Talk for [Pixels.Camp 2017 Edition](http://pixels.camp/)_

- [Slides](https://speakerdeck.com/jpdias/piheadquarters-or-how-to-take-control-of-your-house-with-raspberry-pi-and-docker)

## Description

We're living on the verge of ubiquitous computing, where _computing is made to appear everywhere and anywhere_. As such, we're dealing with this now, by the means of the Internet of Things. Empowered by the ever-cheaper devices with internet connectivity such as the ESP8266 (that costs under 4$) we're able to build our very _own_ smart homes. However, some questions arise on how to deal with all the sensing and actuating capabilities of such devices as well as all the privacy and security issues that are on the table. 

A very common approach that has been applied is the use of gateways for control the data flow between _things_ and the Internet as is. As worth mentioning and novel example of such is the [Things Gateway](https://iot.mozilla.org/gateway/) by Mozilla. In this talk, I will share how I build my _smart home_ headquarters (gateway and server) on top of a Raspberry Pi 2, using Docker and all the _buzzwords_ such as [MQTT](http://mqtt.org/), [Mosquitto](https://mosquitto.org/), [InfluxDB](https://www.influxdata.com/time-series-platform/influxdb/), [Grafana](https://grafana.com/) and [Node-RED](https://nodered.org/). With this approach anyone is capable of continuosly monitor the current state of the home by its metrics, configure alarms (such as a moving sensor for intruder alert), turn on the AC system before leaving work or even make dinner by turning on the microwave, all empowered by easily-configured flow-control diagrams.


## Required/Advised Tools & Hardware

### Tools

- [Visual Studio Code](https://code.visualstudio.com/) _or_ [Atom](https://atom.io/) 
- [PlatformIO](http://platformio.org/)
- [Docker](https://www.docker.com/)

### Hardware

- ESP8266/32 based dev board (Node-MCU ESP-12E is used in this WS)
    - 1x LED
    - 1x DHT11 or DHT22 (temp/humidity sensor)
    - Jump Cables
    - 1x Breadboard
    - 330 Ω resistor
    - 4700 Ω resistor
- Raspberry Pi (any version, v3 is used in this WS)
- Router with Internet connectivity required for setup (in this talk a modified ZSUN with OpenWRT is used)
