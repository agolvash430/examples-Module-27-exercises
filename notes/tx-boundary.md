# Lab 27 — Transaction Boundary Placement

## Place annotation on
TransferService.transfer(...) with @Transactional

## Avoid
@Transactional on controller

## Why (one sentence)
Transactional proxy belongs on the Spring service bean so HTTP stays thin and boundaries remain clear.

## Self-invocation risk
Calling this.transfer() inside the same class bypasses the proxy and skips the transaction.

## Scope
Pre-lab only.
