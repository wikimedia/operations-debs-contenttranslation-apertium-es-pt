#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.


AC_PREREQ(2.52)

AC_INIT([apertium-es-pt], [1.1.5], [sortiz@users.sourceforge.net])
AM_INIT_AUTOMAKE([apertium-es-pt], [1.1.5], no-define)
AC_PROG_LN_S
AC_PROG_AWK
AC_CONFIG_HEADER([config])

m4_define([required_apertium_version], [3.2.0])
PKG_CHECK_MODULES(APERTIUM,   apertium >= required_apertium_version, [], [PKG_CHECK_MODULES(APERTIUM,   apertium-3.2 >= required_apertium_version)])
                          

AC_SUBST(APERTIUM_VER)

AC_OUTPUT([Makefile])

