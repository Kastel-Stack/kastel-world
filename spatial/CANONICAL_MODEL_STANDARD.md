# Canonical Model Standard

## Purpose

Canonical 3D models provide spatial ground truth for the comic.

They do not need architectural-construction accuracy unless the story requires it. They do need enough accuracy to preserve:

- scale;
- adjacency;
- perspective;
- furniture placement;
- character movement;
- recurring visual identity.

## Location package

Each major location should contain or reference:

1. **Site context**
   - terrain;
   - north orientation;
   - roads;
   - neighbouring features;
   - vegetation zones.

2. **Building shell**
   - walls;
   - floors;
   - roof;
   - windows;
   - doors;
   - stairs.

3. **Functional interior**
   - kitchen;
   - living spaces;
   - workspaces;
   - technical rooms;
   - storage;
   - circulation.

4. **Dressing**
   - furniture;
   - wall colours;
   - materials;
   - lights;
   - rugs;
   - art;
   - books;
   - plants;
   - personal objects.

5. **Technical objects**
   - screens;
   - network equipment;
   - workshop tools;
   - sensors;
   - water/energy controls.

6. **Persistent props**
   Objects readers can recognise across issues.

## Story state

Never overwrite important narrative change without preserving the prior state.

Example:

```text
SA01_BASE
SA01_ISSUE003_WILDFIRE
SA01_ISSUE004_AFTER_FIRE
SA01_ISSUE009_WORKSHOP_EXTENSION
```

A broken window, new greenhouse, damaged roof or changed painting should persist until the story changes it.

## Camera canon

Named cameras turn locations into reusable comic sets.

Example control-room set:

- `CAM-SA01-CTRL-01` — doorway wide;
- `CAM-SA01-CTRL-02` — desk two-shot;
- `CAM-SA01-CTRL-03` — over-shoulder map wall;
- `CAM-SA01-CTRL-04` — console close-up;
- `CAM-SA01-CTRL-05` — high emergency angle.

Store:

- position;
- focal length;
- framing notes;
- intended panel types.

## Decorative continuity

Small recurring details help make the node feel inhabited.

Examples:

- a distinctive kettle;
- a badly framed painting;
- a particular chair;
- a battered field radio;
- an old map;
- a child's drawing;
- a plant that grows over several issues.

These are canon, not incidental texture.

## Asset provenance

Every third-party asset should have a recorded licence/provenance note.

Do not import assets whose redistribution or publication rights are unclear.
