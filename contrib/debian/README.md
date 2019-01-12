
Debian
====================
This directory contains files used to package stipendd/stipend-qt
for Debian-based Linux systems. If you compile stipendd/stipend-qt yourself, there are some useful files here.

## stipend: URI support ##


stipend-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install stipend-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stipend-qt binary to `/usr/bin`
and the `../../share/pixmaps/stipend128.png` to `/usr/share/pixmaps`

stipend-qt.protocol (KDE)
