# Template

[![Hacs](https://img.shields.io/badge/HACS-Custom-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/timpihl/template?style=for-the-badge) 
![GitHub Release Date](https://img.shields.io/github/release-date/timpihl/template?style=for-the-badge)

> Template theme by TimPihl

## Screenshots

### Overview

![Theme - Overview](https://raw.githubusercontent.com/timpihl/template/master/docs/theme-overview.png)

### Map

![Theme - Map](https://raw.githubusercontent.com/timpihl/template/master/docs/theme-map.png)

### Logbook

![Theme - Logbook](https://raw.githubusercontent.com/timpihl/template/master/docs/theme-logbook.png)

### History

![Theme - History](https://raw.githubusercontent.com/timpihl/template/master/docs/theme-history.png)

### Developer Tools

![Theme - Developer Tools](https://raw.githubusercontent.com/timpihl/template/master/docs/theme-developer-tools.png)

### Configuration

![Theme - Configuration](https://raw.githubusercontent.com/timpihl/template/master/docs/theme-configuration.png)

### Profile

![Theme - Profile](https://raw.githubusercontent.com/timpihl/template/master/docs/theme-profile.png)

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

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/timpihl/template.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/timpihl/template.git
```
