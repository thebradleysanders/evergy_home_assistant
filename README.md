# ⚡Evergy Integration for Home Assistant

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)

A simple utility that you can use to login to your Evergy account and retrieve you meter readings.

> **Note: This is an unofficial utility that uses Evergy's non-public API.**

## Usage

1. Copy the folder evergy into your Home Assistant custom_components folder
  <b>OR</b>
  Install via HACS (Home Assistant Community Store) by adding this custom repository
4. Restart Home Assistant
5. Within Home Assistant->Settings->Integrations->Add->Evergy


### Output
The sensor will present the latest data. The `Usage` is in kilowatt-hours. I believe the `Peak Date Time` is the
time during that day when your usage was the highest and the `Peak Demand` is how many kilowatts you were drawing at that time.

#### About
* Update Interval is 90 minutes, sensors are only updated if there are changes.
* Support for the Energy Dashboard
* There seems to be at least 4 updates per day.

Exposed Sensors:
* Address: `123 Seseme St.`
* Period: `Friday`
* Bill Amount: `0.0`
* Is Past Due: `false`
* Bill Date: `0000-00-01T00:00:00`
* Usage: `14.7756`
* Demand: `3.7992`
* Avgerage Demand: `0.0`
* Peak Demand: `3.7992`
* Peak Date Time: `12:45 p.m.`
* Max Temp: `71.0`
* Min Temp: `71.0`
* Avgerage Temp: `71.0`



## Related Projects
- [KC Water](https://github.com/patrickjmcd/kcwater): A similar project developed by [Patrick McDonagh](https://github.com/patrickjmcd). Check it out!
- [KS_Gas](https://github.com/thebradleysanders/Kansas_Gas_Home_Assistant): A Home Assistant Integration for Kansas Gas

