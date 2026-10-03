![Output Analog Strings Desktop](assets/hero.png)

# Output Analog Strings Desktop

*Find the Output Analog Strings folder fast and keep a local spare.*

## Overview

**Output Analog Strings Desktop** runs on your own PC. Local Windows and macOS helper for Output Analog Strings data paths, config and export caches, and export folders.

Output Analog Strings drops data files next to launcher caches.

Use it when you want the change on this machine without opening a dozen Settings pages.

## What's included

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Features

- Finds the Output Analog Strings data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Output Analog Strings desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/claihoward496/output-analog-strings-desktop

MIT license. See `LICENSE`.
