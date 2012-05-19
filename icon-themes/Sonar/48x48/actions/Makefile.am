themedir = $(datadir)/icons/Sonar/48x48/actions
theme_DATA =   document-open.png folder-new.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c actions )
MAINTAINERCLEANFILES = Makefile.in
