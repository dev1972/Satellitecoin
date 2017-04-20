
Debian
====================
This directory contains files used to package stlld/STLL-qt
for Debian-based Linux systems. If you compile stlld/STLL-qt yourself, there are some useful files here.

## stll: URI support ##


STLL-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install STLL-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stllqt binary to `/usr/bin`
and the `../../share/pixmaps/stll128.png` to `/usr/share/pixmaps`

STLL-qt.protocol (KDE)

