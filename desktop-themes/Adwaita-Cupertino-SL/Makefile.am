THEME_NAME=Adwaita-Cupertino-SL
 
themedir = $(datadir)/themes/$(THEME_NAME)

theme_DATA = index.theme \
	readme.txt \
	leeme.txt \
	LICENSE

EXTRA_DIST = $(theme_DATA)

SUBDIRS =		\
	gtk-2.0		\
	gtk-3.0		\
	metacity-1

DIST_SUBDIRS =		\
	gtk-2.0		\
	gtk-3.0		\
	metacity-1

CLEANFILES = index.theme

index.theme: index.theme.in
	$(AM_V_GEN)sed \
		-e s!\@BACKGROUND_DIR\@!$(datadir)/pixmaps/backgrounds/mate/abstract! \
		< $< > $@
