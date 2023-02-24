# Portmaster Operational Data

### notifications.yaml

Operational messages, warnings and other information broadcasted to all Portmaster instances.

__Testing__

- Put Portmaster into Dev Mode.
- Run `curl --upload-file notifications.yaml http://127.0.0.1:817/api/v1/broadcasts/simulate`

Other helpful things:
```
# View matching data
curl http://127.0.0.1:817/api/v1/broadcasts/matching-data

# Reset state
curl -X POST http://127.0.0.1:817/api/v1/broadcasts/reset-state
```
