# Sundown Theme

[![Build Status](https://www.travis-ci.org/home-assistant-community-themes/template.svg?branch=master)](https://www.travis-ci.org/home-assistant-community-themes/template)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)

> Sundown theme by am80l

## Screenshots

### Overview

![Theme - Overview](https://raw.githubusercontent.com/am80l/sundown/master/sundown.jpg)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

Add the following line to your lovelace-ui.yaml or use the RAW editor:
```
background: var(--background-image)
```
(Optional) add the following to the same file to make the header smaller (you need to install cch too):
```
cch:
  background: 'rgba(155, 155, 155, 0.25)'
  clock_format: 24
  options: clock
  swipe_animate: fade
  swipe_prevent_default: true
```
### HACS

1. Go to the Community Store.
2. Search for `Sundown`.
3. Navigate to `Sundown` theme.
4. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/am80l/sundown.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/am80l/sundown.git
```
