---
title: "EVN ZBHS4RGBW Homebridge/HomeKit integration"
description: "Add HomeKit support to your EVN ZBHS4RGBW, using Homebridge, Zigbee2MQTT and homebridge-z2m."
---
<!---
This file has been GENERATED using src/docgen/docgen.ts
DO NOT EDIT THIS FILE MANUALLY!
-->
# EVN ZBHS4RGBW
> Zigbee 4 channel RGBW remote control


# Services and characteristics
The following HomeKit Services and Characteristics are exposed by
the EVN ZBHS4RGBW

* [Battery](../../battery.md)
  * Battery Level
  * Charging State
  * Status Low Battery



## Exposes

This is the information provided by Zigbee2MQTT for this device:

```json
[
  {
    "type": "numeric",
    "name": "battery",
    "property": "battery",
    "access": 1,
    "unit": "%",
    "description": "Remaining battery in %",
    "value_min": 0,
    "value_max": 100
  },
  {
    "type": "enum",
    "name": "action",
    "property": "action",
    "access": 1,
    "values": [
      "color_move",
      "color_temperature_move",
      "brightness_step_up",
      "brightness_step_down",
      "brightness_move_up",
      "brightness_move_down",
      "brightness_stop",
      "hue_move",
      "hue_stop",
      "recall_*",
      "on",
      "off"
    ],
    "description": "Triggered action (e.g. a button click)"
  },
  {
    "type": "numeric",
    "name": "linkquality",
    "property": "linkquality",
    "access": 1,
    "unit": "lqi",
    "description": "Link quality (signal strength)",
    "value_min": 0,
    "value_max": 255
  }
]
```

# Related
* [Other devices from EVN](../index.md#evn)
* [Zigbee2MQTT documentation for this device](https://www.zigbee2mqtt.io/devices/ZBHS4RGBW.html)