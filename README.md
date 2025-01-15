# VNC Server


---
## NoMachine Enterprise Desktop for Raspberry Pi
https://downloads.nomachine.com/linux/?distro=Raspberry&id=26

* NoMachine Enterprise Desktop
* NoMachine Enterprise Desktop for Windows
* NoMachine Enterprise Desktop for Mac
* NoMachine Enterprise Desktop for Linux
* NoMachine Enterprise Desktop for Raspberry Pi
* NoMachine Enterprise Desktop for Arm

NoMachine Enterprise Desktop for Raspberry ARMv8 DEB
NoMachine Enterprise Desktop for Raspberry - arm64
https://downloads.nomachine.com/download/?id=78&distro=Raspberry&hw=Pi4


NoMachine Enterprise Desktop for Linux
NoMachine Enterprise Desktop for Linux -x86_64, amd64
NoMachine Enterprise Desktop for Linux DEB amd64
https://downloads.nomachine.com/download/?id=40

### Connection

```
$ nx://192.168.50.53:4000
$ ssh://192.168.50.53:22
$ https://192.168.50.53:4443
```

---
## VNC on Raspberry Pi 5

https://forums.raspberrypi.com/viewtopic.php?t=358458


---
## Raspberry Pi 5, Bookworm and RealVNC Connect

https://help.realvnc.com/hc/en-us/articles/14110635000221-Raspberry-Pi-5-Bookworm-and-RealVNC-Connect#statement-0-0

* Our current versions of RealVNC Viewer and RealVNC Server unfortunately will not support the RPi 5 platform out-of-the-box as a result of Raspberry Pi’s move to a default Wayland environment on Debian (Bookworm).

#### Updates

2025-01-03 - Wayland support update
* Our development team are continuing to work on updating RealVNC Server for PiOS to support Wayland, we will share further updates as this progresses.

2023-10-12 - Pi OS Bookworm compatibility
* We can confirm compatibility of RealVNC Viewer and RealVNC Server when running Pi OS Bookworm in X11 mode, instead of Wayland (wayfire), as below.
* Raspberry Pi 0-3: These continue to use X11 by default therefore RealVNC Connect continues to be supported.
* Raspberry Pi 4-5: This device defaults to using Wayland (wayfire) on Pi OS Bookworm, however it is possible to switch to X11 by using the command line raspi-config utility, under Advanced Options -> Wayland, to use RealVNC Connect.
