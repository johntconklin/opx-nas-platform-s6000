ACLOCAL_AMFLAGS=-I m4

lib_LTLIBRARIES=libopx_nas_platform.la

libopx_nas_platform_la_SOURCES=src/nas_ndi_plat_stat.c

libopx_nas_platform_la_CPPFLAGS= -D_FILE_OFFSET_BITS=64 -I$(includedir)/opx

libopx_nas_platform_la_CXXFLAGS=-std=c++11

libopx_nas_platform_la_LDFLAGS=-shared -version-info 1:1:0

libopx_nas_platform_la_LIBADD= -lopx_common -lopx_cps_api_common -lopx_logging
