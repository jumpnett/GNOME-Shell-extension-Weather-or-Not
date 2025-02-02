<img align="left" src="https://gitlab.gnome.org/GNOME/gnome-weather/-/raw/main/data/icons/org.gnome.Weather.svg">

# GNOME Shell Extension - Weather or Not

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

A simple extension for GNOME Shell 42+ that adds an icon showing the current weather conditions and temperature to the right of the clock (while also keeping it centered). Clicking the icon opens GNOME Weather, which is required for the extension to operate properly (that's where it gets it's weather data from).

**NB:** GNOME Weather is required!

![screenshot](https://user-images.githubusercontent.com/15643750/212436694-3601a050-a659-4b63-aed0-439da2f975a0.png)

## Installation
[<img src="https://user-images.githubusercontent.com/15643750/212080370-77899e64-bae8-43f1-b67a-fc946785c4b3.png" height="100">](https://extensions.gnome.org/extension/5660/weather-or-not/)

Alternatively, use the [Extension Manager](https://github.com/mjakeman/extension-manager) app.

#### Manual installation
1. Make sure you have GNOME Weather installed and a default location set in it
2. Download the extension .zip archive from this repo and unzip it
3. Copy the `weatherornot@somepaulo.github.io` folder to `~/.local/share/gnome-shell/extensions/`
4. Log out and log back in (on Wayland) or use `Alt+F2`,`r`,`Enter` (on X11)
5. Enable the extension in either `Extensions`, `Extension Manager` or [GNOME Shell Extensions](https://extensions.gnome.org/local/)
