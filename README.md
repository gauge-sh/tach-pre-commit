# tach-pre-commit

A [pre-commit](https://pre-commit.com/) hook for [Tach](https://github.com/gauge-sh/tach).

Distributed as a standalone repository to enable installing Tach via prebuilt wheels from
[PyPI](https://pypi.org/project/tach/).

### Using Tach with pre-commit

To run `tach check` via pre-commit, add the following to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/gauge-sh/tach-pre-commit
  # Tach version.
  rev: v0.9.2
  hooks:
    - id: tach
```
