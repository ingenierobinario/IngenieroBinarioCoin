
Debian
====================
This directory contains files used to package dashd/ingenierobinariocoin-qt
for Debian-based Linux systems. If you compile dashd/ingenierobinariocoin-qt yourself, there are some useful files here.

## ingenierobinariocoin: URI support ##


ingenierobinariocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ingenierobinariocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ingenierobinariocoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/dash128.png` to `/usr/share/pixmaps`

ingenierobinariocoin-qt.protocol (KDE)

