THEME_NAME=Gnome-Cupertino-Mint
 
themedir = $(datadir)/themes/$(THEME_NAME)

theme_DATA = index.theme \
	change-log.txt \
	leeme.txt \
	LICENSE \
	metacity-lion-buttons.tar.gz \
	metacity-sl-buttons.tar.gz \
	unity-lion-buttons.tar.gz \
	unity-sl-buttons.tar.gz \
	readme.txt

EXTRA_DIST = $(theme_DATA)

SUBDIRS =		\
	gtk-2.0		\
	gtk-3.0		\
	metacity-1 \
	unity

DIST_SUBDIRS =		\
	gtk-2.0		\
	gtk-3.0		\
	metacity-1 \
	unity

CLEANFILES = index.theme
