AC_PREREQ(2.53)

AC_INIT([mate-themes-extras], [3.16.2], [http://www.raveit.de])

AM_INIT_AUTOMAKE([1.11 no-dist-gzip dist-xz tar-ustar check-news])

# Enable silent build rules by default, requires at least
# Automake-1.11. Disable by either passing --disable-silent-rules to
# configure or passing V=1 to make
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

PKG_PROG_PKG_CONFIG([0.19])

# Workaround to make aclocal get the right flags
AC_SUBST(ACLOCAL_AMFLAGS, "\${ACLOCAL_FLAGS}")

dnl ***************************************************************************
dnl *** Blue-Submarine checks							    				***
dnl ***************************************************************************
AC_ARG_ENABLE([Blue-Submarine],
    AC_HELP_STRING([--enable-Blue-Submarine], [Install the Blue-Submarine desktop theme.]),
    enable_blue_submarine=$enableval,
    enable_blue_submarine=no)
AM_CONDITIONAL(BUILD_BLUE_SUBMARINE, test "x$enable_blue_submarine" = "xyes")

dnl ***************************************************************************
dnl *** clearlooks-phenix specific checks                           	    ***
dnl ***************************************************************************
AC_ARG_ENABLE([clearlooks-phenix],
    AC_HELP_STRING([--enable-clearlooks-phenix], [Install the Clearlooks-Phenix desktop theme.]),
    enable_clearlooks_phenix=$enableval,
    enable_clearlooks_phenix=no)
AM_CONDITIONAL(BUILD_CLEARLOOKS_PHENIX, test "x$enable_clearlooks_phenix" = "xyes")

dnl ***************************************************************************
dnl *** Delorean specific checks                   	        	    ***
dnl ***************************************************************************
AC_ARG_ENABLE([DeLorean],
    AC_HELP_STRING([--enable-DeLorean], [Install the Delorean desktop theme.]),
    enable_delorean=$enableval,
    enable_delorean=no)
AM_CONDITIONAL(BUILD_DELOREAN, test "x$enable_delorean" = "xyes")

dnl ***************************************************************************
dnl *** Delorean-Dark specific checks                   	        	    ***
dnl ***************************************************************************
AC_ARG_ENABLE([DeLorean-Dark],
    AC_HELP_STRING([--enable-DeLorean-Dark], [Install the Delorean-Dark desktop theme.]),
    enable_delorean_dark=$enableval,
    enable_delorean_dark=no)
AM_CONDITIONAL(BUILD_DELOREAN_DARK, test "x$enable_delorean_dark" = "xyes")

dnl ***************************************************************************
dnl *** Faience specific checks                           	    			***
dnl ***************************************************************************
AC_ARG_ENABLE([Faience],
    AC_HELP_STRING([--enable-Faience], [Install the Faience desktop theme.]),
    enable_faience=$enableval,
    enable_faience=no)
AM_CONDITIONAL(BUILD_FAIENCE, test "x$enable_faience" = "xyes")

dnl ***************************************************************************
dnl *** Faience-Ocre specific checks                           	    		***
dnl ***************************************************************************
AC_ARG_ENABLE([Faience-Ocre],
    AC_HELP_STRING([--enable-Faience-Ocre], [Install the Faience-Ocre desktop theme.]),
    enable_faience_ocre=$enableval,
    enable_faience_ocre=no)
AM_CONDITIONAL(BUILD_FAIENCE_OCRE, test "x$enable_faience_ocre" = "xyes")

dnl ***************************************************************************
dnl *** Gnome-Cupertino specific checks                               		***
dnl ***************************************************************************
AC_ARG_ENABLE([Gnome-Cupertino],
    AC_HELP_STRING([--enable-Gnome-Cupertino], [Install the Gnome-Cupertino desktop theme.]),
    enable_gnome_cupertino=$enableval,
    enable_gnome_cupertino=no)
AM_CONDITIONAL(BUILD_GNOME_CUPERTINO, test "x$enable_gnome_cupertino" = "xyes")

dnl ***************************************************************************
dnl *** GnomishBeige checks						    						***
dnl ***************************************************************************
AC_ARG_ENABLE([GnomishBeige],
    AC_HELP_STRING([--enable-GnomishBeige], [Install the GnomishBeige desktop theme.]),
    enable_gnomishbeige=$enableval,
    enable_gnomishbeige=no)
AM_CONDITIONAL(BUILD_GNOMISHBEIGE, test "x$enable_gnomishbeige" = "xyes")

dnl ***************************************************************************
dnl *** Green-Submarine checks							    				***
dnl ***************************************************************************
AC_ARG_ENABLE([Green-Submarine],
    AC_HELP_STRING([--enable-Green-Submarine], [Install the Green-Submarine desktop theme.]),
    enable_green_submarine=$enableval,
    enable_green_submarine=no)
AM_CONDITIONAL(BUILD_GREEN_SUBMARINE, test "x$enable_green_submarine" = "xyes")

dnl ***************************************************************************
dnl *** Zukitwo checks							    						***
dnl ***************************************************************************
AC_ARG_ENABLE([Zukitwo],
    AC_HELP_STRING([--enable-Zukitwo], [Install the Zukitwo desktop theme.]),
    enable_zukitwo=$enableval,
    enable_zukitwo=no)
AM_CONDITIONAL(BUILD_ZUKITWO, test "x$enable_zukitwo" = "xyes")

AC_CONFIG_FILES([
Makefile
desktop-themes/Makefile
desktop-themes/Blue-Submarine/Makefile
desktop-themes/Blue-Submarine/cinnamon/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/apps/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/apps/Handles/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/apps/Panel/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/assets/Makefile
desktop-themes/Blue-Submarine/gtk-3.0/Makefile
desktop-themes/Blue-Submarine/gtk-3.0/assets/Makefile
desktop-themes/Blue-Submarine/metacity-1/Makefile
desktop-themes/clearlooks-phenix/Makefile
desktop-themes/clearlooks-phenix/doc/Makefile
desktop-themes/clearlooks-phenix/gtk-2.0/Makefile
desktop-themes/clearlooks-phenix/gtk-3.0/Makefile
desktop-themes/clearlooks-phenix/gtk-3.0/img/Makefile
desktop-themes/clearlooks-phenix/metacity-1/Makefile
desktop-themes/clearlooks-phenix/openbox-3/Makefile
desktop-themes/clearlooks-phenix/wallpapers/Makefile
desktop-themes/clearlooks-phenix/xfwm4/Makefile
desktop-themes/clearlooks-phenix/xfwm4/png/Makefile
desktop-themes/DeLorean/Makefile
desktop-themes/DeLorean/cinnamon/Makefile
desktop-themes/DeLorean/firefox/Makefile
desktop-themes/DeLorean/firefox/chrome/Makefile
desktop-themes/DeLorean/firefox/chrome/images/Makefile
desktop-themes/DeLorean/firefox/chrome/images/tabbrowser/Makefile
desktop-themes/DeLorean/gnome-shell/Makefile
desktop-themes/DeLorean/gtk-2.0/Makefile
desktop-themes/DeLorean/gtk-2.0/Arrows/Makefile
desktop-themes/DeLorean/gtk-2.0/Buttons/Makefile
desktop-themes/DeLorean/gtk-2.0/Check-Radio/Makefile
desktop-themes/DeLorean/gtk-2.0/Entry/Makefile
desktop-themes/DeLorean/gtk-2.0/Expanders/Makefile
desktop-themes/DeLorean/gtk-2.0/Handles/Makefile
desktop-themes/DeLorean/gtk-2.0/Lines/Makefile
desktop-themes/DeLorean/gtk-2.0/Menu-Menubar/Makefile
desktop-themes/DeLorean/gtk-2.0/Others/Makefile
desktop-themes/DeLorean/gtk-2.0/ProgressBar/Makefile
desktop-themes/DeLorean/gtk-2.0/Range/Makefile
desktop-themes/DeLorean/gtk-2.0/Scrollbars/Makefile
desktop-themes/DeLorean/gtk-2.0/Shadows/Makefile
desktop-themes/DeLorean/gtk-2.0/Spin/Makefile
desktop-themes/DeLorean/gtk-2.0/Tabs/Makefile
desktop-themes/DeLorean/gtk-2.0/Toolbar/Makefile
desktop-themes/DeLorean/gtk-3.0/Makefile
desktop-themes/DeLorean/gtk-3.0/assets/Makefile
desktop-themes/DeLorean/gtk-3.0/assets/SVGs/Makefile
desktop-themes/DeLorean/metacity-1/Makefile
desktop-themes/DeLorean/openbox-3/Makefile
desktop-themes/DeLorean/thunderbird/Makefile
desktop-themes/DeLorean/thunderbird/chrome/Makefile
desktop-themes/DeLorean/thunderbird/chrome/images/Makefile
desktop-themes/DeLorean/xfce-notify-4.0/Makefile
desktop-themes/DeLorean/xfce-notify-4.0/buttons/Makefile
desktop-themes/DeLorean/xfwm4/Makefile
desktop-themes/DeLorean-Dark/Makefile
desktop-themes/DeLorean-Dark/chrome/Makefile
desktop-themes/DeLorean-Dark/chrome/images/Makefile
desktop-themes/DeLorean-Dark/chrome/images/tabbrowser/Makefile
desktop-themes/DeLorean-Dark/cinnamon/Makefile
desktop-themes/DeLorean-Dark/gnome-shell/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Arrows/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Buttons/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Check-Radio/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Entry/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Expanders/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Handles/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Lines/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Menu-Menubar/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Others/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/ProgressBar/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Range/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Scrollbars/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Shadows/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Spin/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Tabs/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Toolbar/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/assets/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/assets/SVGs/Makefile
desktop-themes/DeLorean-Dark/metacity-1/Makefile
desktop-themes/DeLorean-Dark/openbox-3/Makefile
desktop-themes/DeLorean-Dark/Software-Center/Makefile
desktop-themes/DeLorean-Dark/unity/Makefile
desktop-themes/DeLorean-Dark/xfwm4/Makefile
desktop-themes/Faience/Makefile
desktop-themes/Faience/gnome-shell/Makefile
desktop-themes/Faience/gnome-shell/assets/Makefile
desktop-themes/Faience/gtk-2.0/Makefile
desktop-themes/Faience/gtk-2.0/apps/Makefile
desktop-themes/Faience/gtk-2.0/apps/Handles/Makefile
desktop-themes/Faience/gtk-2.0/apps/Caja/Makefile
desktop-themes/Faience/gtk-2.0/apps/Null/Makefile
desktop-themes/Faience/gtk-2.0/apps/Others/Makefile
desktop-themes/Faience/gtk-2.0/widgets/Makefile
desktop-themes/Faience/gtk-2.0/widgets/Null/Makefile
desktop-themes/Faience/gtk-2.0/widgets/Others/Makefile
desktop-themes/Faience/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Faience/gtk-3.0/Makefile
desktop-themes/Faience/gtk-3.0/apps/Makefile
desktop-themes/Faience/gtk-3.0/assets/Makefile
desktop-themes/Faience/metacity-1/Makefile
desktop-themes/Faience/unity/Makefile
desktop-themes/Faience-Ocre/Makefile
desktop-themes/Faience-Ocre/gtk-2.0/Makefile
desktop-themes/Faience-Ocre/gtk-2.0/apps/Makefile
desktop-themes/Faience-Ocre/gtk-2.0/apps/Handles/Makefile
desktop-themes/Faience-Ocre/gtk-2.0/apps/Nautilus/Makefile
desktop-themes/Faience-Ocre/gtk-2.0/apps/Null/Makefile
desktop-themes/Faience-Ocre/gtk-2.0/apps/Others/Makefile
desktop-themes/Faience-Ocre/gtk-2.0/widgets/Makefile
desktop-themes/Faience-Ocre/gtk-2.0/widgets/Null/Makefile
desktop-themes/Faience-Ocre/gtk-2.0/widgets/Others/Makefile
desktop-themes/Faience-Ocre/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Faience-Ocre/gtk-3.0/Makefile
desktop-themes/Faience-Ocre/gtk-3.0/assets/Makefile
desktop-themes/Faience-Ocre/metacity-1/Makefile
desktop-themes/Faience-Ocre/unity/Makefile
desktop-themes/Gnome-Cupertino/Makefile
desktop-themes/Gnome-Cupertino/gnome-shell/Makefile
desktop-themes/Gnome-Cupertino/gtk-2.0/Makefile
desktop-themes/Gnome-Cupertino/gtk-2.0/assets/Makefile
desktop-themes/Gnome-Cupertino/gtk-2.0/apps/Makefile
desktop-themes/Gnome-Cupertino/gtk-3.0/Makefile
desktop-themes/Gnome-Cupertino/gtk-3.0/assets/Makefile
desktop-themes/Gnome-Cupertino/gtk-3.0/apps/Makefile
desktop-themes/Gnome-Cupertino/metacity-1/Makefile
desktop-themes/Gnome-Cupertino/unity/Makefile
desktop-themes/GnomishBeige/Makefile
desktop-themes/GnomishBeige/gtk-2.0/Makefile
desktop-themes/GnomishBeige/gtk-2.0/Styles/Makefile
desktop-themes/GnomishBeige/gtk-3.0/Makefile
desktop-themes/GnomishBeige/gtk-3.0/assets/Makefile
desktop-themes/GnomishBeige/gtk-3.0/window-controls/Makefile
desktop-themes/GnomishBeige/metacity-1/Makefile
desktop-themes/GnomishBeige/unity/Makefile
desktop-themes/Green-Submarine/Makefile
desktop-themes/Green-Submarine/cinnamon/Makefile
desktop-themes/Green-Submarine/gtk-2.0/Makefile
desktop-themes/Green-Submarine/gtk-2.0/apps/Makefile
desktop-themes/Green-Submarine/gtk-2.0/apps/Handles/Makefile
desktop-themes/Green-Submarine/gtk-2.0/apps/Panel/Makefile
desktop-themes/Green-Submarine/gtk-2.0/assets/Makefile
desktop-themes/Green-Submarine/gtk-3.0/Makefile
desktop-themes/Green-Submarine/gtk-3.0/assets/Makefile
desktop-themes/Green-Submarine/metacity-1/Makefile
desktop-themes/Zukitwo/Makefile
desktop-themes/Zukitwo/gtk-2.0/Makefile
desktop-themes/Zukitwo/gtk-2.0/apps/Makefile
desktop-themes/Zukitwo/gtk-2.0/apps/Handles/Makefile
desktop-themes/Zukitwo/gtk-2.0/apps/Caja/Makefile
desktop-themes/Zukitwo/gtk-2.0/apps/Null/Makefile
desktop-themes/Zukitwo/gtk-2.0/apps/Others/Makefile
desktop-themes/Zukitwo/gtk-2.0/widgets/Makefile
desktop-themes/Zukitwo/gtk-2.0/widgets/Null/Makefile
desktop-themes/Zukitwo/gtk-2.0/widgets/Others/Makefile
desktop-themes/Zukitwo/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Zukitwo/gtk-2.0/widgets/Scale/Makefile
desktop-themes/Zukitwo/gtk-3.0/Makefile
desktop-themes/Zukitwo/gtk-3.0/assets/Makefile
desktop-themes/Zukitwo/gtk-3.0/borders/Makefile
desktop-themes/Zukitwo/gtk-3.0/window-controls/Makefile
desktop-themes/Zukitwo/gnome-shell/Makefile
desktop-themes/Zukitwo/metacity-1/Makefile
desktop-themes/Zukitwo/unity/Makefile
desktop-themes/Zukitwo/xfwm4/Makefile
])

AC_OUTPUT

dnl ==========================================================================
echo "
	mate-themes-extras-$VERSION:

	Installation prefix:                    ${prefix}

	Building desktop themes:
		Install Blue-Submarine:             ${enable_blue_submarine}
		Install Clearlooks-Phenix:          ${enable_clearlooks_phenix}
		Install DeLorean:                   ${enable_delorean}
		Install DeLorean-Dark:              ${enable_delorean_dark}
		Install Faience:              	    ${enable_faience}
		Install Faience-Ocre:               ${enable_faience_ocre}
		Install Gnome-Cupertino:            ${enable_gnome_cupertino}
		Install Green-Submarine:            ${enable_green_submarine}
		Install GnomishBeige:               ${enable_gnomishbeige}

	configuration successfully :)  now type make
"
