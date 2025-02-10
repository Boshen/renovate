# My shared renovate config for Rust projects

Example:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>Boshen/renovate"]
}
```

## `automergeType=branch`

Add the `renovate/**` branch to your testing workflow files, or Renovate will not work properly with the `automergeType=branch` setting.

In GitHub repo /settings/actions, enable "Workflow permissions":

* Read and write permissions
* Allow GitHub Actions to create and approve pull requests

* https://docs.renovatebot.com/configuration-options/#automergetype
* https://docs.renovatebot.com/key-concepts/automerge/#branch-vs-pr-automerging

## Website

[developer.mend.io](https://developer.mend.io)
