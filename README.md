mate-themes-extras
====================

The mate-themes-extras package contains a collection of GTK2/3 desktop themes for MATE. These themes can change the appearance of application widgets, window borders, etc.
As everybody know you need an optimize package for GTK3 for your distro.
You can use several branches or release packages for download.

Branches:

master - development

GTK3-3.14

GTK3-3.12

GTK3-3.10

GTK3-3.8

GTK3-3.6

GTK3-3.4

GTK3-3.2

Releases:

https://github.com/NiceandGently/mate-themes-extras/releases

1.9.1 for GTK3-3.12

1.8.2 for GTK3-3.10

1.7.5 for GTK3-3.8

1.6.7 for GTK3-3.6

1.5.3 for GTK3-3.4

1.4.0 for GTK3-3.2

Themes:

--Blue-Submarine

--clearlooks-phenix

--delorean-dark

--Faience

--Faience-Ocre

--Gnome-Cupertino

--Gnome-Cupertino-Mint

--GnomishBeige

--Green-Submarine

--Smootly

--Smootly-Black

--Zukitwo


Installation:

Use NOCONFIGURE=1 ./autogen.sh for generate configure and make files.

You have to use ./configure with configure flags to enable a theme.

Without a flag nothing will compile!

Use configure --help after autogen to find out the right configure flags for a theme.

--prefix=/usr is needed, otherwise the themes are installed in /usr/local/share/themes ,

and  mate-appearance-properties doesn't find the themes!


Example for install Gnome-Cupertino theme:

NOCONFIGURE=1 ./autogen.sh

./configure --prefix=/usr \

--enable-Gnome-Cupertino

make

make install (as root)


Or simply copy the theme folders to ~./themes
