# sdcore-github-workflows

This repository stores GitHub workflows used by Charmed SD-Core operators.


## Renovate base configuration

This repository contains a base Renovate configuration. To use it in other
projects, create a `renovate.json5` file with the following content:

```json
{
    "$schema": "https://docs.renovatebot.com/renovate-schema.json",
    "extends": ["https://raw.githubusercontent.com/canonical/sdcore-github-workflows/refs/heads/main/renovate.json5"]
}
```
