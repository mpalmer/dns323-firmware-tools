# dns323-firmware-tools

This package contains programs for manipulating the firmware images used by
the D-Link DNS-323 and similar devices.

These firmware images are what are used to "bundle" the kernel, initrd, and
other data when uploading custom firmware images using the "stock" firmware
update interface.  If you are already running a custom firmware, it is
likely that these tools will be of no use to you, and you will need to use
whatever update mechanism is provided by your firmware.


## Requirements

In order to run, this program requires:

 * Ruby 1.9 or above;

 * The `cstruct` gem (`gem install cstruct`);

 * A compatible firmware file, or the input files (kernel/initrd) to make
   into a firmware.
