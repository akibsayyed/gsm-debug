INCLUDES = $(all_includes) -I$(top_srcdir)/include
noinst_PROGRAMS = smscb_test
EXTRA_DIST = smscb_test.ok

smscb_test_SOURCES = smscb_test.c
smscb_test_LDADD = $(top_builddir)/src/libosmocore.la $(top_builddir)/src/gsm/libosmogsm.la
