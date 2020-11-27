# kbd_backlight
Controls the keyboard backlight on Linux

This fork uses smc::kbd_backlight instead as needed for some machines such as Macbook Air.
Forked from: https://github.com/Spauldo/kbd_backlight

Options:

-e

  Enable, set to 100%
  
-d

  Disable, set to 0%

-l <num>

  Set the level to <num> - must be between 0 and 100

This is hardcoded to use /sys/class/leds/kbd_backlight/brightness.  If
your system does not use this file for backlight control, then this
program isn't for you.

# NOTE:

This simple program was intended as a simple example to someone on
StackExchange on how to control the keyboard backlight.  While it does what
it says, the main goal is simplicity.

In other words, if you're here because you're considering hiring me, don't
assume this is the extent of my coding abilities :)
