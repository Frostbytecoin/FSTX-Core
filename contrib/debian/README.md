
Debian
====================
This directory contains files used to package frostbyted/frostbyte-qt
for Debian-based Linux systems. If you compile frostbyted/frostbyte-qt yourself, there are some useful files here.

## frostbyte: URI support ##


frostbyte-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install frostbyte-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your frostbyteqt binary to `/usr/bin`
and the `../../share/pixmaps/frostbyte128.png` to `/usr/share/pixmaps`

frostbyte-qt.protocol (KDE)

