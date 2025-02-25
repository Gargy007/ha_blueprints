# Home Assistant Solar Power Management Blueprint

This blueprint provides automated power management for homes with solar panels and battery storage, specifically designed for Solax inverters.

## Features

- Manages devices based on solar power excess
- Supports multiple device types (switches, climate devices, lights)
- Time-based forecast control
- Anti-flapping protection with minimum on/off times
- Battery level protection
- Solar forecast integration

## Requirements

- Home Assistant
- Solax inverter integration
- Forecast.Solar integration (optional)

## Installation

1. Install the blueprint by clicking: [![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/gargy007/ha-blueprints/blob/main/blueprints/automation/gsh/solar_excess_power.yaml)

2. Configure the automation with your specific entities and thresholds

## Configuration

### Required Input Entities
- Battery level sensor
- Export power sensor
- Device to control

### Optional Settings
- Battery level thresholds
- Power export thresholds
- Minimum on/off times
- Forecast time window

## Author
Petr Gargulak