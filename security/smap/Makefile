# Created by: Edwin Groothuis <edwin@mavetju.org>
# $FreeBSD$

PORTNAME=	smap
PORTVERSION=	0.5.0
PORTREVISION=	2
CATEGORIES=	security net
MASTER_SITES=	http://www.wormulon.net/smap/

MAINTAINER=	ports@FreeBSD.org
COMMENT=	SIP scanner and identifier

# does not really specify # of clauses, so stay
# with strictest variant to be on a safe side
LICENSE=	BSD4CLAUSE

BROKEN=		unfetchable
DEPRECATED=	Unfetchable, unmaintained
EXPIRATION_DATE=	2019-10-16

USES=		gmake

do-install:
	${INSTALL_PROGRAM} ${WRKSRC}/smap ${STAGEDIR}${PREFIX}/bin
	@${MKDIR} ${STAGEDIR}${DATADIR}
	${INSTALL_DATA} ${WRKSRC}/fingerprint.db ${STAGEDIR}${DATADIR}

.include <bsd.port.mk>
