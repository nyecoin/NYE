
Debian
====================
This directory contains files used to package nyecoind/nyecoin-qt
for Debian-based Linux systems. If you compile nyecoind/nyecoin-qt yourself, there are some useful files here.

## nyecoin: URI support ##


nyecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nyecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nyecoinqt binary to `/usr/bin`
and the `../../share/pixmaps/nyecoin128.png` to `/usr/share/pixmaps`

nyecoin-qt.protocol (KDE)

