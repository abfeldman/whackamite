AC_PREREQ([2.63])
AC_INIT([whackamite],[0.1],[alexander.feldman@nspyre.nl])
AC_CONFIG_SRCDIR([src/main.cpp])
AC_CONFIG_HEADERS([include/config.h])
AC_CONFIG_AUX_DIR(auxdir)
AC_CONFIG_MACRO_DIR([m4])

AM_SILENT_RULES([yes])

# Checks for programs.
AC_PROG_CC
AC_PROG_CXX
AC_PROG_INSTALL
LT_INIT

AM_INIT_AUTOMAKE([-Wall silent-rules])

# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

# Checks for dependencies.

AX_OPENCV
if test $ac_cv_have_opencv = no ; then
  AC_MSG_ERROR([OpenCV is required to build Whack-A-Mite.])
fi


AC_CONFIG_FILES([Makefile
                 src/Makefile])
AC_OUTPUT
