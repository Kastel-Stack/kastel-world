# TECH-017 — Wildfire Early-Warning Layer

**Reality status:** EXPERIMENTAL  
**Capability:** combine local environmental sensing with official information and human observation to improve situational awareness  
**Difficulty:** intermediate/advanced  
**Cost band:** ££  
**Internet required:** optional for local sensors; useful for official/remote feeds  
**Self-hostable:** partly  
**Professional installation:** depends on the site and any linked suppression system  
**Last reviewed:** 2026-10-03

## In everyday language

A rural property can combine:

- local weather;
- temperature/humidity;
- wind;
- smoke/particulate sensing;
- cameras;
- water/pump status;
- remote sensor nodes;
- official fire alerts.

The objective is not to claim that a cheap sensor can "detect every wildfire".

The useful capability is:

> **notice changing conditions earlier and understand what is happening around the property.**

## Important distinction

Environmental sensing is not a substitute for:

- official warnings;
- fire-service advice;
- evacuation orders;
- professionally designed fire protection.

## Plausible architecture

```text
local weather station
+ smoke/PM sensors
+ cameras
+ remote LoRa nodes
+ official alerts when online
→ local dashboard
→ human assessment
```

## Present-day anchors

- Home Assistant — https://www.home-assistant.io/
- Meshtastic — https://meshtastic.org/
- OpenStreetMap — https://www.openstreetmap.org/

Specific wildfire guidance should come from the relevant local fire authority.

## Comic use

NODE-SA-01 can use this layer to build a picture of wind, smoke, water reserve and access routes during a fire episode.

The dramatic value comes from incomplete information: sensors improve awareness but do not eliminate uncertainty.
