
Debian
====================
This directory contains files used to package ballcoind/ballcoin-qt
for Debian-based Linux systems. If you compile ballcoind/ballcoin-qt yourself, there are some useful files here.

## ballcoin: URI support ##


ballcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ballcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ballcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/ballcoin128.png` to `/usr/share/pixmaps`

ballcoin-qt.protocol (KDE)

