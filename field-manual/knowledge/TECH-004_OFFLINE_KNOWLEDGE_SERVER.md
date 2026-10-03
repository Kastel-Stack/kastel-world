# TECH-004 — Offline Knowledge Server

**Reality status:** REAL NOW  
**Capability:** keep a useful reference library available on the local network when the internet is unavailable  
**Difficulty:** beginner/intermediate  
**Cost band:** £  
**Internet required:** only to acquire/update content  
**Self-hostable:** yes  
**Professional installation:** no  
**Last reviewed:** 2026-10-03

## In everyday language

An offline knowledge server can keep locally searchable copies of:

- Wikipedia;
- dictionaries;
- selected educational material;
- manuals;
- local maps;
- public-domain books;
- house documentation.

The key resilience benefit is that an internet outage becomes mainly a loss of **current information**, rather than a loss of basic reference knowledge.

## Present-day anchor

Kiwix is a mature open-source platform for serving offline web content.

Official project:

- https://www.kiwix.org/

## Typical architecture

```text
small computer / server
+ SSD
+ Kiwix library
+ local web server
→ available to phones/laptops on the LAN
```

## Limits

- content becomes stale;
- not every website can legally or technically be mirrored;
- emergency/medical information still requires appropriate professional context;
- storage requirements rise quickly for large collections.

## Related Builds

- BUILD-003 — Offline knowledge server (planned)

## Comic use

A node may retain maps, technical manuals or encyclopaedic reference during a wider communications outage.
