if ENABLE_X11
lib_LTLIBRARIES = libaggplatformX11.la

libaggplatformX11_la_LDFLAGS = -version-info @AGG_LIB_VERSION@ @X_LDFLAGS@
libaggplatformX11_la_SOURCES = agg_platform_support.cpp
libaggplatformX11_la_CXXFLAGS =  -I$(top_srcdir)/include -I@x_includes@
libaggplatformX11_la_LIBADD = ../../libagg.la -lX11
endif
