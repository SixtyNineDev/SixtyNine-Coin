
Debian
====================
This directory contains files used to package SixtyNined/SixtyNine-qt
for Debian-based Linux systems. If you compile SixtyNined/SixtyNine-qt yourself, there are some useful files here.

## SixtyNine: URI support ##


SixtyNine-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install SixtyNine-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your SixtyNineqt binary to `/usr/bin`
and the `../../share/pixmaps/SixtyNine128.png` to `/usr/share/pixmaps`

SixtyNine-qt.protocol (KDE)

