#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([opx-nas-platform-s6000],[1.0.1],[ops-dev@lists.openswitch.net])
AM_INIT_AUTOMAKE([foreign subdir-objects])
AC_CONFIG_SRCDIR([src])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIRS([m4])

# Checks for programs.
AC_PROG_CXX
AC_PROG_AWK
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET
AC_PROG_RANLIB

LT_INIT([shared])

# Checks for libraries.
# FIXME: Replace `main' with a function in `-lopx_common':
AC_CHECK_LIB([opx_common], [main])
# FIXME: Replace `main' with a function in `-lopx_cps_class_map':
AC_CHECK_LIB([opx_cps_class_map], [main])
# FIXME: Replace `main' with a function in `-lopx_logging':
AC_CHECK_LIB([opx_logging], [main])
# FIXME: Replace `main' with a function in `-lopx_cps':
AC_CHECK_LIB([opx_cps], [main])

# Checks for header files.
AC_CHECK_HEADERS([string.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_SIZE_T
AC_TYPE_UINT64_T

# Checks for library functions.

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
