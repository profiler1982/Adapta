Adapta
=========
<img src="img/Button.gif" alt="Button" align="right" />
An adaptive Gtk+ theme based on Material Design Guidelines.
Lots of elements are forked from Flat-Plat: https://github.com/nana-4/Flat-Plat

Elements
--------
![Materials](img/Materials.png)

Required Components
-------------------
* Gtk+-3.0 >= 3.18.6
* Gtk+-2.0 >= 2.24.29
* gtk2-engines-pixbuf >= 2.24.29

Supported Desktop Environments
------------------------------
* GNOME 3.18.x
  * gnome-shell >= 3.18.2
  * mutter >= 3.18.2
* GNOME-Flashback 3.18.x
  * gnome-flashback >= 3.18.1
  * gnome-panel >= 3.18.1
  * metacity >= 3.18.1
* Budgie-Desktop 10.2.2
* Unity7 7.4.0
  * Compiz >= 0.9.12

Unsupported Gtk+ Based Desktops
-------------------------------
* Cinnamon
* Mate
* XFce4
* Pantheon

Installation
------------
1. Check `autoconf`, `automake` and `pkg-config` (`pkgconfig`) are installed.
2. Build and install system-wide:
   ```
   ./autogen.sh
   make
   sudo make install
   ```
   * Default prefix is `/usr`
   * `make` actually does nothing (for future release)

3. Use `gnome-tweak-tool` to change the theme.

Work in Progress
----------------
* Unity7 desktop integration (but unity is not my thing at all...)

TODO
----
* Add Cinnamon 2.8 theme styling (regardless)

Public License
--------------
* License: GPLv2

Special Thanks to
-----------------
Nana-4, the developer of Flat-Plat.
