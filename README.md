# Corne Keyboard Setup
Wireless Corne with Choc switches running on ZMK.

### Guide

#### Edit 
- Edit layout with GUI [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/), and save changes.

#### Get firmware 
- Open this repo's [Github Actions](https://github.com/kormyen/zmk-corne/actions/). 
- Either click the latest "Build ZMK firmware" action that has run, or wait for your latest change to finish automatically building.
- At the bottom of the page under the "Artifacts produced during runtime" section, click "firmware". This will download a zip file with the updated firmware for the ZMK keyboards.

#### Install firmware 
- Plug the keyboards into your PC via USB.
- Double press the reset button that is next to the on/off switch - this changes the keyboard into bootloader mode and shows up as a USB thumbdrive on your PC.
- Unzip the "firmware.zip" folder, there should be a firmware file for the left keyboard, and one for the right keyboard.
- Drag the appropriate left or right firmware file into the keyboard drive.
- The file transfer may say that it failed but the keyboard will automatically reset and reconnect and be running the new firmware.

### Sources

- [Wireless Corne](https://docs.typeractive.xyz/build-guides/corne-wireless) is the official documentation for this keyboard.
- [ZMK Firmware](https://zmk.dev/docs) is the firmware for this keyboard.

### Tools

- [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) is a webapp GUI Keymap Editor for ZMK keymaps.

### References

- [Designing a Symbol Layer](https://getreuer.info/posts/keyboards/symbol-layer/index.html) is a page with thoughts and suggestions for a Symbols layer.
- [Miryoku](https://github.com/manna-harbour/miryoku/tree/master/docs/reference) is an ergonomic, minimal, orthogonal, and universal keyboard layout.
- [Colemak DH](https://colemakmods.github.io/mod-dh/) is a keyboard layout designed to make typing more comfortable.

### Screen Art
- https://www.reddit.com/r/ErgoMechKeyboards/comments/15t3o6k/custom_art_on_niceview_displays/?share_id=rgH_Be2qhaH8GM2n3kX7x&utm_content=2&utm_medium=ios_app&utm_name=ioscss&utm_source=share&utm_term=1 
- https://github.com/GPeye/urchin-peripheral-animation