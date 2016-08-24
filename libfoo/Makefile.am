AUTOMAKE_OPTIONS = subdir-objects

lib_LTLIBRARIES = libfoo-@API_VERSION@.la

libfoo_@API_VERSION@_la_SOURCES = src/libfoo.c

libfoo_includedir = $(includedir)/libfoo-@API_VERSION@
libfoo_include_HEADERS = src/libfoo.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = foo-@API_VERSION@.pc

DISTCLEANFILES = $(pkgconfig_DATA)
EXTRA_DIST = foo.pc.in

