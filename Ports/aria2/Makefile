include ../../Library/GNU.mk

Title=		aria2
Name=		aria2
Version=	1.16.5
Revision=	0
URL=		http://downloads.sourceforge.net/aria2
Source=		$(Name)-$(Version).tar.bz2

GnuConfigureExtra += --with-included-gettext

define test_inner_hook
$(BinDir)/aria2c --version
$(BinDir)/aria2c http://rudix.googlecode.com/hg/Ports/rudix/rudix.py
rm -f rudix.py
endef
