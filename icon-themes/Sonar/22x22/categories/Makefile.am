themedir = $(datadir)/icons/Sonar/22x22/categories
theme_DATA =   preferences-system-network.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c categories )
MAINTAINERCLEANFILES = Makefile.in
