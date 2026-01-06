# Heartbeat Message

Topic:
```
alona/{node_id}/heartbeat
```

Payload:
```json
{
  "v": 1,
  "ts": 1700000000,
  "uptime": 3600,
  "rssi": -67
}
```

Sent periodically to indicate liveness.
