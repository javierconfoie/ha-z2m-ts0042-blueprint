# Home Assistant Zigbee2MQTT TS0042 Blueprint

A reusable MQTT-based blueprint for the Tuya TS0042 2-button remote in Home Assistant.

## Features

Supports the following actions for both buttons:

- `1_single` — Button 1 single press
- `2_single` — Button 2 single press
- `1_double` — Button 1 double press
- `2_double` — Button 2 double press
- `1_hold` — Button 1 hold
- `2_hold` — Button 2 hold

## Installation

### Import via URL

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fjavierconfoie%2Fha-z2m-ts0042-blueprint%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fzigbee2mqtt%2Fts0042_action.yaml)

### Manual Installation

1. Copy `blueprints/automation/zigbee2mqtt/ts0042_action.yaml` to your Home Assistant `config/blueprints/automation/zigbee2mqtt/` directory.
2. Reload blueprints in Home Assistant (**Developer Tools → YAML → Reload Blueprints**).

## Usage

1. Go to **Settings → Automations & Scenes → Blueprints**.
2. Find **Tuya TS0042 2-button remote (Zigbee2MQTT)** and click **Create Automation**.
3. Enter the Zigbee2MQTT base topic and device friendly name.
4. Assign actions to each button event.

## Requirements

- [Home Assistant](https://www.home-assistant.io/) with the MQTT integration configured.
- [Zigbee2MQTT](https://www.zigbee2mqtt.io/) running and paired with a Tuya TS0042 device.

## License

[MIT](LICENSE)
