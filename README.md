# golb

This ansible playbook will configure your host to share /media/golb over SMB (using Samba) and HTTP (using nginx), exactly how golb is set up at QL.

Also it puts some ASCII art in your MOTD :)

Note: If you're like me and trying to test this on a Raspberry Pi VM, and like me you weren't able to get it fully working in qemu with Bookworm but were able to get it working in Buster, you should know that **the `wsdd` package that this playbook installs is not packaged for Buster.** For a workaround, download the .deb directly and install it manually with `dpkg`.
