---
sidebar_position: 3
---

# Installation

Installing QuickJS is simple, and we provide multiple ways to do so.

## Homebrew

If you use [Homebrew][], run the following command:

```bash
brew install quickjs-ng 
```

## jsvu

As of version 2.2.0 of jsvu, requesting the quickjs engine will install QuickJS-ng.

```bash
npm install jsvu -g
```

## Prebuilt binary

Each [release on GitHub][] includes binaries for a number of systems and architectures.

## Build from source

If you built it from source as outlined in [building](./building), run the following command:

```bash
make install
```

QuickJS-ng will install to your system at `/usr/local` by default.

[Homebrew]: https://brew.sh
[release on GitHub]: https://github.com/quickjs-ng/quickjs/releases
