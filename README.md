# 3ative 'blue' Theme

[![Version](https://img.shields.io/badge/version-0.01-green.svg?style=flat-square&labelColor=2ea9f4&color=1473ae)](#)
[![maintained](https://img.shields.io/maintenance/yes/2020.svg?style=flat-square&labelColor=2ea9f4&color=1473ae)](#)

> My 'Blue' theme, give a cool electric feel to LoveLace.

> ***Also: Download my custom background "3ative_bg.jpg" and place it in your **/config/www/** folder... or use your own.***
https://github.com/3ative/3ative-blue-theme/blob/master/3ative_bg.jpg

**Screenshots**

**Main Page**
![1](https://github.com/3ative/3ative-blue-theme/blob/master/screenshots/01-front.JPG)
**Config**
![2](https://github.com/3ative/3ative-blue-theme/blob/master/screenshots/02%20config.JPG)
**States**
![3](https://github.com/3ative/3ative-blue-theme/blob/master/screenshots/03%20States.JPG)
**Devices**
![4](https://github.com/3ative/3ative-blue-theme/blob/master/screenshots/04%20devices.JPG)

**Include BG image**
![5](https://github.com/3ative/3ative-blue-theme/blob/master/3ative_bg.jpg)

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
