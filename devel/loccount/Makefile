# $FreeBSD$

PORTNAME=	loccount
DISTVERSION=	2.0
CATEGORIES=	devel

MAINTAINER=	yuri@FreeBSD.org
COMMENT=	Count source lines of code in a project

LICENSE=	BSD2CLAUSE
LICENSE_FILE=	${WRKSRC}/COPYING

USES=		go

USE_GITLAB=	yes
GL_ACCOUNT=	esr
GL_COMMIT=	249ea3d6927fd327086b609857c04bb95eafdd98

GO_PKGNAME=	gitlab.com/${GL_ACCOUNT}/${PORTNAME}

PLIST_FILES=	bin/${PORTNAME}

.include <bsd.port.mk>
