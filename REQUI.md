
## Requirements

Particolar requirements, you should install/set if you want to compile and use this build.

> **O:** Obviously an already working Xorg installation and standard dev-tools must be present

**lib**
  * libx11 libx11-devel
  * libxft libxft-devel
  * libxcb libxcb-devel
  * libxinerama libxinerama-devel

**bin**
  * alacritty (rust terminal emulator)
  * st-luke (make && make install)
  * dwmblocks-luke (make && make install)
  * slock (make && sudo make install)
  * pamixer (pulse audio mixer, make && make install)
  * rofi (dmenu replacement)
  * rofi-power (rofi power management script)
  * rofi-pass (rofi pass support script, make && make install)
  * teiler (rofi screen capture script, make && make install)
  * picom or compton (for alpha effects)
  * feh (for background)
  * ranger (simple file manager and more)
  * brightnessctl (adjust screen brightness)

**conf**, see [here](https://github.com/andros21/dotfiles)
  * Xresources (global settings and aspects)
  * profile (setup X env before dwm)
