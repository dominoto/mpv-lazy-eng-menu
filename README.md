# mpv-lazy english menu

How to translate [mpv-lazy's](https://github.com/hooke007/MPV_lazy) interface to English:

1. Download [uosc_lang.conf](https://github.com/hooke007/MPV_lazy/blob/main/portable_config/script-opts/uosc_lang.conf) and put it in _portable_config/script-opts_ (buttons translated to English) [(Source)](https://github.com/hooke007/MPV_lazy/issues/303)
2. Download my modded [input_uosc.conf](https://github.com/dominoto/mpv-lazy-eng-menu/blob/d5b231864c975d8994b33774f66a4898a0738500/input_uosc.conf) and put it in _portable_config_ (menu translated to English)

Changes to input_uosc.conf:

+ Added shortcuts:
  - **SPACE**: play/pause
  - **Right arrow**: fast-forward 10 seconds
  - **Left arrow**: reverse 5 seconds
  - **ENTER**: toggle fullscreen
+ Added playback speed x1.1 and removed x2
+ Volume shortcuts changed to Up/Down arrow keys

I am using this translation with version [mpv-lazy-2023V5](https://github.com/hooke007/MPV_lazy/releases/tag/20230630) with vsMega filters.
