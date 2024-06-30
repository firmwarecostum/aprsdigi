# automake Makefile.am for Laprs (linux APRS(tm)) package
# APRS is a registered trademark of Bob Bruninga, WB4APR
SUFFIXES = .fig .html .8 .pdf
noinst_LIBRARIES = libaprs.a
sbin_PROGRAMS = aprsmon aprsdigi
noinst_PROGRAMS = mic_e_test testparse testmcast fiforead fifowrite
aprsmon_SOURCES = aprsmon.c aprsshm.c aprsshm.h
LDADD = libaprs.a
aprsdigi_SOURCES = aprsdigi.c
mic_e_test_SOURCES = mic_e_test.c
testparse_SOURCES = testparse.c
testmcast_SOURCES = testmcast.c
fiforead_SOURCES = fiforead.c
fifowrite_SOURCES = fifowrite.c
libaprs_a_SOURCES = mic_e.c mic_e.h libax25ext.c libax25ext.h



