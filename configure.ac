AC_PREREQ(2.53)

AC_INIT([mate-themes-extras], [3.16.3], [http://www.raveit.de])

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
desktop-themes/DeLorean/Makefile
desktop-themes/DeLorean/chrome/Makefile
desktop-themes/DeLorean/chrome/images/Makefile
desktop-themes/DeLorean/chrome/images/tabbrowser/Makefile
desktop-themes/DeLorean/cinnamon/Makefile
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
])

AC_OUTPUT

dnl ==========================================================================
echo "
	mate-themes-extras-$VERSION:

	Installation prefix:                    ${prefix}

	Building desktop themes:
		Install Blue-Submarine:             ${enable_blue_submarine}
		Install DeLorean:                   ${enable_delorean}
		Install DeLorean-Dark:              ${enable_delorean_dark}
		Install Green-Submarine:            ${enable_green_submarine}
		Install GnomishBeige:               ${enable_gnomishbeige}

	configuration successfully :)  now type make
"
