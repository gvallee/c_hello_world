# -*- shell-script -*-
#
# Copyright 2021. NVIDIA CORPORATION. All rights reserved.
# See COPYING in top-level directory.
#
# Additional copyrights may follow
#
# $HEADER$
#

AC_INIT([c_hello_world], [1.0.1], [geoffroy.vallee@gmail.com])
AM_INIT_AUTOMAKE([dist-bzip2 subdir-objects foreign tar-ustar])
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

AC_CONFIG_MACRO_DIR([m4])

# Checks for programs
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_MKDIR_P

# Checks for header files.
AC_CHECK_HEADERS([stdlib.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_C_INLINE
AC_TYPE_SIZE_T
AC_TYPE_SSIZE_T


AM_PROG_CC_C_O
m4_pattern_allow([AM_PROG_AR], [AM_PROG_AR])
AC_ENABLE_SHARED
AC_DISABLE_STATIC
LT_INIT

# Generate Makefiles
AC_CONFIG_FILES([Makefile src/Makefile])
AC_OUTPUT
