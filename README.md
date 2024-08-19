Hi,

this is a fork of the original BlueBerry Firmware by Drexel-Macintosh for the BB9900 keyboard by Zitaotech
(see the links below).

The aim was to get the keyboard produce **Czech characters** on my daughter's old Android 13 phone, but along the way, 
I also changed the top row buttons behaviour and Alt layer to fit my pattern of keyboard & phone usage. 

I am an absolute beginner with exactly zero experience in programming anything but with the descriptions of the firmware building and updating by ZitaoTech, 
keymapping pictures on the Drexel-Macintosh page, the tips on the ZMK firmware blog, and the absolutely fantastic WYSIWYG key map editor by Nick Coutsos, I was able to put together 
something that brought back the vibes of the good old Blackberry times of ultimate productivity ;-)

My usage:
- ZitaoTech BB9900 USB/BLE keyboard (notice the little hole on the bottom: you can press twice to reset and connect via cable to your computer if you really muck up your firmware - you can guess why I know this :-)
- Android 13 phone (Pixel 4a)
- Czech QWERTY Android keyboard installed (will not work with the default US keyboard due to different characters mapping on the physical keyboard!)
- Microsoft SwiftKey keyboard app to interpret the physical key presses, with Czech language installed
- the Czech characters (háčky, čárky) can be invoked by long pressing the respective keys on the keyboard in Layer 0 (there are more characters available in Layer 1 = alt layer), or long press K for čárka, long press L for háček and then press the required character
- using SwiftKey features of guessing phrases, you can press space to invoke the middle suggestion (option 2), or use the 0 key for other suggestions (short press = left suggestion, long press = right suggestion; this is as close as I could emulate the great feature of swipe-up gestures on the capacitative keyboard of Blackberry Key 1 and 2 while using Blackberry keyboard app)
- press $ to backspace, press Del to delete
- for details, take a look at the keymapping file in my fork


Thanks to the fabulous work of the guys below, they made me feel 15 years younger :-)

[BlueBerry Firmware](https://github.com/Drexel-Macintosh/BlueBerry_Q20/blob/main/README.md)

[ZitaoTech project](https://github.com/ZitaoTech/BB9900-USB_BLE_Keyboard)

[Key map editor](https://nickcoutsos.github.io/keymap-editor/)

[ZMK firmware documentation](https://zmk.dev/docs)

[ZMK firmware blog on localisation](https://zmk.dev/blog/2024/01/05/zmk-tools)
