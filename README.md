# Badge-s

`Badge-s` is a small artifact repository containing badge experiments and lightweight pairing/testing outputs. It is intentionally a scratch-style workspace rather than a packaged application or library.

## Contents

| Path | Purpose |
| --- | --- |
| [`badges/`](./badges) | Generated badge notes and artifacts |
| [`pair/`](./pair) | Pair-session output logs |
| [`testing/`](./testing) | Small generated testing fixtures |

## Working with the repository

There is currently no runtime, package manifest, build system, or automated test suite. Clone the repository and inspect the artifacts with standard Git tools:

```bash
git clone https://github.com/mayankbohara0-dev/Badge-s.git
cd Badge-s
find . -maxdepth 3 -type f -not -path './.git/*' -print
```

## Status and license

This repository is maintained as an evolving scratch space. No license file is currently included; add one if you want to define how these artifacts may be reused.

## Author

Maintained by [Mayank Bohara](https://github.com/mayankbohara0-dev).
