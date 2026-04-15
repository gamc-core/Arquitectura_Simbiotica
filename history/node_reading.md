# ENDO — NODE READING

---

## ENTRY

Minimal reading protocol for node execution history.

No interpretation.
  
Only structural reading.

---

## QUICK PROTOCOL

1. Did it close?

→ [execution_traces](history/node00-gamc/execution_traces)  


2. What exists?  

→ [snapshots](history/node00-gamc/snapshots/)  

3. How does it behave?  

→ [trajectory](history/node00-gamc/trajectory/)  

4. What is the current state? 

→ [latest](history/node00-gamc/latest.json)  

---

FLOW:

CLOSURE → STATE → DYNAMICS → CURRENT  

---

## LAYERS

Each node exposes:

- execution_trace → closure  
- snapshot → captured state  
- trajectory → structural dynamics  
- latest → current cut  

All layers derive from the same runtime instance within the node.

---

## ACTIVE NODES

node00-gamc

Origin node currently exposed.

---

## READING

### 1. EXECUTION TRACE

Confirms closure.

- EXISTS → closed  
- NOT EXISTS → not closed  

---

### 2. SNAPSHOT

Observes captured state.

- closed = false → open  
- closed = true → closed  

---

### 3. TRAJECTORY

Observes structural dynamics.

READ ORDER:

- intra → state  
- inter → transition  
- structure → organization  
- lineage → memory  

---

CORE SIGNALS:

- emission_density  
- reference_usage  
- chain_linearity  
- generation_delta  
- regime_behavior  
- lineage_avg_length  
- lineage_avg_depth  

---

### 4. LATEST

Current system cut.

- closed = false → active  
- closed = true → closed  

---

## GLOBAL CHECKS

- Did it close? → execution_trace  
- What exists? → snapshot  
- Is it connected? → reference_usage  
- Did it break? → chain_linearity  
- Is it expanding? → generation_delta  
- Does it persist? → regime_behavior  
- Does it remember? → lineage_avg_depth  
- What is current? → latest  

---

## DEFINITION

Reading is structural.

No:

- narrative  
- intention  
- interpretation  

Only:

- state  
- transition  
- relation  

---

## CONSOLIDATION

A system is correctly read when:

- closure is confirmed  
- state is observable  
- dynamics are traceable  
- memory is identifiable  
- current state is clear  

All layers converge into a single structural reading.