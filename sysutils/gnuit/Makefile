# $OpenBSD$

COMMENT =	GNU interactive tools
DISTNAME =	gnuit-4.9.5
CATEGORIES =	sysutils

HOMEPAGE =	https://www.gnu.org/software/gnuit/
MAINTAINER =	Brian Callahan <bcallah@openbsd.org>

# GPLv3+
PERMIT_PACKAGE_CDROM =	Yes

WANTLIB += c curses

MASTER_SITES =	${MASTER_SITE_GNU:=gnuit/}

BUILD_DEPENDS =	textproc/texi2html

CONFIGURE_STYLE =	gnu
CONFIGURE_ARGS =	--disable-transition

.include <bsd.port.mk>
