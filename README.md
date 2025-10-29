# import-linter-pre-commit

A [pre-commit](https://pre-commit.com/) hook for [import-linter](https://github.com/seddonym/import-linter).

### Usage

Add the following to your `.pre-commit-config.yaml`:

```yaml
repos:
  - repo: https://github.com/yamnikov-oleg/import-linter-pre-commit
    rev: HEAD
    hooks:
      - id: lint-imports
```
