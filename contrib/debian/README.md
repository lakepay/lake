
Debian
====================
This directory contains files used to package laked/lake-qt
for Debian-based Linux systems. If you compile laked/lake-qt yourself, there are some useful files here.

## lake: URI support ##


lake-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lake-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lake-qt binary to `/usr/bin`
and the `../../share/pixmaps/lake128.png` to `/usr/share/pixmaps`

lake-qt.protocol (KDE)

