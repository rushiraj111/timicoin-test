
Debian
====================
This directory contains files used to package timicoind/timicoin-qt
for Debian-based Linux systems. If you compile timicoind/timicoin-qt yourself, there are some useful files here.

## timicoin: URI support ##


timicoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install timicoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your timicoinqt binary to `/usr/bin`
and the `../../share/pixmaps/timicoin128.png` to `/usr/share/pixmaps`

timicoin-qt.protocol (KDE)

