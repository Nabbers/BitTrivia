
Debian
====================
This directory contains files used to package bittriviad/bittrivia-qt
for Debian-based Linux systems. If you compile bittriviad/bittrivia-qt yourself, there are some useful files here.

## bittrivia: URI support ##


bittrivia-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bittrivia-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bittrivia-qt binary to `/usr/bin`
and the `../../share/pixmaps/bittrivia128.png` to `/usr/share/pixmaps`

bittrivia-qt.protocol (KDE)

