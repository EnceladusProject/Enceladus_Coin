
Debian
====================
This directory contains files used to package enceladusd/enceladus-qt
for Debian-based Linux systems. If you compile enceladusd/enceladus-qt yourself, there are some useful files here.

## enceladus: URI support ##


enceladus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install enceladus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your enceladusqt binary to `/usr/bin`
and the `../../share/pixmaps/enceladus128.png` to `/usr/share/pixmaps`

enceladus-qt.protocol (KDE)

