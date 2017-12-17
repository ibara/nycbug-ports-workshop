# $OpenBSD$

COMMENT =	ncurses git history browser
MODPY_EGG_VERSION =	0.5.9
DISTNAME =	bblame-${MODPY_EGG_VERSION}
PKGNAME =	py-${DISTNAME}
CATEGORIES =	sysutils

MAINTAINER =	Brian Callahan <bcallah@openbsd.org>

# MIT
PERMIT_PACKAGE_CDROM =	Yes

FLAVORS =	python3
FLAVOR ?=

MODULES =	lang/python
MODPY_SETUPTOOLS =	Yes
MODPY_PI =	Yes

# Does not actually have the entirety of the test framework.
# Errors out because of this.
NO_TEST =	Yes

post-install:
	@mv ${PREFIX}/bin/bblame ${PREFIX}/bin/bblame${MODPY_BIN_SUFFIX}

.include <bsd.port.mk>
