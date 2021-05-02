
Debian
====================
This directory contains files used to package hbcurd/hbcur-qt
for Debian-based Linux systems. If you compile hbcurd/hbcur-qt yourself, there are some useful files here.

## hbcur: URI support ##


hbcur-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hbcur-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hbcurqt binary to `/usr/bin`
and the `../../share/pixmaps/hbcur128.png` to `/usr/share/pixmaps`

hbcur-qt.protocol (KDE)

