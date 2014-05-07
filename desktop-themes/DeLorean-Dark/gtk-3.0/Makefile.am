THEME_NAME=DeLorean-Dark
 
themedir = $(datadir)/themes/$(THEME_NAME)/gtk-3.0

theme_DATA = \
	gnome-applications.css \
	gtk.css \
	gtk-fallback.css \
	gtk-main-common.css \
	gtk-main.css \
	gtk-widgets-assets.css \
	gtk-widgets-backgrounds.css \
	gtk-widgets-borders.css \
	gtk-widgets.css \
	overlay-scrollbar.css \
	settings.ini

EXTRA_DIST = $(theme_DATA)

SUBDIRS =	\
	apps	\
	assets	\
	borders

DIST_SUBDIRS =	\
	apps	\
	assets	\
	borders

CLEANFILES = index.theme
