
Debian
====================
This directory contains files used to package cmdd/cmd-qt
for Debian-based Linux systems. If you compile cmdd/cmd-qt yourself, there are some useful files here.

## cmd: URI support ##


cmd-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cmd-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cmdqt binary to `/usr/bin`
and the `../../share/pixmaps/cmd128.png` to `/usr/share/pixmaps`

cmd-qt.protocol (KDE)

