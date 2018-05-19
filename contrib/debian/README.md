
Debian
====================
This directory contains files used to package nuyuld/nuyul-qt
for Debian-based Linux systems. If you compile nuyuld/nuyul-qt yourself, there are some useful files here.

## nuyul: URI support ##


nuyul-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nuyul-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nuyulqt binary to `/usr/bin`
and the `../../share/pixmaps/nuyul128.png` to `/usr/share/pixmaps`

nuyul-qt.protocol (KDE)

