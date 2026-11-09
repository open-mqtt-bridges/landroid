# Maintenance evidence

## Baseline

- Base: `ea535ff2505954505764017c6d2c51dc8bb84e0d`; tracked checkout clean before branch creation.
- Issue: https://github.com/open-mqtt-bridges/landroid/issues/42.
- Declared versions, engines, package manager and overrides: `baseline.json`.
- Target selection: stable official npm/crates.io metadata and GitHub Action releases, with version-matched migration notes before breaking changes.
- No public MQTT/API/configuration contracts are intentionally changed.

## Deferred targets

- TypeScript 7 remains deferred where typescript-eslint or ts-jest excludes it. Existing compiler aliases remain authoritative.
- Roborock 3.40.3 remains deferred unless its declared engine range supports pinned Node 26.

## Results

Implementation and validation pending.
