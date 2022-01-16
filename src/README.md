# MCU Source Code

`src` contains code/config for the ESP8266 to expose the particle sensor via API. This can then be read from other devices, such as home assistant servers.

# Setting up

Create a python virtual env

`python3 -m venv .venv`

Step into it

`source .venv/bin/activate`

Install esphome

`pip3 install esphome` (or install the specific version from requirements.txt)

Flash to the ESP.

`esphome run particulate_sensor.yaml`