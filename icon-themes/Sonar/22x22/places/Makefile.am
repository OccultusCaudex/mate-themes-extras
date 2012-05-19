themedir = $(datadir)/icons/Sonar/22x22/places
theme_DATA =   folder-documents.png folder-download.png folder-music.png folder-pictures.png folder.png folder-publicshare.png folder-remote.png folder-saved-search.png folder-templates.png folder-videos.png network-workgroup.png start-here.png user-desktop.png user-home.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c places )
MAINTAINERCLEANFILES = Makefile.in
