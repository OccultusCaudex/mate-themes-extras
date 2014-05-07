AC_PREREQ(2.53)

AC_INIT([mate-themes-extras-5], [1.7.11], [http://www.raveit.de])

AM_INIT_AUTOMAKE([1.11 no-dist-gzip dist-xz tar-ustar])

# Enable silent build rules by default, requires at least
# Automake-1.11. Disable by either passing --disable-silent-rules to
# configure or passing V=1 to make
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

PKG_PROG_PKG_CONFIG([0.19])

# Workaround to make aclocal get the right flags
AC_SUBST(ACLOCAL_AMFLAGS, "\${ACLOCAL_FLAGS}")

# Check GTK+ theme engines
PKG_CHECK_MODULES(THEME_ENGINE,
 [gtk+-2.0 >= 2.0.0 dnl
  gdk-pixbuf-2.0 >= 2.0.0 ]) 

GTK_VERSION=`$PKG_CONFIG --variable=gtk_binary_version gtk+-2.0`
AC_SUBST(GTK_VERSION)

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
dnl *** Cologne specific checks                           		    		***
dnl ***************************************************************************
AC_ARG_ENABLE([Cologne],
    AC_HELP_STRING([--enable-Cologne], [Install the Cologne desktop theme.]),
    enable_cologne=$enableval,
    enable_cologne=no)
AM_CONDITIONAL(BUILD_COLOGNE, test "x$enable_cologne" = "xyes")

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
dnl *** Gnome-Cupertino-Mint specific checks                                ***
dnl ***************************************************************************
AC_ARG_ENABLE([Gnome-Cupertino-Mint],
    AC_HELP_STRING([--enable-Gnome-Cupertino-Mint], [Install the Gnome-Cupertino-Mint desktop theme.]),
    enable_gnome_cupertino_mint=$enableval,
    enable_gnome_cupertino_mint=no)
AM_CONDITIONAL(BUILD_GNOME_CUPERTINO_MINT, test "x$enable_gnome_cupertino_mint" = "xyes")

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
dnl *** Smoothly checks							    						***
dnl ***************************************************************************
AC_ARG_ENABLE([Smoothly],
    AC_HELP_STRING([--enable-Smoothly], [Install the Smoothly desktop theme.]),
    enable_smootly=$enableval,
    enable_smootly=no)
AM_CONDITIONAL(BUILD_SMOOTLY, test "x$enable_smootly" = "xyes")

dnl ***************************************************************************
dnl *** Smoothly-Black checks							    				***
dnl ***************************************************************************
AC_ARG_ENABLE([Smoothly-Black],
    AC_HELP_STRING([--enable-Smoothly-Black], [Install the Smoothly-Black desktop theme.]),
    enable_smootly_black=$enableval,
    enable_smootly_black=no)
AM_CONDITIONAL(BUILD_SMOOTLY_BLACK, test "x$enable_smootly_black" = "xyes")

dnl ***************************************************************************
dnl *** Zukitwo checks							    						***
dnl ***************************************************************************
AC_ARG_ENABLE([Zukitwo],
    AC_HELP_STRING([--enable-Zukitwo], [Install the Zukitwo desktop theme.]),
    enable_zukitwo=$enableval,
    enable_zukitwo=no)
AM_CONDITIONAL(BUILD_ZUKITWO, test "x$enable_zukitwo" = "xyes")

dnl ***************************************************************************
dnl *** Zukitwo-Brave checks						    					***
dnl ***************************************************************************
AC_ARG_ENABLE([Zukitwo-Brave],
    AC_HELP_STRING([--enable-Zukitwo-Brave], [Install the Zukitwo-Brave desktop theme.]),
    enable_zukitwo_brave=$enableval,
    enable_zukitwo_brave=no)
AM_CONDITIONAL(BUILD_ZUKITWO_BRAVE, test "x$enable_zukitwo_brave" = "xyes")

dnl ***************************************************************************
dnl *** Zukitwo-Dust checks						    						***
dnl ***************************************************************************
AC_ARG_ENABLE([Zukitwo-Dust],
    AC_HELP_STRING([--enable-Zukitwo-Dust], [Install the Zukitwo-Dust desktop theme.]),
    enable_zukitwo_dust=$enableval,
    enable_zukitwo_dust=no)
AM_CONDITIONAL(BUILD_ZUKITWO_DUST, test "x$enable_zukitwo_dust" = "xyes")

dnl ***************************************************************************
dnl *** Zukitwo-Human checks						    					***
dnl ***************************************************************************
AC_ARG_ENABLE([Zukitwo-Human],
    AC_HELP_STRING([--enable-Zukitwo-Human], [Install the Zukitwo-Human desktop theme.]),
    enable_zukitwo_human=$enableval,
    enable_zukitwo_human=no)
AM_CONDITIONAL(BUILD_ZUKITWO_HUMAN, test "x$enable_zukitwo_human" = "xyes")

dnl ***************************************************************************
dnl *** Zukitwo-Illustrious checks					    					***
dnl ***************************************************************************
AC_ARG_ENABLE([Zukitwo-Illustrious],
    AC_HELP_STRING([--enable-Zukitwo-Illustrious], [Install the Zukitwo-Illustrious desktop theme.]),
    enable_zukitwo_illustrious=$enableval,
    enable_zukitwo_illustrious=no)
AM_CONDITIONAL(BUILD_ZUKITWO_ILLUSTRIOUS, test "x$enable_zukitwo_illustrious" = "xyes")

dnl ***************************************************************************
dnl *** Zukitwo-Noble checks						    					***
dnl ***************************************************************************
AC_ARG_ENABLE([Zukitwo-Noble],
    AC_HELP_STRING([--enable-Zukitwo-Noble], [Install the Zukitwo-Noble desktop theme.]),
    enable_zukitwo_noble=$enableval,
    enable_zukitwo_noble=no)
AM_CONDITIONAL(BUILD_ZUKITWO_NOBLE, test "x$enable_zukitwo_noble" = "xyes")

dnl ***************************************************************************
dnl *** Zukitwo-Wine checks						    						***
dnl ***************************************************************************
AC_ARG_ENABLE([Zukitwo-Wine],
    AC_HELP_STRING([--enable-Zukitwo-Wine], [Install the Zukitwo-Wine desktop theme.]),
    enable_zukitwo_wine=$enableval,
    enable_zukitwo_wine=no)
AM_CONDITIONAL(BUILD_ZUKITWO_WINE, test "x$enable_zukitwo_wine" = "xyes")

dnl ***************************************************************************
dnl *** Zukitwo-Wise checks						    						***
dnl ***************************************************************************
AC_ARG_ENABLE([Zukitwo-Wise],
    AC_HELP_STRING([--enable-Zukitwo-Wise], [Install the Zukitwo-Wise desktop theme.]),
    enable_zukitwo_wise=$enableval,
    enable_zukitwo_wise=no)
AM_CONDITIONAL(BUILD_ZUKITWO_WISE, test "x$enable_zukitwo_wise" = "xyes")


dnl ***************************************************************************
dnl *** Zukitwo-Colors checks						    					***
dnl ***************************************************************************
AC_ARG_ENABLE([Zukitwo-Colors],
    AC_HELP_STRING([--enable-Zukitwo-Colors], [Install the Zukitwo-Colors desktop theme.]),
    enable_zukitwo_colors=$enableval,
    enable_zukitwo_colors=no)
AM_CONDITIONAL(BUILD_ZUKITWO_COLORS, test "x$enable_zukitwo_colors" = "xyes")

AC_CONFIG_FILES([
Makefile
desktop-themes/Makefile
desktop-themes/Blue-Submarine/Makefile
desktop-themes/Blue-Submarine/cinnamon/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/apps/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/apps/Caja/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/apps/Handles/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/apps/Null/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/apps/Others/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/widgets/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/widgets/Null/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/widgets/Others/Makefile
desktop-themes/Blue-Submarine/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Blue-Submarine/gtk-3.0/Makefile
desktop-themes/Blue-Submarine/gtk-3.0/apps/Makefile
desktop-themes/Blue-Submarine/gtk-3.0/assets/Makefile
desktop-themes/Blue-Submarine/metacity-1/Makefile
desktop-themes/Blue-Submarine/unity/Makefile
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
desktop-themes/Cologne/Makefile
desktop-themes/Cologne/gtk-2.0/Makefile
desktop-themes/Cologne/gtk-2.0/Styles/Makefile
desktop-themes/Cologne/gtk-3.0/Makefile
desktop-themes/Cologne/metacity-1/Makefile
desktop-themes/DeLorean-Dark/Makefile
desktop-themes/DeLorean-Dark/cinnamon/Makefile
desktop-themes/DeLorean-Dark/gnome-shell/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/arrows/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/buttons/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/check-radio/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/columns/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/entry/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/expanders/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/frames/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/frames/etched/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/handles/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/other/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/other/handlebox/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/progress/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/range/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/scroll/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/separator/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/shadows/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/spin/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/tabs/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/images/toolbar/Makefile
desktop-themes/DeLorean-Dark/gtk-2.0/panel-background/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/assets/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/assets/check-radio/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/assets/menu-check/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/assets/scale-slider/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/assets/scroll/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/assets/sidebar-radio/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/button/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/column/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/entry/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/inline/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/primary/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/raised/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/scale/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/separator/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/switch/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/tooltip/Makefile
desktop-themes/DeLorean-Dark/gtk-3.0/borders/trough/Makefile
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
desktop-themes/Faience-Ocre/gnome-shell/Makefile
desktop-themes/Faience-Ocre/gnome-shell/assets/Makefile
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
desktop-themes/Gnome-Cupertino/gtk-2.0/Makefile
desktop-themes/Gnome-Cupertino/gtk-2.0/assets/Makefile
desktop-themes/Gnome-Cupertino/gtk-2.0/apps/Makefile
desktop-themes/Gnome-Cupertino/gtk-3.0/Makefile
desktop-themes/Gnome-Cupertino/gtk-3.0/assets/Makefile
desktop-themes/Gnome-Cupertino/gtk-3.0/apps/Makefile
desktop-themes/Gnome-Cupertino/metacity-1/Makefile
desktop-themes/Gnome-Cupertino/unity/Makefile
desktop-themes/Gnome-Cupertino-Mint/Makefile
desktop-themes/Gnome-Cupertino-Mint/gtk-2.0/Makefile
desktop-themes/Gnome-Cupertino-Mint/gtk-2.0/assets/Makefile
desktop-themes/Gnome-Cupertino-Mint/gtk-2.0/apps/Makefile
desktop-themes/Gnome-Cupertino-Mint/gtk-3.0/Makefile
desktop-themes/Gnome-Cupertino-Mint/gtk-3.0/assets/Makefile
desktop-themes/Gnome-Cupertino-Mint/gtk-3.0/apps/Makefile
desktop-themes/Gnome-Cupertino-Mint/metacity-1/Makefile
desktop-themes/Gnome-Cupertino-Mint/unity/Makefile
desktop-themes/GnomishBeige/Makefile
desktop-themes/GnomishBeige/gtk-2.0/Makefile
desktop-themes/GnomishBeige/gtk-2.0/Styles/Makefile
desktop-themes/GnomishBeige/gtk-3.0/Makefile
desktop-themes/GnomishBeige/gtk-3.0/assets/Makefile
desktop-themes/GnomishBeige/metacity-1/Makefile
desktop-themes/GnomishBeige/gnome-shell/Makefile
desktop-themes/GnomishBeige/gnome-shell/dashtodock/Makefile
desktop-themes/Green-Submarine/Makefile
desktop-themes/Green-Submarine/cinnamon/Makefile
desktop-themes/Green-Submarine/gtk-2.0/Makefile
desktop-themes/Green-Submarine/gtk-2.0/apps/Makefile
desktop-themes/Green-Submarine/gtk-2.0/apps/Caja/Makefile
desktop-themes/Green-Submarine/gtk-2.0/apps/Handles/Makefile
desktop-themes/Green-Submarine/gtk-2.0/apps/Null/Makefile
desktop-themes/Green-Submarine/gtk-2.0/apps/Others/Makefile
desktop-themes/Green-Submarine/gtk-2.0/widgets/Makefile
desktop-themes/Green-Submarine/gtk-2.0/widgets/Null/Makefile
desktop-themes/Green-Submarine/gtk-2.0/widgets/Others/Makefile
desktop-themes/Green-Submarine/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Green-Submarine/gtk-3.0/Makefile
desktop-themes/Green-Submarine/gtk-3.0/apps/Makefile
desktop-themes/Green-Submarine/gtk-3.0/assets/Makefile
desktop-themes/Green-Submarine/metacity-1/Makefile
desktop-themes/Green-Submarine/unity/Makefile
desktop-themes/Smoothly/Makefile
desktop-themes/Smoothly/gtk-2.0/Makefile
desktop-themes/Smoothly/gtk-2.0/assets/Makefile
desktop-themes/Smoothly/gtk-3.0/Makefile
desktop-themes/Smoothly/gtk-3.0/assets/Makefile
desktop-themes/Smoothly/metacity-1/Makefile
desktop-themes/Smoothly-Black/Makefile
desktop-themes/Smoothly-Black/gtk-2.0/Makefile
desktop-themes/Smoothly-Black/gtk-2.0/assets/Makefile
desktop-themes/Smoothly-Black/gtk-3.0/Makefile
desktop-themes/Smoothly-Black/metacity-1/Makefile
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
desktop-themes/Zukitwo/gnome-shell/Makefile
desktop-themes/Zukitwo/metacity-1/Makefile
desktop-themes/Zukitwo/unity/Makefile
desktop-themes/Zukitwo/xfwm4/Makefile
desktop-themes/Zukitwo-Dust/Makefile
desktop-themes/Zukitwo-Dust/cinnamon/Makefile
desktop-themes/Zukitwo-Dust/gnome-shell/Makefile
desktop-themes/Zukitwo-Dust/unity/Makefile
desktop-themes/Zukitwo-Dust/xfwm4/Makefile
desktop-themes/Zukitwo-Dust/gtk-2.0/Makefile
desktop-themes/Zukitwo-Dust/gtk-2.0/apps/Makefile
desktop-themes/Zukitwo-Dust/gtk-2.0/apps/Caja/Makefile
desktop-themes/Zukitwo-Dust/gtk-2.0/apps/Handles/Makefile
desktop-themes/Zukitwo-Dust/gtk-2.0/apps/Nautilus/Makefile
desktop-themes/Zukitwo-Dust/gtk-2.0/apps/Null/Makefile
desktop-themes/Zukitwo-Dust/gtk-2.0/apps/Others/Makefile
desktop-themes/Zukitwo-Dust/gtk-2.0/widgets/Makefile
desktop-themes/Zukitwo-Dust/gtk-2.0/widgets/Null/Makefile
desktop-themes/Zukitwo-Dust/gtk-2.0/widgets/Others/Makefile
desktop-themes/Zukitwo-Dust/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Zukitwo-Dust/gtk-3.0/Makefile
desktop-themes/Zukitwo-Dust/gtk-3.0/apps/Makefile
desktop-themes/Zukitwo-Dust/metacity-1/Makefile
desktop-themes/Zukitwo-Brave/Makefile
desktop-themes/Zukitwo-Brave/cinnamon/Makefile
desktop-themes/Zukitwo-Brave/gnome-shell/Makefile
desktop-themes/Zukitwo-Brave/unity/Makefile
desktop-themes/Zukitwo-Brave/gtk-2.0/Makefile
desktop-themes/Zukitwo-Brave/gtk-2.0/apps/Makefile
desktop-themes/Zukitwo-Brave/gtk-2.0/apps/Caja/Makefile
desktop-themes/Zukitwo-Brave/gtk-2.0/apps/Handles/Makefile
desktop-themes/Zukitwo-Brave/gtk-2.0/apps/Nautilus/Makefile
desktop-themes/Zukitwo-Brave/gtk-2.0/apps/Null/Makefile
desktop-themes/Zukitwo-Brave/gtk-2.0/apps/Others/Makefile
desktop-themes/Zukitwo-Brave/gtk-2.0/widgets/Makefile
desktop-themes/Zukitwo-Brave/gtk-2.0/widgets/Null/Makefile
desktop-themes/Zukitwo-Brave/gtk-2.0/widgets/Others/Makefile
desktop-themes/Zukitwo-Brave/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Zukitwo-Brave/gtk-3.0/Makefile
desktop-themes/Zukitwo-Brave/gtk-3.0/apps/Makefile
desktop-themes/Zukitwo-Human/Makefile
desktop-themes/Zukitwo-Human/cinnamon/Makefile
desktop-themes/Zukitwo-Human/gnome-shell/Makefile
desktop-themes/Zukitwo-Human/unity/Makefile
desktop-themes/Zukitwo-Human/gtk-2.0/Makefile
desktop-themes/Zukitwo-Human/gtk-2.0/apps/Makefile
desktop-themes/Zukitwo-Human/gtk-2.0/apps/Caja/Makefile
desktop-themes/Zukitwo-Human/gtk-2.0/apps/Handles/Makefile
desktop-themes/Zukitwo-Human/gtk-2.0/apps/Nautilus/Makefile
desktop-themes/Zukitwo-Human/gtk-2.0/apps/Null/Makefile
desktop-themes/Zukitwo-Human/gtk-2.0/apps/Others/Makefile
desktop-themes/Zukitwo-Human/gtk-2.0/widgets/Makefile
desktop-themes/Zukitwo-Human/gtk-2.0/widgets/Null/Makefile
desktop-themes/Zukitwo-Human/gtk-2.0/widgets/Others/Makefile
desktop-themes/Zukitwo-Human/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Zukitwo-Human/gtk-3.0/Makefile
desktop-themes/Zukitwo-Human/gtk-3.0/apps/Makefile
desktop-themes/Zukitwo-Illustrious/Makefile
desktop-themes/Zukitwo-Illustrious/cinnamon/Makefile
desktop-themes/Zukitwo-Illustrious/gnome-shell/Makefile
desktop-themes/Zukitwo-Illustrious/unity/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-2.0/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-2.0/apps/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-2.0/apps/Caja/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-2.0/apps/Handles/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-2.0/apps/Nautilus/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-2.0/apps/Null/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-2.0/apps/Others/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-2.0/widgets/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-2.0/widgets/Null/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-2.0/widgets/Others/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-3.0/Makefile
desktop-themes/Zukitwo-Illustrious/gtk-3.0/apps/Makefile
desktop-themes/Zukitwo-Noble/Makefile
desktop-themes/Zukitwo-Noble/cinnamon/Makefile
desktop-themes/Zukitwo-Noble/gnome-shell/Makefile
desktop-themes/Zukitwo-Noble/unity/Makefile
desktop-themes/Zukitwo-Noble/gtk-2.0/Makefile
desktop-themes/Zukitwo-Noble/gtk-2.0/apps/Makefile
desktop-themes/Zukitwo-Noble/gtk-2.0/apps/Caja/Makefile
desktop-themes/Zukitwo-Noble/gtk-2.0/apps/Handles/Makefile
desktop-themes/Zukitwo-Noble/gtk-2.0/apps/Nautilus/Makefile
desktop-themes/Zukitwo-Noble/gtk-2.0/apps/Null/Makefile
desktop-themes/Zukitwo-Noble/gtk-2.0/apps/Others/Makefile
desktop-themes/Zukitwo-Noble/gtk-2.0/widgets/Makefile
desktop-themes/Zukitwo-Noble/gtk-2.0/widgets/Null/Makefile
desktop-themes/Zukitwo-Noble/gtk-2.0/widgets/Others/Makefile
desktop-themes/Zukitwo-Noble/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Zukitwo-Noble/gtk-3.0/Makefile
desktop-themes/Zukitwo-Noble/gtk-3.0/apps/Makefile
desktop-themes/Zukitwo-Wine/Makefile
desktop-themes/Zukitwo-Wine/cinnamon/Makefile
desktop-themes/Zukitwo-Wine/gnome-shell/Makefile
desktop-themes/Zukitwo-Wine/unity/Makefile
desktop-themes/Zukitwo-Wine/gtk-2.0/Makefile
desktop-themes/Zukitwo-Wine/gtk-2.0/apps/Makefile
desktop-themes/Zukitwo-Wine/gtk-2.0/apps/Caja/Makefile
desktop-themes/Zukitwo-Wine/gtk-2.0/apps/Handles/Makefile
desktop-themes/Zukitwo-Wine/gtk-2.0/apps/Nautilus/Makefile
desktop-themes/Zukitwo-Wine/gtk-2.0/apps/Null/Makefile
desktop-themes/Zukitwo-Wine/gtk-2.0/apps/Others/Makefile
desktop-themes/Zukitwo-Wine/gtk-2.0/widgets/Makefile
desktop-themes/Zukitwo-Wine/gtk-2.0/widgets/Null/Makefile
desktop-themes/Zukitwo-Wine/gtk-2.0/widgets/Others/Makefile
desktop-themes/Zukitwo-Wine/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Zukitwo-Wine/gtk-3.0/Makefile
desktop-themes/Zukitwo-Wine/gtk-3.0/apps/Makefile
desktop-themes/Zukitwo-Wise/Makefile
desktop-themes/Zukitwo-Wise/cinnamon/Makefile
desktop-themes/Zukitwo-Wise/gnome-shell/Makefile
desktop-themes/Zukitwo-Wise/unity/Makefile
desktop-themes/Zukitwo-Wise/gtk-2.0/Makefile
desktop-themes/Zukitwo-Wise/gtk-2.0/apps/Makefile
desktop-themes/Zukitwo-Wise/gtk-2.0/apps/Caja/Makefile
desktop-themes/Zukitwo-Wise/gtk-2.0/apps/Handles/Makefile
desktop-themes/Zukitwo-Wise/gtk-2.0/apps/Nautilus/Makefile
desktop-themes/Zukitwo-Wise/gtk-2.0/apps/Null/Makefile
desktop-themes/Zukitwo-Wise/gtk-2.0/apps/Others/Makefile
desktop-themes/Zukitwo-Wise/gtk-2.0/widgets/Makefile
desktop-themes/Zukitwo-Wise/gtk-2.0/widgets/Null/Makefile
desktop-themes/Zukitwo-Wise/gtk-2.0/widgets/Others/Makefile
desktop-themes/Zukitwo-Wise/gtk-2.0/widgets/Panel/Makefile
desktop-themes/Zukitwo-Wise/gtk-3.0/Makefile
desktop-themes/Zukitwo-Wise/gtk-3.0/apps/Makefile
desktop-themes/Zukitwo-Colors/Makefile
desktop-themes/Zukitwo-Colors/cinnamon/Makefile
desktop-themes/Zukitwo-Colors/gnome-shell/Makefile
desktop-themes/Zukitwo-Colors/metacity-1/Makefile
desktop-themes/Zukitwo-Colors/xfwm4/Makefile
])

AC_OUTPUT

dnl ==========================================================================
echo "
	mate-themes-extras-$VERSION:

	Installation prefix:                    ${prefix}

	Building desktop themes:
		Install Blue-Submarine:             ${enable_blue_submarine}
		Install Clearlooks-Phenix:          ${enable_clearlooks_phenix}
		Install Cologne:                    ${enable_cologne}
		Install DeLorean-Dark:              ${enable_delorean_dark}
		Install Faience:              	    ${enable_faience}
		Install Faience-Ocre:               ${enable_faience_ocre}
		Install Gnome-Cupertino:            ${enable_gnome_cupertino}
		Install Gnome-Cupertino-Mint:       ${enable_gnome_cupertino_mint}
		Install Green-Submarine:            ${enable_green_submarine}
		Install GnomishBeige:               ${enable_gnomishbeige}
		Install Smoothly:                   ${enable_smootly}
		Install Smoothly-Black:             ${enable_smootly_black}
		Install Zukitwo:                    ${enable_zukitwo}
		Install Zukitwo-Dust:               ${enable_zukitwo_dust}
		Install Zukitwo-Brave:              ${enable_zukitwo_brave}
		Install Zukitwo-Human:              ${enable_zukitwo_human}
		Install Zukitwo-Illustrious:        ${enable_zukitwo_illustrious}
		Install Zukitwo-Noble:              ${enable_zukitwo_noble}
		Install Zukitwo-Wine:               ${enable_zukitwo_wine}
		Install Zukitwo-Wise:               ${enable_zukitwo_wise}
		Install Zukitwo-Colors:             ${enable_zukitwo_colors}

	configuration successfully :)  now type make
"
