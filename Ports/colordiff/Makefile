include ../../Library/Unix.mk

Title=		ColorDiff
Name=		colordiff
Version=	1.0.13
Revision=	1
URL=		http://www.colordiff.org
Source=		$(Name)-$(Version).tar.gz

define prep_post_hook
cd $(BuildDir) ; mv INSTALL _INSTALL
endef

define build_inner_hook
endef

define test_inner_hook
endef

define install_post_hook
mv $(InstallDir)/usr/local/etc/colordiffrc \
	$(InstallDir)/usr/local/etc/colordiffrc.default
endef

define test_inner_hook
$(BinDir)/colordiff -u $(BuildDir)/colordiff.pl $(BinDir)/colordiff || true
endef
