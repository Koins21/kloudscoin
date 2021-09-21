
Debian
====================
This directory contains files used to package kloudcoinsd/kloudcoins-qt
for Debian-based Linux systems. If you compile kloudcoinsd/kloudcoins-qt yourself, there are some useful files here.

## kloudcoins: URI support ##


kloudcoins-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kloudcoins-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kloudcoinsqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

kloudcoins-qt.protocol (KDE)

