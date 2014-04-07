dnl Autoconf configure script for cygrunsrv.

AC_PREREQ(2.60)dnl
AC_INIT(default-manifest.rc)

AC_CANONICAL_HOST

AC_PROG_INSTALL

case "${host}" in
  *-cygwin)
  	;;
  *-mingw*)
  	;;
  *)
  	echo "The only supported hosts are Cygwin and MingW."
	exit 1
	;;
esac

AC_CHECK_TOOL(WINDRES, windres)

AC_OUTPUT(Makefile)
