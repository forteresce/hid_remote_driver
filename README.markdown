Generic HID Remote Driver for XBMC
----------------------------------

This is a generic hid driver for use with XBMC if your computer came with
a hid remote or you bought one. The base code was provided by [coldsource](http://forum.xbmc.org/member.php?u=80895)

After having successfully used this for a while, I started having trouble
when I upgraded my OS to Ubuntu 11.04 and later to Ubuntu 11.10. I debugged
it a bit and provided this slightly hacked version that made it work for me.

This is provided asis and without any guarantee. Please see LICENCE for more
details.


Usage
-----

### Compile the drivers
$ make

### Make sure your HID remote is recognized (listed)
$ sudo ./hid_mapper --list-devices

### Run with learn mode so you can create your map file
TODO

### Run with the map file to use it
$ sudo ./run_remote

### Extra steps if you need autostart
TODO

