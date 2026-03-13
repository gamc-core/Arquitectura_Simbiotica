# REGIME — EXECUTION EXAMPLES

This document defines the structural format used to record
execution traces produced within the REGIME protocol.


---

## Example 01 — Initial Execution Trace

An actor executes structural acts within an experimental environment.

```bash
EXECUTION TRACE — gmc-ET01

Origin: gmc  
Environment: experimental runtime  
Date: 2026  

Condition  
Finite operational window declared.

Act  
Structural act executed within the environment.

Record  
Execution record stored in repository.

Evidence  
Repository commit and recorded output.

Trajectory  
Record appended to system trajectory.

State  
Active regime.
```

---

## Example 02 — Experiment Referencing Previous Experiment

A second experiment observes a previous execution and references it as part of its condition.

```bash
EXECUTION TRACE — gmc-ET02

Origin: gmc  
Environment: experimental runtime
Date: 2026  

Condition  
Observation of previous experiment.

Reference  
gmc-ET01

Reference Location (optional)  
https://example.com/gmc-ET01

Act  
New structural act executed.

Record  
Execution trace stored in repository.

Evidence  
Repository commit.

Trajectory  
Trace appended to system trajectory.

State  
Closure.
```

---

## RELATED DOCUMENTS

REGIME — Structural Experimental Protocol  
Defines the structural model and execution cycle of the REGIME system.

REGIME — Entry Point 01  
Defines the minimal entry interface required to execute experiments within REGIME.

---

End of document.