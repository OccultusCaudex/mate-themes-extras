themedir = $(datadir)/icons/Sonar/32x32/status
theme_DATA =   audio-volume-high.png audio-volume-low.png audio-volume-medium.png audio-volume-muted.png dialog-password.png folder-drag-accept.png folder-open.png folder-visiting.png network-error.png network-idle.png network-offline.png network-receive.png network-transmit.png network-transmit-receive.png nm-signal-00.png nm-signal-100.png nm-signal-25.png nm-signal-50.png nm-signal-75.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c status )
MAINTAINERCLEANFILES = Makefile.in
