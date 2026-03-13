# Home-Assistant-Updated-Nest-Integration
Small tweaks to standard Nest thermostat integration:
- Minimum temperature of 9C rather than the standard 10 (change this value in climate.py, line 73)
- Thermostat current temperature rounds to nearest 0.5 to match the Nest display. Currently, the thermostat card shows the figure accurate to 0.1 which I find frustrating
- The current temperature sensor still is accurate to 0.1 but to change to 0.5, look at line 92 in sensor.py

## How to install
1. Download the nest directory and place in config/custom_components
1. Restart Home Assistant
