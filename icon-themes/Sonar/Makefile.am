THEME_NAME=Sonar
 
themedir = $(datadir)/icons/$(THEME_NAME)

theme_DATA = index.theme

gtk_update_icon_cache = gtk-update-icon-cache -f -t "$(themedir)"

install-data-hook:
		@if test -z "$(DESTDIR)"; then \
                        echo "Updating Gtk icon cache."; \
                        $(gtk_update_icon_cache); \
                else \
                        echo "*** Icon cache not updated.       After install, run this:"; \
                        echo "***        $(gtk_update_icon_cache)"; \
                fi


EXTRA_DIST=                             \
        index.theme

SUBDIRS = \
	16x16 \
	22x22 \
	24x24 \
	32x32 \
	48x48 \
	256x256

DIST_SUBDIRS = \
	16x16 \
	22x22 \
	24x24 \
	32x32 \
	48x48 \
	256x256

MAINTAINERCLEANFILES = \
	Makefile.in
