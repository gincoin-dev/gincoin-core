
Debian
====================
This directory contains files used to package gincoind/gincoin-qt
for Debian-based Linux systems. If you compile gincoind/gincoin-qt yourself, there are some useful files here.

## gincoin: URI support ##


gincoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gincoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gincoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/gincoin128.png` to `/usr/share/pixmaps`

gincoin-qt.protocol (KDE)

