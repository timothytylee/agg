
if ENABLE_FT
aggincludedir = $(includedir)/agg2
agginclude_HEADERS = agg_font_freetype.h
lib_LTLIBRARIES = libaggfontfreetype.la

libaggfontfreetype_la_LDFLAGS = -version-info @AGG_LIB_VERSION@
libaggfontfreetype_la_SOURCES = agg_font_freetype.cpp
libaggfontfreetype_la_CXXFLAGS = -I$(top_srcdir)/include @FREETYPE_CFLAGS@ 
libaggfontfreetype_la_LIBADD = ../src/libagg.la @FREETYPE_LIBS@
endif

