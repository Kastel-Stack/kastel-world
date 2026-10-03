# Content Linking Standard

The distinguishing feature of Kastel World is the ability to move from a fictional panel to progressively deeper real-world material.

## Identifier families

- `TECH-001` — technology or capability
- `BUILD-001` — practical build
- `NODE-SA-01` — fictional node
- `CHAR-001` — character
- `BLUE-001` — Blue Rail institution/system pattern
- `ISSUE-001` — comic issue

Identifiers are permanent once published.

## Comic → website

A panel should not be cluttered with URLs.

Preferred mechanisms:

1. end-of-issue technology index;
2. clickable digital-panel marker;
3. small QR code in print;
4. issue webpage listing referenced entries.

## Technology-page minimum metadata

```yaml
id: TECH-001
title:
status: REAL_NOW
capability:
cost_band:
difficulty:
internet_required:
self_hostable:
professional_installation:
official_links:
related_builds:
comic_appearances:
limitations:
last_reviewed:
```

## Link hierarchy

Prefer:

1. official/open-source project documentation;
2. standards bodies;
3. government/public authority guidance;
4. manufacturer documentation;
5. high-quality independent technical sources.

Avoid making affiliate links the evidential backbone of the Field Manual.

## Versioning

Technology moves faster than canon.

Therefore:

- comic references point to permanent IDs;
- Field Manual pages can be updated;
- old technical claims should retain a revision history;
- "last reviewed" dates are mandatory for fast-moving technologies.

## Example

Comic panel:

> The Garden Node switches to local mode as the fibre link fails.

Issue notes:

- `TECH-004 Local-first home control`
- `TECH-009 Multi-WAN connectivity`
- `BUILD-003 Offline knowledge server`

The reader can ignore those links and continue the story, or follow them into reality.
