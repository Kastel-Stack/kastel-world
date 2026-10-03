# TECH-001 — Local AI Workstation

**Reality status:** REAL NOW  
**Capability:** run useful AI models locally without sending every task to an external cloud  
**Difficulty:** intermediate  
**Cost band:** ££–£££  
**Internet required:** optional after software/models are downloaded  
**Self-hostable:** yes  
**Professional installation:** no, for ordinary workstation use  
**Last reviewed:** 2026-10-03

## In everyday language

A local AI workstation lets a household or node:

- chat with locally stored models;
- search private documents;
- summarise notes;
- assist with coding;
- transcribe audio;
- analyse images;
- support local automation;
- keep sensitive work off external AI services when desired.

It does not make the node independent of the wider AI ecosystem: models, software updates and hardware still come from external supply chains.

## Present-day components

Typical stack:

```text
modern high-memory workstation
→ local model runtime
→ private web interface
→ optional document/RAG layer
→ local network
```

Useful current anchors:

- Ollama — https://ollama.com/
- llama.cpp — https://github.com/ggml-org/llama.cpp
- Open WebUI — https://openwebui.com/

## Offline behaviour

Once models and dependencies are present, many tasks can continue with no internet connection.

Cloud models may still be used selectively for tasks requiring greater capability.

## Failure modes

- insufficient memory for the selected model;
- slow inference;
- model hallucination;
- storage failure;
- software update breakage;
- excessive power draw during off-grid operation.

## Safety / decision boundary

Local AI should not autonomously control high-consequence systems merely because it is local.

For safety-critical home functions:

> AI may interpret and advise; deterministic controls and human judgement remain authoritative.

## Related Builds

- BUILD-002 — Private AI box (planned)

## Comic use

A Kastel node may switch from cloud AI to local AI during connectivity loss, or keep sensitive research local while using Blue Rail services for public-facing work.
