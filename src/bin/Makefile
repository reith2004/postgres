#-------------------------------------------------------------------------
#
# Makefile for src/bin (client programs)
#
# Portions Copyright (c) 1996-2010, PostgreSQL Global Development Group
# Portions Copyright (c) 1994, Regents of the University of California
#
# src/bin/Makefile
#
#-------------------------------------------------------------------------

subdir = src/bin
top_builddir = ../..
include $(top_builddir)/src/Makefile.global

SUBDIRS = initdb pg_ctl pg_dump \
	psql scripts pg_config pg_controldata pg_resetxlog
ifeq ($(PORTNAME), win32)
SUBDIRS+=pgevent
endif

$(recurse)
