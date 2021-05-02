
Debian
====================
This directory contains files used to package hbcucoind/hbcucoin-qt
for Debian-based Linux systems. If you compile hbcucoind/hbcucoin-qt yourself, there are some useful files here.

## hbcucoin: URI support ##


hbcucoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hbcucoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hbcucoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

hbcucoin-qt.protocol (KDE)

