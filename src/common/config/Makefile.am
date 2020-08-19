noinst_LTLIBRARIES = libconfig.la

libconfig_la_SOURCES = ini.c ini.h session-config.c session-config.h \
		config-session-abi.h config-internal.h
libconfig_la_CPPFLAGS = $(libxml2_CFLAGS) $(AM_CPPFLAGS)
libconfig_la_LIBADD = ${libxml2_LIBS}
