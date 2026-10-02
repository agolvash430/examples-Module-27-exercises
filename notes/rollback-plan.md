# Lab 27 — Rollback Evidence Plan

## Before measurement
Record ACC‑1001‑MAIN balance before triggering the transfer

## Force-fail action
POST a transfer using destination ACC‑FORCE‑FAIL to trigger the error path

## After assertions
Expect error response; confirm MAIN balance unchanged and no success TransactionLog row

## Evidence location
Screenshot/notes stored under lab-27/

## Scope
Pre-lab only.
