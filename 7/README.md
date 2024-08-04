Live USB Creator
This tool will make a bootable Live Linux USB disk. It is a GUI frontend for dd command.
It also features an option to create SparkyLinux live USB disk with persistence.

Copyright (C) 2013-2024 Paweł Pijanowski and others, see copyright file.
License: GPL-2

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Dependencies:
-------------
coreutils
gawk
grep
mount
sparky-remsu (>= 0.2.17)
yad
zenity
sed
fdisk
util-linux
e2fsprogs

Install:
-------------
su (or sudo) 
./install.sh

Uninstall:
-------------
su (or sudo)
./install.sh uninstall
