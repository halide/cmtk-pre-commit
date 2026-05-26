# cmtk-pre-commit

pre-commit hooks for cmtk (CMake formatter and static analyzer).

This repository is a pre-compiled mirror distribution. It allows using `cmtk` in `pre-commit` without compiling it from source.

## Usage

Add this to your `.pre-commit-config.yaml`:

```yaml
repos:
  - repo: https://github.com/halide/cmtk-pre-commit
    rev: v0.1.0
    hooks:
      - id: cmtk
```
