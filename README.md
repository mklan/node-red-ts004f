# node-red-TS004F

Node-red subflow for zigbee [4-way switch TS004F](https://zigbee.blakadder.com/Eardatek_ESW-4ZAA-CN.html). Works only with [Zigbee2Tasmota](https://tasmota.github.io/docs/Zigbee/)!

<img src="https://zigbee.blakadder.com/assets/images/devices/Eardatek_ESW-4ZAA-CN.jpg" width="300">
<img src="https://github.com/mklan/node-red-TS004F/blob/main/outputs.png" width="800">

## install 

In you node-red dashboard press `ctrl + i` and import `subflow.json`

## Connect to Zigbee2Tasmota

1.  `double click` the imported subflow called 4Way Switch [TS004F] and set the friendly name of your switch you set in Zigbee2Tasmota

2. `click` on Edit subflow template to open the inner template. 

3. `ctrl + double click` the zigbee2tasmota submodule to open its inner template.

4. `double click` the mqtt-in module called `enter-your-mqtt-topic` and set your mqtt-server and topic matching your Zigbee2Tasmota config.
