AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic
include_HEADERS = main.h

lib_LTLIBRARIES = libexample.la
libexample_la_SOURCES  = examplelib.c
libexample_la_LDFLAGS= -version-info 1:0:0

bin_PROGRAMS = main
main_SOURCES = main.c
main_LDADD = .libs/libexample.la
main_DEPENDENCIES = libexample.la
