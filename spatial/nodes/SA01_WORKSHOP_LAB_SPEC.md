# SA-01 Workshop / Lab — Canonical Specification

**Asset ID:** `BLDG-SA-01-LAB-W1`  
**Node:** `NODE-SA-01`  
**Status:** canonical concept v0.1  
**Type:** detached workshop, fabrication space and technical lab  
**Relationship to house:** separate building within easy walking distance

## 1. Purpose

The workshop/lab is one of the defining buildings of NODE-SA-01.

It gives the node the practical capacity to:

- repair;
- fabricate;
- prototype;
- diagnose;
- store spares;
- maintain electronics;
- build environmental sensors;
- service bicycles and small equipment;
- host larger local compute/storage where appropriate.

Narratively, it is also an excellent recurring set.

It provides:

- technical problem-solving scenes;
- humour;
- arguments while fixing things;
- experiments;
- breakdowns;
- improvised repairs;
- visitor demonstrations;
- occasional comic disasters.

## 2. Why detached

The workshop/lab should be separate from the main house for:

- noise;
- dust;
- fire separation;
- tool safety;
- battery/equipment separation;
- visual distinction;
- story flexibility.

A detached building also lets the house remain warm and domestic while the lab can be rougher and more functional.

## 3. Suggested size

Initial target:

- approximately 35–55 m² internal area;
- covered external work apron;
- lockable component/tool store;
- optional small loft/mezzanine for light storage.

## 4. Functional zones

Recommended zoning:

```text
┌─────────────────────────────────────────────┐
│                 WORKSHOP / LAB              │
│                                             │
│  WOOD / GENERAL        METAL / BENCH        │
│  FABRICATION           FABRICATION          │
│                                             │
│  ┌───────────┐        ┌──────────────┐      │
│  │ bench     │        │ vice / tools │      │
│  │ saws      │        │ drill press  │      │
│  └───────────┘        └──────────────┘      │
│                                             │
│  ELECTRONICS /         DIGITAL FAB          │
│  TEST BENCH            / PRINTING           │
│                                             │
│  ┌───────────┐        ┌──────────────┐      │
│  │ soldering │        │ 3D printers  │      │
│  │ scopes    │        │ CAD station  │      │
│  └───────────┘        └──────────────┘      │
│                                             │
│  COMPUTE / STORAGE     PARTS / SPARES       │
│  (enclosed clean zone)                     │
└───────────────────────────┬─────────────────┘
                            │
                    COVERED WORK APRON
```

## 5. General workshop zone

Functions:

- hand tools;
- drilling;
- cutting;
- clamping;
- bike repair;
- irrigation repair;
- general household maintenance.

Canonical visual features:

- robust timber workbench;
- pegboard/tool wall;
- labelled drawers;
- vice;
- clamps;
- shelves;
- portable lights;
- worn floor;
- recognisable old stool.

## 6. Electronics lab

This should be visually distinct from the dirty workshop.

Functions:

- soldering;
- microcontroller work;
- sensor assembly;
- cable repair;
- PCB inspection;
- radio/LoRa experiments;
- equipment diagnosis.

Canonical equipment:

- soldering station;
- multimeter;
- oscilloscope;
- bench power supply;
- magnifier;
- small component drawers;
- antistatic mat;
- laptop/terminal;
- labelled test leads;
- spare ESP32-class boards;
- radios;
- environmental sensors.

## 7. Digital fabrication zone

Functions:

- 3D printing;
- light CAD;
- enclosure production;
- jigs;
- replacement parts;
- prototyping.

Canonical equipment:

- 1–2 enclosed 3D printers;
- filament storage;
- CAD workstation;
- measuring tools;
- calipers;
- print-cleaning area.

A laser cutter or CNC machine can be added later only if story or practical use justifies it.

## 8. Metal/general fabrication zone

The comic should keep this plausible and ordinary.

Possible equipment:

- angle grinder;
- drill press;
- vice;
- portable MIG welder;
- metal stock rack;
- fireproof work surface.

The workshop is not an industrial machine shop.

## 9. Wood zone

Possible equipment:

- track saw;
- mitre saw;
- router;
- sanding tools;
- drill/drivers;
- clamps;
- timber rack.

Dust extraction and separation from electronics should be visually credible.

## 10. Compute / storage clean room

A small enclosed, filtered, relatively clean technical zone may contain:

- NAS;
- backup server;
- local compute nodes;
- network distribution;
- spare SSDs;
- UPS/battery-backed low-voltage equipment.

This zone should not look like a hyperscale data centre.

Think:

> **small private server room inside a rural workshop.**

## 11. Spares and inventory

A central theme of the node is component competence.

The lab should visibly store:

- connectors;
- cable;
- fasteners;
- pipe fittings;
- relays;
- sensors;
- pumps/valves;
- spare network hardware;
- power supplies;
- batteries;
- common repair materials.

The AI/house system can track inventory, but the physical storage remains human-readable.

## 12. Safety

Canonical safety features should include:

- ventilation;
- fire extinguisher;
- fire blanket;
- eye protection;
- PPE storage;
- clear egress;
- separated flammables;
- isolated welding/grinding area;
- first-aid kit;
- obvious electrical shut-off.

## 13. Security

The workshop holds valuable tools and electronics.

Practical defensive design should focus on:

- strong doors;
- ordinary alarm sensors;
- local cameras;
- lighting;
- secure tool cabinets;
- separation from the house.

Avoid weaponised or harmful autonomous security systems.

## 14. Story-state variants

- `SA01_W1_BASE`
- `SA01_W1_ACTIVE_REPAIR`
- `SA01_W1_NIGHT`
- `SA01_W1_WILDFIRE_ALERT`
- `SA01_W1_POWER_FAULT`
- `SA01_W1_POST_STORM`
- `SA01_W1_EXPANSION`

## 15. Canonical camera set

- `CAM-SA01-W1-01` — entrance wide
- `CAM-SA01-W1-02` — electronics bench close
- `CAM-SA01-W1-03` — general workbench two-shot
- `CAM-SA01-W1-04` — printer/CAD corner
- `CAM-SA01-W1-05` — server-room doorway
- `CAM-SA01-W1-06` — covered apron looking inward
- `CAM-SA01-W1-07` — exterior house/workshop relationship

## 16. Visual identity

The workshop should look used.

Important recurring details might include:

- old climbing sticker on a tool cabinet;
- battered metal mug;
- hand-written labels;
- repaired radio;
- half-finished sensor project;
- wall map;
- old wooden stool;
- visible scraps from earlier story repairs.

## 17. Relationship to Field Manual

This building is the natural setting for practical links such as:

- TECH-013 environmental sensor network;
- TECH-014 Kastel Field Node;
- TECH-018 flood-level node;
- BUILD-001 off-grid environmental node;
- future 3D-printing / electronics builds.

## 18. Modelling priority

The first workshop model should prioritise:

1. external shell;
2. floor plan;
3. main workbench;
4. electronics bench;
5. tool wall;
6. digital fabrication corner;
7. clean compute room;
8. covered apron;
9. connection to site path;
10. saved cameras.

Fine prop detail can accumulate issue by issue.
