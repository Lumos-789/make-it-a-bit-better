# Changelog

## 0.2.2

- The repo gate now requires `target` to be the repository root: a directory
  nested inside another repository fails the gate and reports both paths,
  instead of silently committing rounds into the parent repo.
