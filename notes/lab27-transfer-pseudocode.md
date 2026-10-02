# Lab 27 — Transfer Pseudocode

## Annotation / method
@Transactional on transfer(from, to, amount, correlation)

## Force-fail check
If `to == ACC-FORCE-FAIL`, throw to trigger rollback

## Money steps
Load accounts; debit `from`; credit `to`

## Log step
Write TransactionLog with correlation before commit

## Scope
Pre-lab only.
