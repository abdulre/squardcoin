
Debian
====================
This directory contains files used to package squardcoind/squardcoin-qt
for Debian-based Linux systems. If you compile squardcoind/squardcoin-qt yourself, there are some useful files here.

## squardcoin: URI support ##


squardcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install squardcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your squardcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/squardcoin128.png` to `/usr/share/pixmaps`

squardcoin-qt.protocol (KDE)

