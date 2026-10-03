# BUILD-001 — Off-Grid Environmental Node

**Status:** concept  
**Related tech:** TECH-013, TECH-014, TECH-017, TECH-018  
**Difficulty:** intermediate  
**Cost band:** £  
**Internet required:** no

## Problem

A rural node needs simple environmental information from places where mains power, Wi-Fi or cellular coverage may not be convenient.

## Intended outcome

Create a small solar/battery-powered sensing node that can report one or more low-risk environmental variables to a local network.

Candidate variables:

- air temperature;
- humidity;
- soil moisture;
- tank level;
- rainfall switch/event;
- simple equipment state.

## Concept architecture

```text
sensor(s)
→ low-power microcontroller
→ LoRa radio
→ local gateway
→ local dashboard
```

## Present-day anchors

- ESP32 family — https://www.espressif.com/en/products/socs/esp32
- Meshtastic — https://meshtastic.org/
- Home Assistant — https://www.home-assistant.io/

## Design priorities

- low power;
- weather-resistant enclosure;
- replaceable commodity sensors;
- local operation without cloud dependence;
- visible battery state;
- easy manual replacement;
- clear distinction between "no data" and a normal reading.

## Not yet a finished build

This page intentionally does **not** yet prescribe a definitive parts list or wiring diagram.

Before promotion to `tested`, the project needs:

1. one reference hardware configuration;
2. enclosure design;
3. power-budget test;
4. range test;
5. sensor-calibration notes;
6. failure-mode test;
7. build photographs;
8. repeatable instructions.

## Comic use

A future Kastel Field Node may be a fictionalised, more capable descendant of this real-world pattern.
