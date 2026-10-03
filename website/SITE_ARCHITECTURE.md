# Website Architecture

## Homepage

# KASTEL

### Build worlds worth living in.

Primary doors:

**The Comic**  
Enter the fictional world.

**The Atlas**  
Explore Kastel's future.

**The Field Manual**  
Build what already exists.

**The Commons**  
Open designs, software and knowledge.

**The Community**  
Share builds and learn from others.

**The Vision**  
Why Kastel exists.

Footer proposition:

> **Fiction is the laboratory.**  
> **The Commons is the bridge.**  
> **Reality is the test.**

## Information architecture

```text
/
├── comic/
│   ├── issues/
│   └── characters/
├── atlas/
│   ├── world/
│   ├── nodes/
│   ├── timeline/
│   └── technology/
├── field-manual/
│   ├── compute/
│   ├── communications/
│   ├── home/
│   ├── land/
│   ├── resilience/
│   ├── workshop/
│   ├── knowledge/
│   └── mobility/
├── builds/
├── commons/
├── community/
└── vision/
```

## Reader journeys

### Fiction-first
Comic → TECH marker → Field Manual → Build.

### Technology-first
Search "offline knowledge" → TECH-004 → related comic scenes → Build.

### Worldbuilding-first
Atlas node → house cutaway → room → characters → issues.

### Community-first
Build log → canonical Build → Field Manual → related fictional technology.

## Node page

Each canonical node may eventually show:

- regional map;
- node overview;
- 3D/cutaway view;
- buildings;
- residents;
- businesses;
- systems;
- issue history;
- technology links;
- current canonical state.

## Technology page

Show immediately:

- reality-status badge;
- plain-English capability;
- difficulty;
- cost band;
- internet dependence;
- open/self-hosted status;
- safety/professional boundary;
- official links;
- Builds;
- comic appearances;
- last review date.

## Comic page

Do not turn the comic reader into a documentation user.

Technology links should be optional and visually secondary.

## Community architecture

Early community can be GitHub Discussions or a conventional forum. Avoid building a custom social platform before there is evidence of demand.

## Website implementation principle

The content model should preserve stable IDs so the site can be rebuilt on different frameworks without breaking comic references.
