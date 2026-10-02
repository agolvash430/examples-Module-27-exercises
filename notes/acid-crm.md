# Lab 27 — ACID for CRM Transfers

| Letter | CRM observation |
| --- | --- |
| A | Forced fail leaves MAIN unchanged; no success log written |
| C | After happy path, balances and transfer log match consistently |
| I | Default isolation; no dirty or mid‑transfer reads required for Pass |
| D | Committed happy path survives restart (note H2 mode caveat) |

## Scope
Pre-lab only.
