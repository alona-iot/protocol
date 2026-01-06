# MQTT Topics

Base namespace:

```
alona/{node_id}/...
```

## Topics

- `alona/{node_id}/telemetry/{sensor}`
- `alona/{node_id}/event/{type}`
- `alona/{node_id}/heartbeat`
- `alona/{node_id}/status`
- `alona/{node_id}/error`

### Rules
- `{node_id}` is immutable per device
- Topics must be lowercase
- No wildcards in publishing
