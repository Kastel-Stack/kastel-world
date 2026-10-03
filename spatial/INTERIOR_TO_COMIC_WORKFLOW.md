# Interior-to-Comic Workflow

This document defines the initial production workflow for recurring Kastel interiors.

## Goal

Create a permanent 3D interior once, then project consistent 2D images from it for comic production.

The 3D scene fixes:

- room geometry;
- perspective;
- furniture;
- wall colours;
- lighting logic;
- props;
- character position;
- camera angle;
- continuity.

The final comic does **not** need to look like a 3D render.

## Workflow

### 1. Block out the room
Use SketchUp or Blender.

Define:

- dimensions;
- doors/windows;
- furniture zones;
- movement routes;
- technical equipment.

### 2. Dress the room
Add:

- furniture assets;
- colours;
- materials;
- lights;
- books;
- plants;
- artwork;
- tools;
- personal objects.

AI can assist with concept palettes, prop ideation and rapid visual references, but canonical geometry and object identity should remain controlled.

### 3. Create named cameras
Save 5–10 recurring views for important rooms.

Typical set:

- establishing wide;
- conversation two-shot;
- over-the-shoulder;
- close-up work surface;
- doorway;
- dramatic high/low angle.

### 4. Place canonical characters
Characters should use persistent models or tightly controlled visual references.

Record:

- height;
- proportions;
- wardrobe;
- hair;
- recurring accessories.

### 5. Create scene state
Set:

- time;
- weather;
- lights;
- screen contents;
- props;
- damage;
- temporary objects.

### 6. Render neutral base
The render should prioritise clean perspective and readable forms over photorealism.

Useful render variants may include:

- flat colour;
- shadow pass;
- line pass;
- depth pass;
- object-ID mask.

### 7. Comic stylisation
Possible routes:

- Clip Studio 3D-to-line/tone tools;
- Blender Grease Pencil;
- hand draw-over;
- controlled image-to-image stylisation;
- mixed manual + AI paint-over.

AI should transform the canonical composition rather than invent the set anew.

### 8. Lettering and panel assembly
Use a dedicated comic layout tool for:

- panel borders;
- speech balloons;
- captions;
- sound effects;
- page flow.

### 9. Record shot metadata

Example:

```yaml
issue: ISSUE-004
page: 12
panel: 3
node: NODE-SA-01
room: ROOM-SA-01-CONTROL
camera: CAM-SA01-CTRL-03
lens_mm: 38
time: "17:42"
weather: smoky
scene_state: SA01_ISSUE004
characters:
  - CHAR-002
tech_refs:
  - TECH-017
```

## Production advantage

A long-running series benefits enormously from this model:

- perspective stays coherent;
- rooms stay recognisable;
- action geography makes sense;
- backgrounds become cheaper over time;
- story-state changes persist;
- the same assets can later feed an interactive Atlas.

The 3D world is therefore not merely an art shortcut. It is part of Kastel's canon infrastructure.
