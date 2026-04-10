# Home Assistant Zigbee2MQTT TS0042 Blueprint

[![Open your Home Assistant instance and import this blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/javierconfoie/ha-z2m-ts0042-blueprint/main/ts0042_action.yaml)

A reusable Home Assistant automation blueprint for the **Tuya TS0042 2-button remote** using **Zigbee2MQTT** over **MQTT**.

This blueprint lets you assign an independent action sequence to each available TS0042 action:

- `1_single`
- `2_single`
- `1_double`
- `2_double`
- `1_hold`
- `2_hold`

## Features

- Supports all Zigbee2MQTT actions exposed by the TS0042
- One blueprint for the whole remote
- Independent action sequence for each button event
- MQTT-based trigger
- Designed for Zigbee2MQTT and Home Assistant

## Import into Home Assistant

Click the button above to import the blueprint directly into your Home Assistant instance.

## Manual Installation

Copy `ts0042_action.yaml` to:

```text
/config/blueprints/automation/zigbee2mqtt/
