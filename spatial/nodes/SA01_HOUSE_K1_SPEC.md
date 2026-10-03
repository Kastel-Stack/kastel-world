# SA-01 House K1 — Canonical Building Specification

**Asset ID:** `BLDG-SA-01-HOUSE-K1`  
**Node:** `NODE-SA-01`  
**Status:** canonical concept v0.1  
**Type:** compact modular autonomous house  
**Target occupancy:** 2–3 permanent/rotating residents, with short-stay guest capacity  
**Target internal area:** approximately 60–75 m², excluding decks and detached workshop/lab  
**Reference lineage:** South African modular/off-grid architecture, especially ECOMO-style pod logic  
**Construction status:** fictional Kastel derivative, not a reproduction of a proprietary house plan

## 1. Purpose

House K1 is the primary domestic building for the South African Garden Node.

It should feel:

- compact rather than luxurious;
- technologically advanced without looking like a laboratory;
- warm, calm and lived-in;
- architecturally plausible for inland Garden Route / Klein Karoo conditions;
- capable of operating comfortably during infrastructure disruption;
- suitable for recurring comic scenes;
- simple enough to model once and reuse for years.

The house is deliberately not a bunker.

Its visual identity should communicate:

> **ordinary human life + quiet technical competence + environmental fit.**

## 2. Architectural grammar

The house takes inspiration from modular South African pod-based architecture:

- rectilinear modules;
- strong indoor/outdoor relationship;
- covered decks/stoeps;
- clear separation between social and private spaces;
- straightforward expansion logic;
- elevated or carefully drained foundations;
- strong solar orientation;
- robust shading.

The exact fictional building should be its own design.

The goal is to use the modular grammar rather than copy a real copyrighted plan.

## 3. Core layout

Recommended first canonical arrangement:

```text
                         NORTH / MAIN VIEW

                ┌─────────────────────────┐
                │     COVERED STOEP       │
                │  outdoor table / seats  │
                └───────────┬─────────────┘
                            │
        ┌───────────────────┴────────────────────┐
        │                                        │
        │          LIVING / DINING /             │
        │              KITCHEN                   │
        │                                        │
        │   open-plan social / work core         │
        │                                        │
        └──────────────┬───────────┬─────────────┘
                       │           │
             ┌─────────┘           └─────────┐
             │                               │
      ┌──────┴──────┐                 ┌──────┴──────┐
      │ BEDROOM 1   │                 │ BEDROOM 2 / │
      │             │                 │ FLEX / GUEST│
      │             │                 │             │
      └──────┬──────┘                 └──────┬──────┘
             │                               │
      ┌──────┴──────┐                 ┌──────┴──────┐
      │ BATHROOM    │                 │ STUDY /     │
      │ + STORAGE   │                 │ CONTROL     │
      └─────────────┘                 └──────┬──────┘
                                             │
                                      ┌──────┴──────┐
                                      │ UTILITY /   │
                                      │ TECH CLOSET │
                                      └─────────────┘
```

This diagram is spatial logic, not a final construction drawing.

## 4. Room schedule

### 4.1 Living / dining / kitchen

The emotional centre of the house.

Functions:

- communal meals;
- informal meetings;
- reading;
- planning;
- cooking;
- guest hosting;
- everyday comic dialogue;
- occasional laptop work.

Visual character:

- warm timber;
- pale mineral/plaster walls;
- matte finishes;
- large shaded glazing;
- visible books;
- plants;
- one or two recognisable recurring objects;
- practical rather than showroom furniture.

Canonical recurring props may include:

- blue enamel kettle;
- battered field radio;
- wall map;
- long timber table;
- mismatched mugs;
- old mechanical clock;
- one deliberately odd artwork that becomes a running visual joke.

### 4.2 Bedroom 1

Primary permanent bedroom.

Keep visually simple:

- bed;
- built-in storage;
- reading light;
- personal shelf;
- view to landscape;
- no high-tech aesthetic.

### 4.3 Bedroom 2 / flex room

Can function as:

- guest room;
- rotating resident room;
- temporary researcher room;
- occasional editing/work room.

This flexibility supports the node's rotating-residency model.

### 4.4 Bathroom

Compact, water-conscious and robust.

Features may include:

- low-flow fittings;
- simple tiled/washable surfaces;
- mechanical ventilation;
- visible water-state indicator only if visually unobtrusive.

### 4.5 Study / control room

This is the main recurring technical interior.

It should still look like a study first.

Functions:

- local AI workstation;
- node dashboard;
- GIS/map display;
- research;
- business/trading work;
- communications monitoring;
- document archive access.

Canonical equipment:

- one primary workstation;
- two large wall/desk displays;
- local map display;
- compact communications panel;
- weather/environment dashboard;
- bookshelf;
- physical notebooks;
- printed maps;
- handheld radios;
- charging drawer;
- emergency documents.

Avoid glossy sci-fi interfaces.

The room should feel like:

> **research study + field operations desk + family office.**

### 4.6 Utility / tech closet

Contains the small domestic technical core that belongs inside the main house.

Possible contents:

- network core;
- small UPS;
- patch panel;
- house automation controller;
- local alarm controller;
- environmental gateways;
- low-voltage distribution;
- selected network hardware.

The larger compute/storage and workshop functions may sit in the detached workshop/lab.

## 5. Interior style

### Palette

Recommended base:

- warm off-white;
- pale clay;
- muted olive;
- dusty green;
- natural timber;
- charcoal hardware;
- stone/concrete neutrals;
- occasional faded blue accents.

Avoid:

- sterile white;
- glossy black;
- cyberpunk lighting;
- neon accents;
- generic "AI lab" blue light.

### Materials

- timber;
- fibre cement / plaster;
- stone;
- matte metal;
- concrete;
- wool / cotton textiles;
- durable outdoor fabrics.

## 6. Exterior style

The exterior should look appropriate to a dry, fire-conscious South African landscape.

Possible language:

- dark or weathered timber/fibre-cement cladding;
- metal roof;
- wide roof overhangs;
- shaded deck;
- restrained glazing;
- screened service side;
- simple rectangular volumes;
- modest elevation above grade where useful;
- stone/gravel non-combustible zone immediately around the building.

## 7. Environmental logic

House K1 should be modelled with:

- strong cross-ventilation;
- deep shading;
- solar orientation;
- roof suitable for rainwater capture;
- external fire-conscious material choices;
- clear drainage away from the structure;
- low-maintenance landscaping near the house.

The comic model should show these visibly enough that the house feels designed rather than generic.

## 8. Technology layer

The house itself contains only the technologies that belong naturally in daily domestic life.

### Inside

- local network;
- local AI access;
- environmental sensing;
- home automation;
- local security display;
- household archive access;
- offline maps/knowledge;
- communications.

### Outside / detached

The workshop/lab may hold:

- larger compute;
- fabrication;
- electronics;
- spares;
- tools;
- experimental hardware.

### Rule

Technology should be present but visually subordinate to human habitation.

## 9. Story-state variants

At minimum create:

- `SA01_K1_BASE_DAY`
- `SA01_K1_BASE_NIGHT`
- `SA01_K1_AWAY_MODE`
- `SA01_K1_WILDFIRE_ALERT`
- `SA01_K1_POWER_DEGRADED`
- `SA01_K1_AFTER_STORM`

Later issue-specific states should branch from these.

## 10. Canonical camera set

### Living space

- `CAM-SA01-K1-LIV-01` — wide from kitchen
- `CAM-SA01-K1-LIV-02` — table conversation two-shot
- `CAM-SA01-K1-LIV-03` — stoep looking inward
- `CAM-SA01-K1-LIV-04` — living room towards landscape

### Control room

- `CAM-SA01-K1-CTRL-01` — doorway wide
- `CAM-SA01-K1-CTRL-02` — desk two-shot
- `CAM-SA01-K1-CTRL-03` — over-shoulder map wall
- `CAM-SA01-K1-CTRL-04` — close console/detail
- `CAM-SA01-K1-CTRL-05` — high emergency angle

### Exterior

- `CAM-SA01-K1-EXT-01` — front three-quarter
- `CAM-SA01-K1-EXT-02` — stoep / social side
- `CAM-SA01-K1-EXT-03` — house + workshop relationship
- `CAM-SA01-K1-EXT-04` — house against mountain/landscape

## 11. Model deliverables

The first canonical 3D package should eventually contain:

- site blockout;
- house shell;
- roof;
- glazing;
- doors;
- stoep/deck;
- all main furniture;
- control-room equipment;
- kitchen;
- core props;
- exterior material setup;
- basic vegetation;
- lighting presets;
- saved cameras;
- story-state collections.

## 12. Licensing / provenance rule

All third-party 3D assets require a provenance record.

Do not use unclear or non-publishable assets in canonical scenes.

## 13. Relationship to real precedents

The design may reference South African modular/off-grid architecture for proportion, climate logic and spatial grammar.

It should remain a **Kastel-designed fictional house** rather than a copied architectural work.

## 14. Next modelling step

Create a first dimensioned blockout using:

- 60–75 m² target internal area;
- two bedrooms;
- open living/kitchen;
- study/control room;
- bathroom;
- utility/tech closet;
- substantial covered deck;
- detached workshop/lab approximately 10–20 m away.

The blockout becomes the basis for all later refinement.
