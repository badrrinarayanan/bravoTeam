# ADR-000: ADR template

## Date:
2025-03-25

## Status:
Proposed

## Context:
We need a interview dashboard that needs to hold a log of interview process and their status. For this, we need event updates to be published by greenhouse.

## Decision:
We will rely on greenhouse application to trigger an event on our system and update the database

## Consequences:
Without these notifications, we would not be able to keep track of the interview process and their status.
