AC_INIT([dummRprojy], [1.0])

# Ensure R_HOME is defined
: ${R_HOME=`R RHOME`}
AC_MSG_NOTICE([Using R_HOME=$R_HOME])

# Run R to verify it works
AC_MSG_NOTICE([Running ${R_HOME}/bin/R --version])
${R_HOME}/bin/R --version || AC_MSG_ERROR([R did not run successfully])
${R_HOME}/bin/R CMD INSTALL --no-staged-install r


AC_OUTPUT