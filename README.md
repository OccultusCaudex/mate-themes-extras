mate-themes-extras
==================

GTK2/3 themes optimized for GTK3-3.4.x

The mate-themes-extras package contains a collection of GTK2/3 desktop themes for MATE. These themes can change the appearance of application widgets, window borders, etc.

Themes:

--Adwaita-Cupertino-SL

--AmbianceBlue

--Ambiance-Xfce-LXDE-MATE

--Cologne

--drakfire-dream-black

--GnomishDark

--RadianceBlue

--Radiance-Xfce-LXDE-MATE

--Smootly

--Smootly-Black

--Sonar

--SonarBlue

--Zukitwo

--Zukitwo-Dark

--Zukitwo-Dust

--Zukitwo-Brave

--Zukitwo-Human

--Zukitwo-Illustrious

--Zukitwo-Noble

--Zukitwo-Wine

--Zukitwo-Wise

--Sonar-Icons


Installation:

You have to use autogen.sh with configure flags to enable a theme.

Without a flag nothing will compile!!!!!

This example for one theme, use ./configure --help after autogen.sh to find the right configure flags.

./autogen.sh \

--enable-Adwaita-Cupertino-SL

make

make install (as root)
