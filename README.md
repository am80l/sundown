# Template Theme

[![Build Status](https://www.travis-ci.org/home-assistant-community-themes/template.svg?branch=master)](https://www.travis-ci.org/home-assistant-community-themes/template)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)

> The Template Theme by Maarten Paauw

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

### HACS

1. Go to the Community Store.
2. Search for `Template`.
3. Navigate to `Template` theme.
4. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/home-assistant-community-themes/template.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/home-assistant-community-themes/template.git
```
