# TECH-018 — Flood-Level Warning Node

**Reality status:** REAL NOW  
**Capability:** measure changing water level remotely and send alerts to a local system  
**Difficulty:** intermediate  
**Cost band:** £  
**Internet required:** no, if local radio telemetry is used  
**Self-hostable:** yes  
**Professional installation:** site dependent  
**Last reviewed:** 2026-10-03

## In everyday language

A small remote node can measure the level of:

- a stream;
- drainage channel;
- tank;
- sump;
- low-lying collection point.

Placed upstream or at a known low point, it may provide warning before water reaches the house.

## Typical architecture

```text
water-level sensor
+ microcontroller
+ battery/solar
+ LoRa or wired link
→ local server/dashboard
→ threshold alert
```

## Useful design principles

- use multiple thresholds rather than one "panic" threshold;
- retain local/manual observation;
- detect sensor failure separately from normal water level;
- design the enclosure for weather, insects and debris;
- treat telemetry as advisory, not infallible.

## Present-day anchors

- Meshtastic — https://meshtastic.org/
- Home Assistant — https://www.home-assistant.io/

## Safety boundary

Flood behaviour is highly site-specific. Barriers, diversions, structural protection and drainage redesign require appropriate hydrological/building expertise.

## Comic use

A rising upstream node can provide a narrative clock: the community sees conditions changing before the lower access road becomes unusable.
