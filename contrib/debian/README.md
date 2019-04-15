
Debian
====================
This directory contains files used to package panamd/panam-qt
for Debian-based Linux systems. If you compile panamd/panam-qt yourself, there are some useful files here.

## panam: URI support ##


panam-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install panam-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your panamqt binary to `/usr/bin`
and the `../../share/pixmaps/panam128.png` to `/usr/share/pixmaps`

panam-qt.protocol (KDE)

