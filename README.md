# ha-blueprints
My Home Assistant blueprints

*If you need help or have any issues with the blueprints make a issue!*

## zha_ts004f_button.yaml / z2M_ts004f_button.yaml
Blueprint for the TS004F signle Zigbee button
- Model: TS004F (in both ZHA and Z2M), ZG-101ZL (in mqtt integration with Z2M)
- Aliexpress: https://www.aliexpress.com/item/1005006762476931.html

ZHA:
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FDanek309044%2Fha-blueprints%2Frefs%2Fheads%2Fmain%2Fzha_ts004f_button.yaml)
<br>Z2M:
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FDanek309044%2Fha-blueprints%2Frefs%2Fheads%2Fmain%2Fz2m_ts004f_button.yaml)

## spotcast_handoff.yaml
Blueprint for the spotify handoff feature
- Integrations: Spotify, Spotcast v6, cast/any media integration for your Spotify connect speaker
- Only works with one Spotify account and with one phone (beacuse of Home Assistant limitations for NFC tags on Android) as the reverse handoff
- Recommended to use in your room/studio

*Tested with Samsung Galaxy S10 and Google Nest Mini 2*

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FDanek309044%2Fha-blueprints%2Frefs%2Fheads%2Fmain%2Fspotcast_handoff.yaml)

### Spotcast v6 setup
[HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=fondberg&repository=spotcast), [Spotcast v6 configuration](https://github.com/fondberg/spotcast/blob/dev/docs/config/spotcast_configuration.md)
