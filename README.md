# **Bixby Button Remapper**

## Description

This Magisk module allows ther user to remap the Bixby hardware button of the
Samsung Galaxy S8/S8+ (G950F/G955F), S9/S9+ (G960F/G965F) and S10e/S10/S10+
(G970F/G973F/G975F) to any one of 15 user-selectable functions.

The following functions are selectable during installation, using the hardware
keys of the phone:

* Camera
* Screenshot
* Google Search
* Google Voice
* Call
* Contacts
* Music Player
* Mute/Unmute Media Volume
* Play/Pause Media
* Next Media
* Recent Apps
* Open/Close Quick Settings
* Internet Browser
* Calendar
* Calculator

To change the currently mapped function, simply reinstall the module, make a
new selection and reboot.

To restore the default Bixby behaviour, simply deactivate or uninstall the
module and reboot.

## Changelog

2019-04-17: v2.3

- Rather than including a replacement keyboard layout file, we now dynamically
  modify a copy of the device's actual file. This way, the file will always be
  up to date and not subject to minor differences between devices and Android
  OS version.

2019-03-29: v2.2

- Updated for Magisk v19 template format.

2019-03-22: v2.1

- Support for the Samsung Galaxy S10e/S10/S10+ (G970F/G973F/G975F).

2018-11-03: v2.0

- Now supports 15 different functions, selectable during installation.

2018-07-03: v1.0

- Initial release, supporting remapping to camera only.
