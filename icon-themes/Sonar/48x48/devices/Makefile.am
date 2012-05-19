themedir = $(datadir)/icons/Sonar/48x48/devices
theme_DATA =   computer.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c devices )
MAINTAINERCLEANFILES = Makefile.in
