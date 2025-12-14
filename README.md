# 3Ative Blue Theme

[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg)](https://github.com/hacs/integration)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/3ative/3ative-blue-theme?label=Version&style=flat-square&labelColor=2ea9f4&color=1473ae)

> My 'Blue' theme, give a cool electric feel to LoveLace.

**Download the background "3ative_bg.jpg" https://github.com/3ative/3ative-blue-theme/blob/master/3ative_bg.jpg and save it in your `/config/www/` folder...** or use your own (just use the same file name) 😎


### Screenshots

**Main Page**
![1](https://github.com/3ative/3ative-blue-theme/blob/master/screenshots/01-front.JPG)
**Config**
![2](https://github.com/3ative/3ative-blue-theme/blob/master/screenshots/02%20config.JPG)
**History (NEW)**
![3](https://user-images.githubusercontent.com/51385971/129607168-c67e50e1-7223-403b-b0ad-87498456eeaa.JPG)
**States**
![4](https://github.com/3ative/3ative-blue-theme/blob/master/screenshots/03%20States.JPG)

**Devices**
![5](https://github.com/3ative/3ative-blue-theme/blob/master/screenshots/04%20devices.JPG)

**Included BG image**
![6](https://github.com/3ative/3ative-blue-theme/blob/master/3ative_bg.jpg)

## Installation

* Find your homeassistant directory containing your configuration (let's say `/config/`)
* Change into `/config/themes` (create the `themes` directory, if it does not exist, you then might have to restart HA)
* Ensure HA knows your new theme file - add this to your `configuration.yaml`
```yaml
frontend:
  themes: !include_dir_merge_named themes/
```
* Copy the https://github.com/3ative/3ative-blue-theme/blob/master/3ative_bg.jpg to your ***config/www/** folder
* Finally enable the theme from your profile page or `configuration.yaml`

### HACS installation
1. Go into the Community Store (HACS)
2. Search for 3ative blue theme
3. Press Install
4. Restart Home Assistant

### No Background image?
If the Background image is not showing, make sure you have **"- background: var(--background-image)"** in your `raw config` setup under `views:` ...

![6](https://github.com/3ative/3ative-blue-theme/blob/master/screenshots/bg_var.JPG)

---

<div align="center">

### 💖 Support This Project

Found this useful? Want to say thanks and fuel future creations?

**Your support keeps the creativity flowing!** 🍺✨

<table>
  <tr>
    <td align="center">
      <a href="https://www.buymeacoffee.com/3ative">
        <img src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Support-yellow.svg?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white" alt="Buy Me A Coffee"/>
        <br/>
        <b>☕ Buy me a Coffee</b>
      </a>
    </td>
    <td align="center">
      <a href="https://www.patreon.com/3ative">
        <img src="https://img.shields.io/badge/Patreon-Become%20a%20Patron-red.svg?style=for-the-badge&logo=patreon&logoColor=white" alt="Patreon"/>
        <br/>
        <b>💖 Join on Patreon</b>
      </a>
    </td>
  </tr>
</table>

**Every contribution helps bring more awesome projects to life!** 🚀

</div>

---
