AM_CPPFLAGS = \
	-I$(srcdir) \
	-I$(srcdir)/.. \
	-I$(srcdir)/../ctags \
	-DGEANY_PRIVATE \
	-DG_LOG_DOMAIN=\"Tagmanager\"
AM_CFLAGS = \
	$(GTK_CFLAGS) \
	@LIBGEANY_CFLAGS@

EXTRA_DIST = \
	makefile.win32

noinst_LTLIBRARIES = libtagmanager.la

tagmanager_includedir = $(includedir)/geany/tagmanager
tagmanager_include_HEADERS = \
	tm_source_file.h \
	tm_tag.h \
	tm_tagmanager.h \
	tm_workspace.h \
	tm_parser.h


libtagmanager_la_SOURCES =\
	tm_tagmanager.h \
	tm_parser.h \
	tm_source_file.h \
	tm_source_file.c \
	tm_tag.h \
	tm_tag.c \
	tm_workspace.h \
	tm_workspace.c
