# Spatial Canon

The spatial layer gives Kastel World a fixed physical reality beneath the comic.

The principle is:

> **Model once. Reuse for years.**

A canonical location should be able to generate:

- floor plans;
- exterior views;
- interior views;
- cutaways;
- establishing shots;
- action blocking;
- consistent travel distances;
- comic-panel camera views;
- later interactive Atlas content.

## Preferred tool chain

A practical starting stack:

```text
open/licensable geographic data
→ QGIS
→ SketchUp or direct Blender blockout
→ Blender master scene
→ optional BIM/IFC layer
→ character/prop placement
→ saved cameras
→ neutral render
→ comic stylisation
```

Possible supporting tools:

- QGIS for geography and site context;
- OpenStreetMap-derived data for roads/buildings where licence-compatible;
- Copernicus/open elevation data for terrain;
- SketchUp for rapid architectural blockout;
- Blender for canonical scene assembly, lighting, cameras and versioned story state;
- Bonsai/IFC if more formal building semantics are useful;
- Clip Studio Paint EX or equivalent for final comic page production;
- Character Creator/iClone or Blender character rigs if persistent character models are needed.

## Google rule

Google Earth and Street View can be useful for private visual familiarisation, but should not be the canonical production substrate.

Do not build publishable geometry by tracing or extracting Google imagery.

## First canonical site package

The first worked spatial package is `SITE-SA-01`:

- [House K1 specification](./nodes/SA01_HOUSE_K1_SPEC.md)
- [Workshop / Lab W1 specification](./nodes/SA01_WORKSHOP_LAB_SPEC.md)
- [Site layout](./nodes/SA01_SITE_LAYOUT.md)

These documents define the initial physical grammar for the South African Garden Node and are the basis for the first 3D blockout.

## Interior production

See:

- [Canonical Model Standard](./CANONICAL_MODEL_STANDARD.md)
- [Interior-to-Comic Workflow](./INTERIOR_TO_COMIC_WORKFLOW.md)

The intended production model is:

```text
canonical 3D room
→ persistent furniture / colours / props
→ saved camera
→ neutral render
→ comic stylisation
→ final panel
```

## Directory intent

Future large binary assets should be stored using an appropriate large-file workflow (for example Git LFS or external asset storage). GitHub should retain:

- manifests;
- source licences;
- asset IDs;
- camera lists;
- state files;
- model notes;
- screenshots;
- lightweight previews;
- revision history.

## Spatial IDs

Recommended pattern:

- `LOC-SA-01` — regional location
- `SITE-SA-01` — node site
- `BLDG-SA-01-HOUSE-K1`
- `BLDG-SA-01-LAB-W1`
- `ROOM-SA-01-CONTROL`
- `CAM-SA-01-CONTROL-03`
- `STATE-SA-01-ISSUE-004`

The goal is reproducibility and continuity, not bureaucracy.
