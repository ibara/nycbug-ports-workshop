# $OpenBSD$

V =		1.07.1
COMMENT =	arbitrary precision calculator from the GNU project
DISTNAME =	bc-${V}
PKGNAME =	gbc-${V}
CATEGORIES =	math

HOMEPAGE =	https://www.gnu.org/software/bc/
MAINTAINER =	Brian Callahan <bcallah@openbsd.org>

# GPLv3+
PERMIT_PACKAGE_CDROM =	Yes

WANTLIB += c curses edit

MASTER_SITES =	${MASTER_SITE_GNU:=bc/}

CONFIGURE_STYLE =	gnu
CONFIGURE_ARGS =	--program-prefix=g \
			--with-libedit

.include <bsd.port.mk>
