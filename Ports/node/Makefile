include ../../Library/Configure.mk

Title=		NodeJS
Name=		node
Version=	0.8.22
Revision=	0
URL=		http://nodejs.org/dist/v$(Version)
Source=		$(Name)-v$(Version).tar.gz

ReadMeFile=	$(SourceDir)/README.md
LicenseFile=	$(SourceDir)/LICENSE

UncompressedName=$(Name)-v$(Version)

EnvExtra += OPENSSL_CFLAGS=-I/usr/include OPENSSL_LIBS=-lcrypto

define test_inner_hook
$(BinDir)/node --version
$(BinDir)/npm --version
endef
