# $FreeBSD$

PORTNAME=	collada-dom
DISTVERSION=	2.5.0
CATEGORIES=	devel

MAINTAINER=	trueos@norwegianrockcat.com
COMMENT=	COLLADA Document Object Model (DOM) C++ Library

LICENSE=	MIT

LIB_DEPENDS+=	libminizip.so:archivers/minizip \
		libpcre.so:devel/pcre \
		libboost_filesystem.so:devel/boost-libs \
		libboost_system.so:devel/boost-libs

USES=	cmake gnome
USE_LDCONFIG=	yes

USE_GNOME+=	libxml2

USE_GITHUB=	yes
GH_ACCOUNT=	rdiankov
GH_PROJECT=	collada-dom
GH_TAGNAME=	v${DISTVERSIONPREFIX}${DISTVERSION}${DISTVERSIONSUFFIX}

.include <bsd.port.mk>
