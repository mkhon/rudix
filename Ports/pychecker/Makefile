include ../../Library/Python.mk

Title=		PyChecker
Name=		pychecker
Version=	0.8.19
Revision=	3
URL=		http://sourceforge.net/projects/pychecker/files/pychecker/$(Version)/
Source=		$(Name)-$(Version).tar.gz

LicenseFile=	$(SourceDir)/COPYRIGHT

define test_inner_hook
$(BinDir)/pychecker --version
endef
