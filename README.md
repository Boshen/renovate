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
