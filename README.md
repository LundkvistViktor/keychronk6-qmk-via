# keychronk6-qmk-via
Personal repository containing my keymap for my keyboard.

If you want to use it for yourself, build the firmware included in this repository, please see https://github.com/SonixQMK/qmk_firmware and https://github.com/CanUnesi/QMK-on-K6

Please note that you currently cannot run both VIA and openRGB at the same time.


## Enabling VIA

Add 
```
VIA_ENABLE = yes
```
 

to rules.<span></span>mk

## Editing Keymap
### Using QMK configurator
https://config.qmk.fm/ </br>
Current keymap is using tada68 as keyboard for the configurator as the official QMK repository doesnt support keychron k*.</br>


Upload and edit the keymap.json, convert to C using qmk toolbox </br>

Edit keymap.c with the new keymap, compile and reflash the keyboard