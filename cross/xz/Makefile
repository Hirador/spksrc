PKG_NAME = xz
PKG_VERS = 5.6.1+really5.4.5
PKG_EXT = tar.xz
PKG_DIST_NAME = $(PKG_NAME)-utils_$(PKG_VERS).orig.$(PKG_EXT)
PKG_DIST_FILE = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://deb.debian.org/debian/pool/main/x/xz-utils/
PKG_DIR = $(PKG_NAME)-5.4.5

DEPENDS =

HOMEPAGE = https://tukaani.org
COMMENT  = Free general-purpose data compression software with high compression ratio.
LICENSE  = various

GNU_CONFIGURE = 1
CONFIGURE_ARGS  = --disable-static
CONFIGURE_ARGS += --disable-scripts
CONFIGURE_ARGS += --disable-doc
ADDITIONAL_CFLAGS = -O

include ../../mk/spksrc.cross-cc.mk
