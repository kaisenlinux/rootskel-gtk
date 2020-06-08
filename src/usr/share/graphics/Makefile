dir = usr/share/graphics

files = \
	kaisen.png \
	note_icon.png \
	warning_icon.png

build-local:: $(files)

install-local:: $(outdir)
	ln -fs kaisen.png $(outdir)/logo_installer.png

include ../../../../Makefile.inc
