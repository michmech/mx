How to install the MX keyboard layout on Ubuntu.

1. Copy the file `symbols/mx` into `/usr/share/X11/xkb/symbols`.
2. Add the XML snippet from `rules/evdev.xml` into `/usr/share/X11/xkb/rules/evdev/xml`.
3. Clear XKB cache: `sudo dpkg-reconfigure xkb-data` and/or restart.

