m4_define([api_version],[1])

AC_INIT([libfoo], 0.1)

AM_INIT_AUTOMAKE([foreign])

AM_SILENT_RULES([yes])

AC_PROG_CC

LT_INIT

AC_SUBST([API_VERSION],api_version)

AC_CONFIG_FILES([
Makefile foo-$API_VERSION.pc:foo.pc.in
],[],
[API_VERSION='$API_VERSION'])

AC_OUTPUT
