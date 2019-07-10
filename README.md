# bleemsync_networking

Just copy the bleemsync folder on top of /media/bleemsync.

Use wifi-wpa-setup to setup networking, or manually edit the file at /media/bleemsync/network/etc/wpa_supplicant/wpa_supplicant.conf

Current tested working drivers/adapters:

* TP-Link WN725(8188eu)
* ASUS AC-53 NANO(rtl8822bu)
* Insignia Gigabit Ethernet(asix)

Drivers can be compiled from the PSC Linux source using the 4.4.22 kernel from Sony's source repo.

This package makes minimal additions to the PSC's filesystem, creating blank directories, and adding some files to those directories only if using the fat32 filesystem for compatibility.

TODO:
Make an uninstall script.
