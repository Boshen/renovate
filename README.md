# My shared renovate config for Rust projects

Example:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>Boshen/renovate", "helpers:pinGitHubActionDigestsToSemver"]
}
```

## `automergeType=pr`

In GitHub Repo Settings - Enable "Allow auto-merge".

## GitHub Actions Security

Due to the insecure nature of GitHub Actions, `automerge` is disabled, `pinGitHubActionDigestsToSemver` is added. See:

* [tj-actions/changed-files action is compromised](https://www.stepsecurity.io/blog/harden-runner-detection-tj-actions-changed-files-action-is-compromised)
* [A supply chain attack on PyTorch](https://johnstawinski.com/2024/01/11/playing-with-fire-how-we-executed-a-critical-supply-chain-attack-on-pytorch)

## Website

[developer.mend.io](https://developer.mend.io)
