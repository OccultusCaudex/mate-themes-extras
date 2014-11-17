mate-themes-extras
==================

The mate-themes-extras package contains a collection of GTK2/3 desktop themes for MATE. These themes can change the appearance of application widgets, window borders, etc.
This branch is optimized for GTK3-3.8.x

Themes:


--Blue-Submarine

--clearlooks-phenix

--delorean-dark

--Faience

--Faience-Ocre

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


Example for install Blue-Submarine theme:

NOCONFIGURE=1 ./autogen.sh

./configure --prefix=/usr \

--enable-Blue-Submarine

make

make install (as root)



Anther way to install is simple copy the theme folders to ~/themes


Needed gtk-engines:

Blue-Submarine, Green-Submarine: gtk-murrine-engine, gtk-unico-engine

clearlook-phenix: gtk2-engines (clearlooks)

Cologne: gtk-xfce-engine

DeLorean-Dark : gtk-murrine-engine

Faience, Faience-Ocre: gtk-murrine-engine, gtk-unico-engine

Gnome-Cupertino, Gnome-Cupertino-Mint: gtk-murrine-engine, gtk-unico-engine

GnomishBeige: gtk-murrine-engine

Smoothly, Smoothly-Black: gtk-smooth-engine

Zukitwo: gtk-murrine-engine

Zukitwo Color themes: gtk-murrine-engine, gtk-unico-engine
