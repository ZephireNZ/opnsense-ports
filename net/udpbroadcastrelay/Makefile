PORTNAME=			udpbroadcastrelay
DISTVERSIONPREFIX=	v
DISTVERSION=		1.1
CATEGORIES=			net

MAINTAINER=	m.muenz@gmail.com
COMMENT=	UDP multicast/unicast relayer
WWW=		https://github.com/marjohn56/udpbroadcastrelay

LICENSE=	GPLv2
LICENSE_FILE=	${WRKSRC}/LICENSE

USE_CSTD=	c99
USE_GITHUB=	yes
GH_ACCOUNT=	marjohn56
# Version is not tagged in the upstream repository
GH_TAGNAME=	07d747947047f4c01a3b7dd26bb15beafffeadff

PLIST_FILES=	sbin/udpbroadcastrelay

do-install:
	${INSTALL_PROGRAM} ${WRKSRC}/udpbroadcastrelay ${STAGEDIR}${PREFIX}/sbin/udpbroadcastrelay

.include <bsd.port.mk>
