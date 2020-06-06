# 3ative 'blue' Theme

[![Version](https://img.shields.io/badge/version-0.01-green.svg?style=flat-square&labelColor=2ea9f4&color=1473ae)](#)
[![maintained](https://img.shields.io/maintenance/yes/2020.svg?style=flat-square&labelColor=2ea9f4&color=1473ae)](#)

My current theme: "blue.yaml"

## Installation

* Find your homeassistant directory containing your configuration (let's say `/config/`)
* Change into `/config/themes` (create the `themes` directory, if it does not exist, you then might have to restart HA)
* Ensure HA knows your new theme file - add this to your `configuration.yaml`
``` yaml
frontend:
  themes: !include_dir_merge_named themes
```
* Finally enable the theme from your profile page or `configuration.yaml`

### HACS installation
1. Go into the Community Store (HACS)
2. Search for 3ative blue theme
3. Press Install
4. Restart Home Assistant

<a href="https://www.buymeacoffee.com/3ative" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-blue.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>
