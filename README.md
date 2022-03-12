# renovate config

## usage

- renovate.json

```json
{
    "extends": ["github>re-taro/renovate"]
}
```

- package.json

```json
{
  "name": "renovate-config",
  "version": "0.0.1",
  ...
  "renovate-config": {
    "default": {
      "extends": ["github>re-taro/renovate"]
    }
  }
}
```
