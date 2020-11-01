
Debian
====================
This directory contains files used to package khrysusd/khrysus-qt
for Debian-based Linux systems. If you compile khrysusd/khrysus-qt yourself, there are some useful files here.

## khrysus: URI support ##


khrysus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install khrysus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your khrysusqt binary to `/usr/bin`
and the `../../share/pixmaps/khrysus128.png` to `/usr/share/pixmaps`

khrysus-qt.protocol (KDE)

