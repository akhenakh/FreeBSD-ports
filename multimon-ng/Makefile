# $FreeBSD$

PORTNAME=	multimon-ng
PORTVERSION=	1.1.0
CATEGORIES=	comms hamradio

MAINTAINER=	akh@nobugware.com
COMMENT=	Digital transmission decoder

LICENSE=	GPLv2

USE_GITHUB=	yes
GH_ACCOUNT=	EliasOenal

USES=	 	cmake

PLIST_FILES=	bin/multimon-ng

do-install:
	${INSTALL_PROGRAM} ${WRKSRC}/multimon-ng ${STAGEDIR}${PREFIX}/bin

post-install:
	${STRIP_CMD} ${STAGEDIR}${PREFIX}/bin/multimon-ng

.include <bsd.port.mk>
