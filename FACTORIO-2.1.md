# Factorio 2.1 notes

Tested with **Factorio 2.1.23**. Current fork version: **1.0.1**.

## Changes

- Updated Factorio compatibility metadata to 2.1.

## Tests

- Library-generated logistics prototypes were used in belt, pipe and substation transfer tests with a connected client.
- Consumer saves loaded and rejoined successfully.

Coverage is through Matt’s Logistics; individual library helpers were not all tested independently.

Tests used private copies of saves and local host/client sessions. Raw player data and test hooks are not shipped.

The 1.0.1 patch repairs changelog formatting and version metadata only. Gameplay files are unchanged.
