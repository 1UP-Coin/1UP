
Debian
====================
This directory contains files used to package 1upd/1up-qt
for Debian-based Linux systems. If you compile 1upd/1up-qt yourself, there are some useful files here.

## 1up: URI support ##


1up-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install 1up-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your 1upqt binary to `/usr/bin`
and the `../../share/pixmaps/1up128.png` to `/usr/share/pixmaps`

1up-qt.protocol (KDE)

