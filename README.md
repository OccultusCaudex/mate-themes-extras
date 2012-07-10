mate-themes-extras
==================

GTK2/3 themes optimized for GTK3-3.2.x

The mate-themes-extras package contains a collection of GTK2/3 desktop themes for MATE. These themes can change the appearance of application widgets, window borders, etc.

Themes:

--Adwaita-Cupertino-SL

--AmbianceBlue

--Ambiance-Xfce-LXDE-MATE

--ANewStartBlood

--Cologne

--drakfire-dream-black

--GnomishDark

--RadianceBlue

--Radiance-Xfce-LXDE-MATE

--Sonar

--SonarBlue

--Zukitwo

--Zukitwo-Dark

--Zukitwo-Dust

--Zukitwo-Brave

--Zukitwo-Colors

--Zukitwo-Human

--Zukitwo-Illustrious

--Zukitwo-Noble

--Zukitwo-Wine

--Zukitwo-Wise

--Sonar-Icons


Installation:

You have to use autogen.sh with configure flags to enable a theme.

Without a flag nothing will compile!

This will install all themes.

./autogen.sh \

--enable-Adwaita-Cupertino-SL \

--enable-AmbianceBlue \

--enable-Ambiance-Xfce-LXDE-MATE \

--enable-ANewStartBlood \

--enable-Cologne=yes \

--enable-drakfire-dream-black \

--enable-GnomishDark \

--enable-RadianceBlue \

--enable-Radiance-Xfce-LXDE-MATE \

--enable-Sonar \

--enable-SonarBlue \

--enable-Zukitwo \

--enable-Zukitwo-Dark \

--enable-Zukitwo-Dust \

--enable-Zukitwo-Brave \

--enable-Zukitwo-Colors \

--enable-Zukitwo-Human \

--enable-Zukitwo-Illustrious \

--enable-Zukitwo-Noble \

--enable-Zukitwo-Wine \

--enable-Zukitwo-Wise \

--enable-Sonar-Icons

make

make install (as root)
