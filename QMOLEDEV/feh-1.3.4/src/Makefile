# Makefile.in generated automatically by automake 1.4-p6 from Makefile.am

# Copyright (C) 1994, 1995-8, 1999, 2001 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.

# A list of all the files in the current directory which can be regenerated


SHELL = /bin/sh

srcdir = .
top_srcdir = ..

prefix = /usr/local
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/info
mandir = ${prefix}/man
includedir = ${prefix}/include
oldincludedir = /usr/include

DESTDIR =

pkgdatadir = $(datadir)/feh
pkglibdir = $(libdir)/feh
pkgincludedir = $(includedir)/feh

top_builddir = ..

ACLOCAL = /home/chris/feh-1.3.4/missing aclocal-1.4
AUTOCONF = autoconf
AUTOMAKE = /home/chris/feh-1.3.4/missing automake-1.4
AUTOHEADER = autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = ${INSTALL} $(AM_INSTALL_PROGRAM_FLAGS)
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL}
transform = s,x,x,

NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
host_alias = 
host_triplet = @host@
CC = /usr/bin/gcc
GIBLIB_CFLAGS = -I/usr/local/include -I/usr/local/include/giblib -I/usr/local/include
GIBLIB_LIBS = -L/usr/local/lib -lgiblib -L/usr/local/lib -lImlib2 -L/usr/local/lib -lfreetype -lz -L/usr/X11R6/lib -lX11 -lXext -lm
GTK_CFLAGS = @GTK_CFLAGS@
GTK_CONFIG = @GTK_CONFIG@
GTK_LIBS = @GTK_LIBS@
HAVE_LIB = @HAVE_LIB@
HAVE_XINERAMA = 
IMLIB_CFLAGS = -I/usr/local/include
IMLIB_LIBS = -L/usr/local/lib -lImlib2 -L/usr/local/lib -lfreetype -lz -L/usr/X11R6/lib -lX11 -lXext -lm
LIB = @LIB@
LTLIB = @LTLIB@
MAINT = #
MAKEINFO = makeinfo
PACKAGE = feh
UP = @UP@
VERSION = 1.3.4
XINERAMA_LIBS = 

MAINTAINERCLEANFILES = Makefile.in				

LDFLAGS = -L/usr/X11R6/lib -L/usr/local/lib -lz -lpng
INCLUDES = -I/usr/X11R6/include $(X_CFLAGS)                     -I$(prefix)/include -I$(includedir)                     -I. -I$(top_srcdir)/src                     -I/usr/local/include/libpng                     -DPREFIX=\""$(prefix)"\"                     -I/usr/local/include -I/usr/local/include -I/usr/local/include/giblib -I/usr/local/include

LIBOBJS = 

bin_PROGRAMS = feh
feh_SOURCES = main.c getopt.c getopt1.c getopt.h feh.h options.c options.h winwidget.c winwidget.h menu.c menu.h structs.h filelist.c filelist.h multiwindow.c imlib.c index.c slideshow.c utils.c utils.h keyevents.c timers.c timers.h list.c collage.c debug.h events.c events.h support.c support.h transupp.c transupp.h thumbnail.c thumbnail.h ipc.c ipc.h md5.c md5.h feh_png.c feh_png.h jpegint.h


feh_LDADD = -lX11 -lz -lpng -L/usr/local/lib -lImlib2 -L/usr/local/lib -lfreetype -lz -L/usr/X11R6/lib -lX11 -lXext -lm -L/usr/local/lib -lgiblib -L/usr/local/lib -lImlib2 -L/usr/local/lib -lfreetype -lz -L/usr/X11R6/lib -lX11 -lXext -lm

images_DATA = about.png menubg_default.png menubg_sky.png menubg_chrome.png menubg_brushed.png menubg_pastel.png menubg_aluminium.png menubg_aqua.png menubg_wood.png menubg_britney.png menubg_black.png


imagesdir = $(prefix)/share/feh/images
EXTRA_DIST = $(images_DATA)

SUBDIRS = ttfonts
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = config.h
CONFIG_CLEAN_FILES = 
PROGRAMS =  $(bin_PROGRAMS)


DEFS = -DHAVE_CONFIG_H -I. -I$(srcdir) -I.
CPPFLAGS = 
LIBS = -ljpeg -lXinerama -lXext -L/usr/X11R6/lib  -lm -ljpeg
feh_OBJECTS =  main.o getopt.o getopt1.o options.o winwidget.o menu.o \
filelist.o multiwindow.o imlib.o index.o slideshow.o utils.o \
keyevents.o timers.o list.o collage.o events.o support.o transupp.o \
thumbnail.o ipc.o md5.o feh_png.o
feh_DEPENDENCIES = 
feh_LDFLAGS = 
CFLAGS = -I/usr/X11R6/include -g -O2
COMPILE = $(CC) $(DEFS) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(LDFLAGS) -o $@
DATA =  $(images_DATA)

DIST_COMMON =  ./stamp-h.in Makefile.am Makefile.in config.h.in


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = tar
GZIP_ENV = --best
SOURCES = $(feh_SOURCES)
OBJECTS = $(feh_OBJECTS)

all: all-redirect
.SUFFIXES:
.SUFFIXES: .S .c .o .s
$(srcdir)/Makefile.in: # Makefile.am $(top_srcdir)/configure.ac $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --foreign --include-deps src/Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status
	cd $(top_builddir) \
	  && CONFIG_FILES=$(subdir)/$@ CONFIG_HEADERS= $(SHELL) ./config.status


config.h: stamp-h
	@if test ! -f $@; then \
		rm -f stamp-h; \
		$(MAKE) stamp-h; \
	else :; fi
stamp-h: $(srcdir)/config.h.in $(top_builddir)/config.status
	cd $(top_builddir) \
	  && CONFIG_FILES= CONFIG_HEADERS=src/config.h \
	     $(SHELL) ./config.status
	@echo timestamp > stamp-h 2> /dev/null
$(srcdir)/config.h.in: #$(srcdir)/stamp-h.in
	@if test ! -f $@; then \
		rm -f $(srcdir)/stamp-h.in; \
		$(MAKE) $(srcdir)/stamp-h.in; \
	else :; fi
$(srcdir)/stamp-h.in: $(top_srcdir)/configure.ac $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOHEADER)
	@echo timestamp > $(srcdir)/stamp-h.in 2> /dev/null

mostlyclean-hdr:

clean-hdr:

distclean-hdr:
	-rm -f config.h

maintainer-clean-hdr:

mostlyclean-binPROGRAMS:

clean-binPROGRAMS:
	-test -z "$(bin_PROGRAMS)" || rm -f $(bin_PROGRAMS)

distclean-binPROGRAMS:

maintainer-clean-binPROGRAMS:

install-binPROGRAMS: $(bin_PROGRAMS)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(bindir)
	@list='$(bin_PROGRAMS)'; for p in $$list; do \
	  if test -f $$p; then \
	    echo "  $(INSTALL_PROGRAM) $$p $(DESTDIR)$(bindir)/`echo $$p|sed 's/$(EXEEXT)$$//'|sed '$(transform)'|sed 's/$$/$(EXEEXT)/'`"; \
	     $(INSTALL_PROGRAM) $$p $(DESTDIR)$(bindir)/`echo $$p|sed 's/$(EXEEXT)$$//'|sed '$(transform)'|sed 's/$$/$(EXEEXT)/'`; \
	  else :; fi; \
	done

uninstall-binPROGRAMS:
	@$(NORMAL_UNINSTALL)
	list='$(bin_PROGRAMS)'; for p in $$list; do \
	  rm -f $(DESTDIR)$(bindir)/`echo $$p|sed 's/$(EXEEXT)$$//'|sed '$(transform)'|sed 's/$$/$(EXEEXT)/'`; \
	done

.c.o:
	$(COMPILE) -c $<

.s.o:
	$(COMPILE) -c $<

.S.o:
	$(COMPILE) -c $<

mostlyclean-compile:
	-rm -f *.o core *.core

clean-compile:

distclean-compile:
	-rm -f *.tab.c

maintainer-clean-compile:

feh: $(feh_OBJECTS) $(feh_DEPENDENCIES)
	@rm -f feh
	$(LINK) $(feh_LDFLAGS) $(feh_OBJECTS) $(feh_LDADD) $(LIBS)

install-imagesDATA: $(images_DATA)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(imagesdir)
	@list='$(images_DATA)'; for p in $$list; do \
	  if test -f $(srcdir)/$$p; then \
	    echo " $(INSTALL_DATA) $(srcdir)/$$p $(DESTDIR)$(imagesdir)/$$p"; \
	    $(INSTALL_DATA) $(srcdir)/$$p $(DESTDIR)$(imagesdir)/$$p; \
	  else if test -f $$p; then \
	    echo " $(INSTALL_DATA) $$p $(DESTDIR)$(imagesdir)/$$p"; \
	    $(INSTALL_DATA) $$p $(DESTDIR)$(imagesdir)/$$p; \
	  fi; fi; \
	done

uninstall-imagesDATA:
	@$(NORMAL_UNINSTALL)
	list='$(images_DATA)'; for p in $$list; do \
	  rm -f $(DESTDIR)$(imagesdir)/$$p; \
	done

# This directory's subdirectories are mostly independent; you can cd
# into them and run `make' without going through this Makefile.
# To change the values of `make' variables: instead of editing Makefiles,
# (1) if the variable is set in `config.status', edit `config.status'
#     (which will cause the Makefiles to be regenerated when you run `make');
# (2) otherwise, pass the desired values on the `make' command line.



all-recursive install-data-recursive install-exec-recursive \
installdirs-recursive install-recursive uninstall-recursive  \
check-recursive installcheck-recursive info-recursive dvi-recursive:
	@set fnord $(MAKEFLAGS); amf=$$2; \
	dot_seen=no; \
	target=`echo $@ | sed s/-recursive//`; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    dot_seen=yes; \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	   || case "$$amf" in *=*) exit 1;; *k*) fail=yes;; *) exit 1;; esac; \
	done; \
	if test "$$dot_seen" = "no"; then \
	  $(MAKE) $(AM_MAKEFLAGS) "$$target-am" || exit 1; \
	fi; test -z "$$fail"

mostlyclean-recursive clean-recursive distclean-recursive \
maintainer-clean-recursive:
	@set fnord $(MAKEFLAGS); amf=$$2; \
	dot_seen=no; \
	rev=''; list='$(SUBDIRS)'; for subdir in $$list; do \
	  rev="$$subdir $$rev"; \
	  test "$$subdir" != "." || dot_seen=yes; \
	done; \
	test "$$dot_seen" = "no" && rev=". $$rev"; \
	target=`echo $@ | sed s/-recursive//`; \
	for subdir in $$rev; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	   || case "$$amf" in *=*) exit 1;; *k*) fail=yes;; *) exit 1;; esac; \
	done && test -z "$$fail"
tags-recursive:
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  test "$$subdir" = . || (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) tags); \
	done

tags: TAGS

ID: $(HEADERS) $(SOURCES) $(LISP)
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	here=`pwd` && cd $(srcdir) \
	  && mkid -f$$here/ID $$unique $(LISP)

TAGS: tags-recursive $(HEADERS) $(SOURCES) config.h.in $(TAGS_DEPENDENCIES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
   if test "$$subdir" = .; then :; else \
	    test -f $$subdir/TAGS && tags="$$tags -i $$here/$$subdir/TAGS"; \
   fi; \
	done; \
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	test -z "$(ETAGS_ARGS)config.h.in$$unique$(LISP)$$tags" \
	  || (cd $(srcdir) && etags -o $$here/TAGS $(ETAGS_ARGS) $$tags config.h.in $$unique $(LISP))

mostlyclean-tags:

clean-tags:

distclean-tags:
	-rm -f TAGS ID

maintainer-clean-tags:

distdir = $(top_builddir)/$(PACKAGE)-$(VERSION)/$(subdir)

subdir = src

distdir: $(DISTFILES)
	@for file in $(DISTFILES); do \
	  d=$(srcdir); \
	  if test -d $$d/$$file; then \
	    cp -pr $$d/$$file $(distdir)/$$file; \
	  else \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file || :; \
	  fi; \
	done
	for subdir in $(SUBDIRS); do \
	  if test "$$subdir" = .; then :; else \
	    test -d $(distdir)/$$subdir \
	    || mkdir $(distdir)/$$subdir \
	    || exit 1; \
	    chmod 777 $(distdir)/$$subdir; \
	    (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) top_distdir=../$(top_distdir) distdir=../$(distdir)/$$subdir distdir) \
	      || exit 1; \
	  fi; \
	done
collage.o: collage.c feh.h config.h getopt.h structs.h menu.h ipc.h \
	utils.h debug.h winwidget.h filelist.h options.h
events.o: events.c feh.h config.h getopt.h structs.h menu.h ipc.h \
	utils.h debug.h filelist.h winwidget.h timers.h options.h \
	events.h thumbnail.h
feh_png.o: feh_png.c feh_png.h feh.h config.h getopt.h structs.h menu.h \
	ipc.h utils.h debug.h
filelist.o: filelist.c feh.h config.h getopt.h structs.h menu.h ipc.h \
	utils.h debug.h filelist.h options.h
getopt.o: getopt.c config.h
getopt1.o: getopt1.c config.h getopt.h
imlib.o: imlib.c feh.h config.h getopt.h structs.h menu.h ipc.h utils.h \
	debug.h filelist.h winwidget.h options.h transupp.h
index.o: index.c feh.h config.h getopt.h structs.h menu.h ipc.h utils.h \
	debug.h filelist.h winwidget.h options.h
ipc.o: ipc.c feh.h config.h getopt.h structs.h menu.h ipc.h utils.h \
	debug.h options.h
keyevents.o: keyevents.c feh.h config.h getopt.h structs.h menu.h ipc.h \
	utils.h debug.h thumbnail.h filelist.h winwidget.h options.h
list.o: list.c feh.h config.h getopt.h structs.h menu.h ipc.h utils.h \
	debug.h filelist.h options.h
main.o: main.c feh.h config.h getopt.h structs.h menu.h ipc.h utils.h \
	debug.h filelist.h winwidget.h timers.h options.h events.h \
	support.h
md5.o: md5.c md5.h
menu.o: menu.c feh.h config.h getopt.h structs.h menu.h ipc.h utils.h \
	debug.h support.h thumbnail.h filelist.h winwidget.h options.h
multiwindow.o: multiwindow.c feh.h config.h getopt.h structs.h menu.h \
	ipc.h utils.h debug.h winwidget.h timers.h filelist.h options.h
options.o: options.c feh.h config.h getopt.h structs.h menu.h ipc.h \
	utils.h debug.h filelist.h options.h
slideshow.o: slideshow.c feh.h config.h getopt.h structs.h menu.h ipc.h \
	utils.h debug.h filelist.h timers.h winwidget.h options.h
support.o: support.c feh.h config.h getopt.h structs.h menu.h ipc.h \
	utils.h debug.h filelist.h options.h support.h
thumbnail.o: thumbnail.c feh.h config.h getopt.h structs.h menu.h ipc.h \
	utils.h debug.h filelist.h winwidget.h options.h thumbnail.h \
	md5.h feh_png.h
timers.o: timers.c feh.h config.h getopt.h structs.h menu.h ipc.h \
	utils.h debug.h options.h timers.h
transupp.o: transupp.c transupp.h
utils.o: utils.c feh.h config.h getopt.h structs.h menu.h ipc.h utils.h \
	debug.h options.h
winwidget.o: winwidget.c feh.h config.h getopt.h structs.h menu.h ipc.h \
	utils.h debug.h filelist.h winwidget.h options.h

info-am:
info: info-recursive
dvi-am:
dvi: dvi-recursive
check-am: all-am
check: check-recursive
installcheck-am:
installcheck: installcheck-recursive
all-recursive-am: config.h
	$(MAKE) $(AM_MAKEFLAGS) all-recursive

install-exec-am: install-binPROGRAMS
install-exec: install-exec-recursive

install-data-am: install-imagesDATA
install-data: install-data-recursive

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-recursive
uninstall-am: uninstall-binPROGRAMS uninstall-imagesDATA
uninstall: uninstall-recursive
all-am: Makefile $(PROGRAMS) $(DATA) config.h
all-redirect: all-recursive-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs: installdirs-recursive
installdirs-am:
	$(mkinstalldirs)  $(DESTDIR)$(bindir) $(DESTDIR)$(imagesdir)


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
	-test -z "$(MAINTAINERCLEANFILES)" || rm -f $(MAINTAINERCLEANFILES)
mostlyclean-am:  mostlyclean-hdr mostlyclean-binPROGRAMS \
		mostlyclean-compile mostlyclean-tags \
		mostlyclean-generic

mostlyclean: mostlyclean-recursive

clean-am:  clean-hdr clean-binPROGRAMS clean-compile clean-tags \
		clean-generic mostlyclean-am

clean: clean-recursive

distclean-am:  distclean-hdr distclean-binPROGRAMS distclean-compile \
		distclean-tags distclean-generic clean-am

distclean: distclean-recursive

maintainer-clean-am:  maintainer-clean-hdr maintainer-clean-binPROGRAMS \
		maintainer-clean-compile maintainer-clean-tags \
		maintainer-clean-generic distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-recursive

.PHONY: mostlyclean-hdr distclean-hdr clean-hdr maintainer-clean-hdr \
mostlyclean-binPROGRAMS distclean-binPROGRAMS clean-binPROGRAMS \
maintainer-clean-binPROGRAMS uninstall-binPROGRAMS install-binPROGRAMS \
mostlyclean-compile distclean-compile clean-compile \
maintainer-clean-compile uninstall-imagesDATA install-imagesDATA \
install-data-recursive uninstall-data-recursive install-exec-recursive \
uninstall-exec-recursive installdirs-recursive uninstalldirs-recursive \
all-recursive check-recursive installcheck-recursive info-recursive \
dvi-recursive mostlyclean-recursive distclean-recursive clean-recursive \
maintainer-clean-recursive tags tags-recursive mostlyclean-tags \
distclean-tags clean-tags maintainer-clean-tags distdir info-am info \
dvi-am dvi check check-am installcheck-am installcheck all-recursive-am \
install-exec-am install-exec install-data-am install-data install-am \
install uninstall-am uninstall all-redirect all-am all installdirs-am \
installdirs mostlyclean-generic distclean-generic clean-generic \
maintainer-clean-generic clean mostlyclean distclean maintainer-clean


test:
	@for i in test[0-9]* ; do \
	  if test -x $$i ; then \
	    echo "Executing test script $$i..." ; \
	    ./$$i ; \
	  fi ; \
	done

testclean:
	-rm -f _test*.jpg

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
