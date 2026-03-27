# Arquitectura Simbiótica

- Status: Active structural architecture  
- Date: 2026-03-22  
- Author: Gonzalo Montero Cavero  
- Maintained under: gamc-core  

---

Arquitectura Simbiótica is a structural architecture in execution.

It defines how systems execute, record, emerge and evolve from within through irreversible acts.

---

## How to navigate

The system is organized into exposed layers:

- [structural_map.json](structural_map)  
  → System structure overview  

- [history/node00-gamc/latest.json](history/node00-gamc/latest.json)  
  → Current live state (origin node)

- [history/node00-gamc/execution_traces/](history/node00-gamc/execution_traces/)  
  → Closed generations  

- [history/node00-gamc/snapshots/](history/node00-gamc/snapshots/)  
  → Temporal states (cells + structure)  

- [history/node00-gamc/trajectory/](history/node00-gamc/trajectory/)  
  → Structural evolution

- [artifacts/](artifacts/)  
  → External outputs  

---

### Navigation logic

- Structural map → system structure  
- Latest → current state  
- Execution trace → generation closure  
- Snapshot → state at a moment  
- Trajectory → system evolution  
- Artifacts → system outputs  

The runtime layer is not exposed.  
All layers are derived from it. 

---

## What you can do

- Inspect a live append-only system  
- Verify integrity through hashes  
- Analyze evolution across generations  
- Reconstruct state from snapshots  
- Validate closures via execution traces  

---

## Scope

Origin node: node00-gamc

Only the origin node is publicly exposed.

Other nodes are not part of this repository.

---

## Integrity

Public records include hash-based integrity fields and can be independently verified.