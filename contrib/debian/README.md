
Debian
====================
This directory contains files used to package scld/scl-qt
for Debian-based Linux systems. If you compile scld/scl-qt yourself, there are some useful files here.

## pivx: URI support ##


scl-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install scl-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your scl-qt binary to `/usr/bin`
and the `../../share/pixmaps/scl128.png` to `/usr/share/pixmaps`

scl-qt.protocol (KDE)

