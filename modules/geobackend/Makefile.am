AM_CPPFLAGS=@THREADFLAGS@ $(BOOST_CPPFLAGS)
EXTRA_DIST=OBJECTFILES OBJECTLIBS
lib_LTLIBRARIES = libgeobackend.la
libgeobackend_la_SOURCES=geobackend.cc geobackend.hh ippreftree.cc ippreftree.hh
libgeobackend_la_CXXFLAGS=-I$(abs_top_srcdir)
libgeobackend_la_LDFLAGS=-module -avoid-version
