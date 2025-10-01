# Naked-AOSP
A very minimal SEMI-GSI for the samsung galaxy A03 core.


You are the one responsible for anything that happens to your device.

You are the one who chooses what to install.

You are the owner of your device.

And I am not.


# Installation
-Download and flash fastbootd recovery from telegram: https://t.me/A03Cdevelopment/7/76264

-Reboot to fastbootd, (through recovery mode or adb reboot fastboot)

-Connect your phone to your pc and open a terminal/command prompt and execute: `fastboot flash system <the name of the image>`

-EXAMPLE: `fastboot flash system NakedAOSP.img`

-After that, wipe using: `fastboot -w`

-Then reboot your device. `fastboot reboot`


# Things to consider
-There's no default keyboard app (Install your own!)

-There's no phone/sms app (Install your own!)

-You are free to make your own repos of this and modify whatever you want.

