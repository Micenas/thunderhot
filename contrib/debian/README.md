
Debian
====================
This directory contains files used to package thunderhotd/thunderhot-qt
for Debian-based Linux systems. If you compile thunderhotd/thunderhot-qt yourself, there are some useful files here.

## thunderhot: URI support ##


thunderhot-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install thunderhot-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your thunderhotqt binary to `/usr/bin`
and the `../../share/pixmaps/thunderhot128.png` to `/usr/share/pixmaps`

thunderhot-qt.protocol (KDE)

