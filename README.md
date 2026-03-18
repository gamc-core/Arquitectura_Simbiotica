# Arquitectura Simbiótica

- Status: Active structural architecture
- Date: 2026-03-09
- Author: Gonzalo Montero Cavero
- Maintained under: gamc-core

---

Arquitectura Simbiótica is a structural architecture for systems where human activity, computational processes and environments operate as participants within the same operational structure.

The architecture studies how systems may emerge from minimal irreversible acts rather than predefined control structures.

This repository contains the structural architecture, the experimental protocol (REGIME), a set of publicly released structural artifacts, the execution traces produced during experimentation, and an observable feed of generational execution.

Infrastructure components remain under active development.

---

## Repository Structure

The repository is organized into six layers.

- architecture/  
Structural definition of the system.

- artifacts/  
Public structural artifacts produced by the system.

- infrastructure/  
Runtime implementation under active development.

- history/  
Public execution traces documenting structural events.

- regime/  
Experimental protocol defining how structural experiments are executed.

- public/feed/  
Observable snapshots of the system’s generational execution.  

This layer exposes partial structural states derived from runtime,  
without revealing internal infrastructure.

Includes:

- latest.json (current observable state)  
- snapshots/ (historical structural cuts)

---

## Integrity

Public records may include hash-based integrity fields.

These allow independent verification that:

- records have not been modified after publication
- snapshots remain internally consistent

Internal integrity is enforced by ENDO through hash chaining across runtime records.

External integrity is exposed through deterministic hashing of published snapshots and records.

---

## Status

The system is under active development. Some infrastructure components remain under private experimentation and are described here only at a high level.