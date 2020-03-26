AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic
include_HEADERS = main.h

lib_LTLIBRARIES = libexample.la
libbbexample_la_SOURCES  = examplelib.c
libbbexample_la_LDFLAGS= -version-info 1:0:0

bin_PROGRAMS = main
bbexample_SOURCES = main.c
bbexample_LDADD = .libs/libexample.la
bbexample_DEPENDENCIES = libexample.la
