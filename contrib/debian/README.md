
Debian
====================
This directory contains files used to package aneyd/aney-qt
for Debian-based Linux systems. If you compile aneyd/aney-qt yourself, there are some useful files here.

## pivx: URI support ##


aney-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aney-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aney-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

aney-qt.protocol (KDE)

