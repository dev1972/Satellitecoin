
Debian
====================
This directory contains files used to package stlld/stll-qt
for Debian-based Linux systems. If you compile stlld/stll-qt yourself, there are some useful files here.

## stll: URI support ##


stll-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install stll-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stllqt binary to `/usr/bin`
and the `../../share/pixmaps/stll128.png` to `/usr/share/pixmaps`

stll-qt.protocol (KDE)

