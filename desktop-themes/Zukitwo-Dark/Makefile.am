THEME_NAME=Zukitwo-Dark
 
themedir = $(datadir)/themes/$(THEME_NAME)

theme_DATA = \
	panelbg.png \
	index.theme

EXTRA_DIST = $(theme_DATA)

SUBDIRS =		\
	gtk-2.0		\
	gtk-3.0		\
	metacity-1	\
	gnome-shell \
	unity		\
	xfwm4

DIST_SUBDIRS =	\
	gtk-2.0		\
	gtk-3.0		\
	metacity-1	\
	gnome-shell \
	unity		\
	xfwm4

CLEANFILES = index.theme

index.theme: index.theme.in
	$(AM_V_GEN)sed \
		-e s!\@BACKGROUND_DIR\@!$(datadir)/backgrounds/mate/abstract! \
		< $< > $@
