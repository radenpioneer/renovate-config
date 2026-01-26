My shareable Renovate configuration, created for personal use.
It actually runs [SNGR Creative's config](https://codeberg.org/sngrcreative/renovate-config).
See there for clarity what configurations/preset be used.

## How to use

In your repo's `renovate.json`:

```json
"extends": [
    "github>radenpioneer/renovate-config"
]
```

Or use security-focused preset:

```json
"extends": [
    "github>radenpioneer/renovate-config:security"
]
```

See [Renovate's config](https://docs.renovatebot.com/config-presets/#extending-from-a-preset).

## Miscellaneous

This repository is stored at Codeberg (https://codeberg.org/sngrcreative/renovate-config) with mirror at GitHub (https://github.com/sngrcreative/renovate-config).