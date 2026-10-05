# Automate the North: Home Assistant configuration

Blueprints, packages and dashboard sections from [automatethenorth.com](https://automatethenorth.com). Every file here runs in daily use in one home. Each project page explains how it works and how to set it up:

| Project                                                                                           | Files                                                                                                                                            |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Car block heater by departure time](https://automatethenorth.com/projects/car-block-heater/)     | `blueprints/automation/automate_the_north/car_block_heater.yaml`, `packages/car_block_heater.yaml`, `dashboards/car_heating_section.*.yaml`      |
| [Smoke guard for the ventilation](https://automatethenorth.com/projects/smoke-guard/)             | `blueprints/automation/automate_the_north/smoke_guard.yaml`, `packages/smoke_guard.yaml`, `dashboards/smoke_guard_section.*.yaml`                |
| [CO₂ boost and home/away](https://automatethenorth.com/projects/co2-boost/)                       | `blueprints/automation/automate_the_north/ventilation_co2_presence.yaml`, `packages/ventilation_co2.yaml`, `dashboards/co2_boost_section.*.yaml` |
| [Spot electricity price](https://automatethenorth.com/projects/spot-price/)                       | `packages/spot_price.yaml`, `dashboards/spot_price_*.yaml`                                                                                       |
| [Ouman H23 district heating over Modbus](https://automatethenorth.com/projects/district-heating/) | `packages/ouman_h23.yaml`, `dashboards/district_heating_section.*.yaml`                                                                          |
| [Dashboard status lines](https://automatethenorth.com/projects/status-lines/)                     | `dashboards/status_line.*.yaml`                                                                                                                  |

Dashboard files come in English (`.en.yaml`) and Finnish (`.fi.yaml`).

## Importing a blueprint

In Home Assistant, go to **Settings → Automations & scenes → Blueprints → Import blueprint** and paste the GitHub link to the blueprint file. The project pages also have an import button.

## Feedback

Questions and ideas are welcome in the project threads on the [Home Assistant Community forum](https://community.home-assistant.io/).

This repository is published automatically from the site's sources, so pull requests can't be merged here.

## License

[MIT](LICENSE)
