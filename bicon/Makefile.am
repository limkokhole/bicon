bin_PROGRAMS = bicon.bin

bicon_bin_SOURCES = \
		bicon.c \
		bicon_read.c \
		bicon_read.h \
		pty_spawn.c \
		pty_spawn.h

bicon_bin_CPPFLAGS = \
		$(FRIBIDI_CFLAGS) \
		-I$(top_srcdir)/bjoining \
		-I$(top_srcdir)/bconsole

bicon_bin_LDADD = \
		$(FRIBIDI_LIBS) \
		$(top_builddir)/bconsole/libbconsole.la \
		$(top_builddir)/bjoining/libbjoining.la

#lib_LTLIBRARIES = libbicon.la
#
#libbicon_la_SOURCES = bicon_so.c
#libbicon_la_LIBADD = 

-include $(top_srcdir)/git.mk
