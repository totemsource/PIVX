
Debian
====================
This directory contains files used to package totemd/totem-qt
for Debian-based Linux systems. If you compile totemd/totem-qt yourself, there are some useful files here.

## totem: URI support ##


totem-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install totem-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your totemqt binary to `/usr/bin`
and the `../../share/pixmaps/totem128.png` to `/usr/share/pixmaps`

totem-qt.protocol (KDE)

