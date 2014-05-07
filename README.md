mate-themes-extras-3
====================

GTK2/3 themes optimized for GTK3-3.6.x

The mate-themes-extras package contains a collection of GTK2/3 desktop themes for MATE. These themes can change the appearance of application widgets, window borders, etc.

Themes:

--Ambiance-blue

--Ambiance-lime

--Blue-Submarine

--clearlooks-phenix

--Cologne

--Delorean-Dark

--Faience

--Faience-Ocre

--Gnome-Cupertino

--Gnome-Cupertino-Mint

--GnomishBeige

--Green-Submarine

--RadianceBlue

--Radiance-Xfce-LXDE-MATE

--Smootly

--Smootly-Black

--Zukitwo

--Zukitwo-Brave

--Zukitwo-Dust

--Zukitwo-Human

--Zukitwo-Illustrious

--Zukitwo-Noble

--Zukitwo-Wine

--Zukitwo-Wise


Installation:

You have to use autogen.sh with configure flags to enable a theme.

Without a flag nothing will compile!

Use configure --help after autogen to find out the right configure flags for a theme.

--prefix=/usr is needed, otherwise the themes are installed in /usr/local/share/themes ,

and  mate-appearance-properties doesn't find the themes!

This example installs one theme.

./autogen.sh

./configure --prefix=/usr \

--enable-Gnome-Cupertino

make

make install (as root)
