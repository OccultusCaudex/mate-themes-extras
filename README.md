mate-themes-extras
====================

The mate-themes-extras package contains a collection of GTK2/3 desktop themes for MATE. These themes can change the appearance of application widgets, window borders, etc.

This branch is optimized for GTK3-3.14.

Themes:

--Blue-Submarine

--clearlooks-phenix

--delorean-dark

--GnomishBeige

--Green-Submarine

--Smootly

--Smootly-Black

--Zukitwo

Note: Those themes aren't ready for GTK3-3.14, there is work from upstream needed.

But i don't wanna drop them for the momment.


--Faience

--Faience-Ocre

--Gnome-Cupertino

--Gnome-Cupertino-Mint


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


Needed gtk-engines:

Blue-Submarine, Green-Submarine: gtk-murrine-engine, gtk-unico-engine

clearlook-phenix: gtk2-engines (clearlooks)

DeLorean-Dark : gtk-murrine-engine

Faience, Faience-Ocre: gtk-murrine-engine, gtk-unico-engine

Gnome-Cupertino, Gnome-Cupertino-Mint: gtk-murrine-engine, gtk-unico-engine

GnomishBeige: gtk-murrine-engine

Smoothly, Smoothly-Black: gtk-smooth-engine

Zukitwo: gtk-murrine-engine


Other requirements (depends on the theme):

adwaita-icon-theme

mate-icon-theme

gnome-icon-theme

faience-icon-theme

Note: you can simply edit the index.theme file, if you want to use another icon-theme,

for example.
