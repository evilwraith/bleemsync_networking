# bleemsync_networking

Just copy the bleemsync folder on top of /media/bleemsync.

Use wifi-wpa-setup to setup networking, or use the updated Retroarch included in the package to use connman for configuration.

The only tested drivers currently loaded are for the TP-Link WN725 wireless adapter(8188eu) and the Insignia USB Gigabit wired adapter(asix). More have been included but have not been tested. Drivers can be compiled from the PSC Linux source using the 4.4.22 kernel.

This package makes minimal additions to the PSC's filesystem, creating blank directories, and adding some files to those directories only if using the fat32 filesystem for compatibility.

TODO:
Make an uninstall script.
