
Debian
====================
This directory contains files used to package VirtDexd/VirtDex-qt
for Debian-based Linux systems. If you compile VirtDexd/VirtDex-qt yourself, there are some useful files here.

## VirtDex: URI support ##


VirtDex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install VirtDex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your VirtDex-qt binary to `/usr/bin`
and the `../../share/pixmaps/VirtDex128.png` to `/usr/share/pixmaps`

VirtDex-qt.protocol (KDE)

