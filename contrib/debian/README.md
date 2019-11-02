
Debian
====================
This directory contains files used to package jebatcoind/jebatcoin-qt
for Debian-based Linux systems. If you compile jebatcoind/jebatcoin-qt yourself, there are some useful files here.

## jebatcoin: URI support ##


jebatcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install jebatcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your jebatcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/jebatcoin128.png` to `/usr/share/pixmaps`

jebatcoin-qt.protocol (KDE)

