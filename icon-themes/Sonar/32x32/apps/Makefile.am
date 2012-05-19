themedir = $(datadir)/icons/Sonar/32x32/apps
theme_DATA =   gnome-device-manager.png gnome-power-manager.png notification-properties.png ooo-base.png ooo-calc.png ooo-draw.png ooo-gulls.png ooo-impress.png ooo-web.png ooo-writer.png system-shutdown.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c apps )
MAINTAINERCLEANFILES = Makefile.in
