# Lab 27 — Propagation Warnings

| Pattern | Risk |
| --- | --- |
| REQUIRES_NEW on log | Log commits even if money rolls back |
| Self-invocation | @Transactional ignored; proxy not used |
| Swallow exception | No rollback triggered |
| TX on controller | Wrong boundary; mixes HTTP with business rules |

## Lab default
REQUIRED on TransferService.transfer

## Scope
Pre-lab only.
