include ../../Library/Python.mk

Title=		pylibmc
Name=		pylibmc
Version=	1.2.3
Revision=	1
URL=		http://pypi.python.org/packages/source/p/pylibmc/
Source=		$(Name)-$(Version).tar.gz

ReadMeFile=	$(SourceDir)/README.rst
LicenseFile=	$(SourceDir)/LICENSE

define test_inner_hook
$(Python) -c 'import pylibmc'
endef
