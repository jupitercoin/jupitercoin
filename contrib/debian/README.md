
Debian
====================
This directory contains files used to package jupitercoind/jupitercoin-qt
for Debian-based Linux systems. If you compile jupitercoind/jupitercoin-qt yourself, there are some useful files here.

## jupitercoin: URI support ##


jupitercoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install jupitercoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your jupitercoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

jupitercoin-qt.protocol (KDE)

