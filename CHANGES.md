## Changelog

* Local install `config.mk`
* patches
  - focus on active
  - ewmh tags
  - bar height xresources
* Personal key bindings and tags
* Restore `config.h` as original, now compile using `myconfig.h` to avoid merge conflict

## Requirements

Particolar requirements, you should install/set if you want to compile and use this build.

> obviously an already working Xorg installation and standard dev-tools must be present

#### Libs

* libx11 libx11-devel
* libxft libxft-devel
* libxcb libxcb-devel
* libxinerama libxinerama-devel

#### Bins

* alacritty (rust terminal emulator)
* brightnessctl (adjust screen brightness)
* dwmblocks-luke (make && make install)
* feh (for background)
* wpctl (wireplumber control cli)
* picom or compton (for alpha effects)
* ranger (simple file manager and more)
* rofi (dmenu replacement)
* rofi-pass (rofi pass support script, make && make install)
* rofi-power (rofi power management script)
* slock (make && sudo make install)
* st-luke (make && make install)
* teiler (rofi screen capture script, make && make install)
* xautolock (auto lock screen)

#### Configs

> see https://github.com/andros21/dotfiles

* Xresources (global settings and aspects)
* profile (setup X env before dwm)
* xinitrc (setup X env before dwm)
