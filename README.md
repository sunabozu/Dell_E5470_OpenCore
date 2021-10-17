# OpenCore setup for Dell Latitude E5470

## Power Management
This setup uses CPUFriend with a tuned profile, which unlocks the lowest frequencies. There is also a [patched version of the DisableTurboBoostBatery.kext](https://osxlatitude.com/forums/topic/2263-kext-to-disable-intel-turbo-boost-on-battery-power/?do=findComment&comment=86783) that works with VirtualSMC.

## Caveats
1. If you plug in an external monitor via HDMI or just boot the system with it attached, the built-in screen turns off. In order to fix it, just close the lid and open it again or plug the cable in only after waking up. Sadly, can't find a solution.
