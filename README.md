Counter-Strike 2
---
```shell
SDL_AUDIODRIVER=pulseaudio XKB_DEFAULT_LAYOUT=us,ru XKB_DEFAULT_OPTIONS=grp:caps_toggle,caps:none gamescope -W 1920 -H 1080 -w 1280 -h 960 -r 300 -S stretch -f --force-grab-cursor -- %command% 
```
`SDL_AUDIODRIVER=pulseaudio` - Fixes audio issues for Source 2 games

Dota 2
---
```shell
SDL_AUDIODRIVER=pulseaudio OBS_VKCAPTURE_NAME="Dota 2" obs-gamecapture %command% 
```
`SDL_AUDIODRIVER=pulseaudio` - Fixes audio issues for Source 2 games

Overwatch 2
---
```shell
DXVK_FILTER_DEVICE_NAME="AMD" %command%
```
`DXVK_FILTER_DEVICE_NAME="AMD"` - Disables my second videocard
