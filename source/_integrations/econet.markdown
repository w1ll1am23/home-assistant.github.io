---
title: Rheem EcoNet Products
description: Instructions on how to integrate Rheem EcoNet water heaters into Home Assistant.
ha_category:
  - Binary Sensor
  - Climate
  - Sensor
  - Water Heater
ha_release: 0.61
ha_iot_class: Cloud Push
ha_domain: econet
ha_codeowners:
  - '@vangorra'
  - '@w1ll1am23'
ha_config_flow: true
---

The `econet` platform is consuming the information provided by a [EcoNet enabled Rheem water heater or thermostat](https://www.rheem.com/EcoNet/Home).

## Configuration

1. From the Home Assistant front-end, navigate to 'Configuration' then 'Integrations'. Under 'Set up a new integration' locate 'Rheem EcoNet Products' and click 'Configure'.
2. Enter the information requested, email and password, and click 'Submit'.

## Platforms

EcoNet devices may be represented by one or more platforms.

- [Binary Sensor](#binary-sensor)
- [Climate](#climate)
- [Sensor](#sensor)
- [Water Heater](#water-heater)

### Binary Sensor

The EcoNet Binary Sensor platform lets you view binary states of sensors associated with your EcoNet thermostat or water heater. For example, if the device is curently running.

### Climate

The EcoNet Climate platform lets you control your EcoNet thermostat. Multi zone HVAC systems will have 1 Climate entity per zone.

### Sensor

The EcoNet Sensor platform lets you view sensors associated with your EcoNet thermostat or water heater. For example, alert count or availble hot water.

### Water Heater

The EcoNet Water Heater platform lets you control your EcoNet water heater. Water Heaters do not report the current water temperature.
