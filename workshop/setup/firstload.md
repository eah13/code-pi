## Settings for the first load of Raspbian or Occidentalis
## TODO: Clean up.  This file is rough.

The following settings should be changed the first time you run a virgin Linus system.  They will pop up in a blue and grey interface or you can edit them by typing `sudo raspi-config`.
* Edit Keyboard Layout (Set everything to US.  I also like to enable Ctrl-Alt-Backspace to kill the X Server)
* Edit locale.  You'll also wan this to be US.  Select US UTF-8 from the encodings.
* Boot Behavior.  Turn on automatic boot to desktop
* SSH. Turn on SSH

Optional settings:
* Memory Sharing
* Overclock: It's fine to crank overclocking up to 900mhtz
