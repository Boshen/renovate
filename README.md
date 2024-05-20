# My shared renovate config for Rust projects

Example:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>Boshen/renovate"],
  "packageRules": [
    {
      "groupName": "rust crates",
      "matchManagers": ["cargo"]
    }
  ]
}
```

## `automergeType=branch`

Add the `renovate/**` branch to your testing workflow files, or Renovate will not work properly with the `automergeType=branch` setting.

* https://docs.renovatebot.com/configuration-options/#automergetype
* https://docs.renovatebot.com/key-concepts/automerge/#branch-vs-pr-automerging
