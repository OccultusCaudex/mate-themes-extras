themedir = $(datadir)/icons/Sonar/256x256/status
theme_DATA =   folder-drag-accept.png folder-open.png folder-visiting.png network-error.png network-idle.png network-offline.png network-receive.png network-transmit.png network-transmit-receive.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c status )
MAINTAINERCLEANFILES = Makefile.in
