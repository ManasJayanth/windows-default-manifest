dnl Autoconf configure script for cygrunsrv.

AC_PREREQ(2.60)dnl
AC_INIT(default-manifest.rc)

AC_CANONICAL_SYSTEM

AC_PROG_INSTALL

case "${target}" in
  *-cygwin)
  	;;
  *-mingw*)
  	;;
  *)
  	echo "The only supported targets are Cygwin and MingW."
	exit 1
	;;
esac

AC_CHECK_TOOL(WINDRES, windres)

AC_OUTPUT(Makefile)
