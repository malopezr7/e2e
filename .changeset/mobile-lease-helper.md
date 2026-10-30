---
'@e2e-dev/mobile': patch
---

Add `@e2e-dev/mobile/lease` for device-provider packages: `agentDeviceLeases()` leases devices from a cloud agent-device runs sessions on, one isolated daemon per worker slot, and fails a release that agent-device can't confirm ended the session.
