themedir = $(datadir)/icons/Sonar/256x256/places
theme_DATA =   folder-documents.png folder-download.png folder-music.png folder-pictures.png folder.png folder-publicshare.png folder-remote.png folder-saved-search.png folder-templates.png folder-videos.png network-workgroup.png user-desktop.png user-home.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c places )
MAINTAINERCLEANFILES = Makefile.in
