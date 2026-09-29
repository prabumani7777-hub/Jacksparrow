# Jack Sparrow Host theme for PS5 WebKit Autoloader

A visual override for [itsPLK/ps5-webkit-autoloader](https://github.com/itsPLK/ps5-webkit-autoloader). The center pirate emblem starts the original `app.js` flow when clicked. It uses the upstream firmware checks and exploit iframe unchanged.

## Use with the upstream PC host

Download the official `webkit-autoloader-host.py` release from the upstream project. Place the `pc-host/overrides/app/` files beside its `pc-host/overrides/` directory, preserving the path. Run the upstream host per its README, and follow the official installer procedure. This repository contains only the themed UI override; it does not include the upstream exploit or compiled installer.

The on-screen 7.61–13.60 label summarizes a range. `app.js` supports specific firmware versions in that range. This theme has not been tested on a PS5.

Based on GPL-3.0 source by PLK and contributors. See `LICENSE` and the upstream project for credits.
