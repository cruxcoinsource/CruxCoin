
Debian
====================
This directory contains files used to package cruxcoind/cruxcoin-qt
for Debian-based Linux systems. If you compile cruxcoind/cruxcoin-qt yourself, there are some useful files here.

## cruxcoin: URI support ##


cruxcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cruxcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cruxcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/cruxcoin128.png` to `/usr/share/pixmaps`

cruxcoin-qt.protocol (KDE)

