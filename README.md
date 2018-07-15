# Customisation of the Keyboardio Model01 keyboardio

My personal customisation for the [Keyboardio Model01 keyboard](https://shop.keyboard.io/).

## Current customisation

* # and ~ keys on function layer via the quote key


## Editing the keymap

The key map is defined in the Model01-Firmware.ico file.  You can edit this in your favourite editor or open it in the arduino ide. 

The definitions for the keyboar maps are underneath the line `enum { QWERTY, FUNCTION, NUMPAD }; // layers`  (currently line 124)

Three layers a defined by default
* QUERTY - the default behaviour of all the tools - layer 0
* NUMPAD - the key behaviour when the num key is pressed - layer 1
* FUNCTION - key behaviour when the fn key is held down - layer 2

The keymap layer is defined in two parts, one part for each keyboard half, starting with the left hand half of the keyboard.

Where the keymap as `___` then nothing is mapped to that key, so you can add a key.  Or replace an existing key with another key or nothing, eg. if you keep hitting the escape key instead of b.

All keys are defined a name that you can use in the keymap in the [key_defs_keyboard.h](https://github.com/keyboardio/Kaleidoscope/blob/master/src/key_defs_keyboard.h) file.

The [Edit a keymap page](https://github.com/keyboardio/Kaleidoscope/wiki/Edit-a-keymap) on the wiki has more details.

## Further reading
[Check out the wiki](https://github.com/keyboardio/Kaleidoscope/wiki/Keyboardio-Model-01-Introduction) for a more in depth introduction to how the Model 01 keyboard and the Kaleidoscope firmware work. 
