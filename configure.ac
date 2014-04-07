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

case "${host_cpu}" in
  i?86)
	RC_FLAGS="-F pe-i386"
	;;
  x86_64)
	RC_FLAGS="-F pe-x86-64"
	;;
esac

AC_SUBST(RC_FLAGS)

AC_OUTPUT(Makefile)
