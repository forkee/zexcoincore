
Debian
====================
This directory contains files used to package zexcoind/zexcoin-qt
for Debian-based Linux systems. If you compile zexcoind/zexcoin-qt yourself, there are some useful files here.

## zexcoin: URI support ##


zexcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zexcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zexcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/zexcoin128.png` to `/usr/share/pixmaps`

zexcoin-qt.protocol (KDE)

