# $Id$

SUBDIRS = include lib/cqdb lib/crf frontend tests swig

docdir = $(prefix)/share/doc/@PACKAGE@
doc_DATA = README.md INSTALL COPYING AUTHORS ChangeLog

EXTRA_DIST = \
	crfsuite.sln \
	autogen.sh \
	tap-driver.sh \
	win32/stdint.h \
	example/crfutils.py \
	example/template.py \
	example/pos.py \
	example/ner.py \
	example/chunking.py

AUTOMAKE_OPTIONS = foreign
ACLOCAL_AMFLAGS = -I m4

