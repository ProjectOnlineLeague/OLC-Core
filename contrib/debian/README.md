
Debian
====================
This directory contains files used to package olcd/olc-qt
for Debian-based Linux systems. If you compile olcd/olc-qt yourself, there are some useful files here.

## olc: URI support ##


olc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install olc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your olcqt binary to `/usr/bin`
and the `../../share/pixmaps/olc128.png` to `/usr/share/pixmaps`

olc-qt.protocol (KDE)

