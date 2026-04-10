# Home Assistant Zigbee2MQTT TS0042 Blueprint

Reusable Home Assistant blueprint for the Tuya TS0042 2-button remote using Zigbee2MQTT over MQTT.

## Features

- Supports all TS0042 actions:
  - `1_single`
  - `2_single`
  - `1_double`
  - `2_double`
  - `1_hold`
  - `2_hold`
- MQTT-based trigger
- Reusable blueprint for multiple automations
- Designed for Zigbee2MQTT and Home Assistant

## Installation

Copy `ts0042_action.yaml` to:

`/config/blueprints/automation/zigbee2mqtt/`

Then reload automations in Home Assistant.

## Usage

Create a new automation from the blueprint, select your Zigbee2MQTT topic, choose the TS0042 action, and define the action sequence to execute.
