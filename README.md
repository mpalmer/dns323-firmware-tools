# dns323-firmware-tools

This package contains programs for manipulating the firmware images used by
the D-Link DNS-323 and similar devices (firmwares sometimes referred to as
"FrodoII" firmwares, due to the magic string used to identify them).

These firmware images are what are used to "bundle" the kernel, initrd, and
other data when uploading new firmware images using the "stock" interface. 
If you are already running a custom firmware, it is likely that these tools
will be of no use to you, and you will need to use whatever update mechanism
is provided by your firmware.


## Requirements

The only requirements to run these tools is an installation of Ruby 1.8, and
the input files (kernel/initrd) to make into a firmware.
