# Alona IoT — Protocol

This repository defines the **communication contracts** used by the Alona IoT system.

It documents:

- MQTT topic conventions
- payload schemas for telemetry, events, and heartbeats
- versioning and compatibility rules
- example messages exchanged between devices and backend

The goal is to keep device firmware and backend loosely coupled while sharing a clear, explicit interface.

## Scope

- Topic hierarchy (`devices/<id>/...`)
- Message types (telemetry, events, heartbeat)
- Required and optional fields
- Schema evolution guidelines

## Why a Separate Repository?

Keeping the protocol isolated:

- makes contracts explicit
- simplifies firmware/backend evolution
- improves long-term maintainability

## Related Repositories

- `firmware` — publishes messages following this protocol
- `core` — consumes and validates messages
