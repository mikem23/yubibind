Yubibind
========

This is a basic tool to avoid stray keystrokes from a yubi nano.

When run, the script will enable all Yubico devices for sixty seconds and
then disable them again. The script can be stopped with ctrl-C and will
still disable the devices before exiting.

Using this script keeps these devices disabled except when they are needed.

Because the script works by binding and unbinding usb devices, it must be
run as root. Sudo is recommended.
