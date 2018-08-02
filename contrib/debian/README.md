
Debian
====================
This directory contains files used to package xornd/xorn-qt
for Debian-based Linux systems. If you compile xornd/xorn-qt yourself, there are some useful files here.

## xorn: URI support ##


xorn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xorn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xornqt binary to `/usr/bin`
and the `../../share/pixmaps/xorn128.png` to `/usr/share/pixmaps`

xorn-qt.protocol (KDE)

