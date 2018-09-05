
Debian
====================
This directory contains files used to package bitzonecoind/bitzonecoin-qt
for Debian-based Linux systems. If you compile bitzonecoind/bitzonecoin-qt yourself, there are some useful files here.

## bitzonecoin: URI support ##


bitzonecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitzonecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitzonecoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bitzonecoin128.png` to `/usr/share/pixmaps`

bitzonecoin-qt.protocol (KDE)

