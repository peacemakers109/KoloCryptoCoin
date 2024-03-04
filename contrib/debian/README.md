
Debian
====================
This directory contains files used to package nwccurrencyd/nwccurrency-qt
for Debian-based Linux systems. If you compile nwccurrencyd/nwccurrency-qt yourself, there are some useful files here.

## nwccurrency: URI support ##


nwccurrency-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nwccurrency-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nwccurrency-qt binary to `/usr/bin`
and the `../../share/pixmaps/nwccurrency128.png` to `/usr/share/pixmaps`

nwccurrency-qt.protocol (KDE)

