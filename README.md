# pre-commit-hooks
Hooks for use with [pre-commit](https://pre-commit.com/)

## Available hooks

* `go-mod-vendor` - Runs `go mod vendor` and asserts all dependencies have been vendored.

## Configure `pre-commit`

Create or append to your `.pre-commit-config.yaml` configuration:

```yaml
- repo: https://github.com/Aneurysm9/pre-commit-hooks
  rev: v0.0.2
  hooks:
  - id: go-mod-vendor
```

## License

`pre-commit-hooks` is open source software released under the [MIT license](https://opensource.org/licenses/MIT).
