## Process this file with automake to produce Makefile.in

inc_local = -I$(top_srcdir)/include -I$(top_srcdir)/src/api/c
c_api = $(top_builddir)/src/api/c

bin_PROGRAMS = spd-say
spd_say_CPPFLAGS = $(inc_local) $(GLIB_CFLAGS)
spd_say_SOURCES = say.c options.c options.h
spd_say_LDADD = $(c_api)/libspeechd.la $(EXTRA_SOCKET_LIBS) $(top_builddir)/src/common/libcommon.la

-include $(top_srcdir)/git.mk
