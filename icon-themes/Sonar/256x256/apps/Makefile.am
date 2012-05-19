themedir = $(datadir)/icons/Sonar/256x256/apps
theme_DATA =   notification-properties.png ooo-base.png ooo-calc.png ooo-draw.png ooo-gulls.png ooo-impress.png ooo-web.png ooo-writer.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c apps )
MAINTAINERCLEANFILES = Makefile.in
