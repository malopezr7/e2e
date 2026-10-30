---
'@e2e-dev/testmu': patch
---

A device release now fails the run when agent-device can't confirm it ended the TestMu AI session: a forced daemon stop, a lost shutdown report, or a daemon that exited during the run. Needs `@e2e-dev/mobile` 0.12.5 or later.
