# Unofficial zstandard wheel for CPython 3.15 on Windows x64

This repository distributes an **unofficial** Windows x64 wheel of [python-zstandard](https://github.com/indygreg/python-zstandard) version **0.25.0**, compiled for **CPython 3.15**.

The binary was built from the upstream `zstandard-0.25.0.tar.gz` source archive using Microsoft Visual Studio Build Tools 2026 and a C-extension backend. The resulting wheel was installed and its compression/decompression functions tested successfully in a clean Python 3.15 virtual environment.

> **Unofficial community build.** Not affiliated with or endorsed by the upstream maintainers. Use at your own risk.

## Files

- `zstandard-0.25.0-cp315-cp315-win_amd64.whl`
- `zstandard-0.25.0.tar.gz` (upstream source archive, for provenance)

## Verify integrity

SHA-256 for the wheel:

```text
57df8c3a6bde23673b3e906edfa95aa1bd46de8506ef96c47c0cd7a4990bedd8
```

SHA-256 for the included source archive:

```text
7713e1179d162cf5c7906da876ec2ccb9c3a9dcbdffef0cc7f70c3667a205f0b
```

## Install

Download the wheel file from this repository, then run on **64-bit Windows with CPython 3.15**:

```powershell
python -m pip install .\zstandard-0.25.0-cp315-cp315-win_amd64.whl
```

This wheel is not compatible with other Python interpreter versions or operating systems.

## Upstream

Original project: https://github.com/indygreg/python-zstandard

Please report issues with this independently compiled binary in this repository, not to upstream unless reproduced with an official build.
