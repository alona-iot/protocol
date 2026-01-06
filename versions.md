# Protocol Versioning

Each message MUST include a version field:

```
"v": 1
```

## Rules

- Patch changes: documentation only
- Minor changes: backward compatible (optional fields)
- Major changes: breaking changes

Backend MUST:
- Accept current version
- Accept previous major version

Firmware SHOULD:
- Never silently change message meaning
