mate-themes-extras
==================

The mate-themes-extras package contains a collection of GTK2/3 desktop themes for MATE. These themes can change the appearance of application widgets, window borders, etc.
This package is optimized for GTK3-3.8.x

Themes:


--Blue-Submarine

--clearlooks-phenix

--Cologne

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

--Zukitwo-Dust

--Zukitwo-Brave

--Zukitwo-Human

--Zukitwo-Illustrious

--Zukitwo-Noble

--Zukitwo-Wine

--Zukitwo-Wise


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
