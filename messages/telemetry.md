# Telemetry Message

Topic:
```
alona/{node_id}/telemetry/{sensor}
```

Payload:
```json
{
  "v": 1,
  "ts": 1700000000,
  "sensor": "temperature",
  "value": 21.4,
  "unit": "celsius"
}
```

Notes:
- `ts` is Unix epoch (seconds)
- `value` must be numeric
