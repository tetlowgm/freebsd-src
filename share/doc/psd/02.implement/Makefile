VOLUME=		psd/02.implement
SRCS=		stubs implement
EXTRA=		ref.bib
MACROS=		-ms
USE_PIC=
USE_REFER=
USE_SOELIM=
CLEANFILES=	stubs

stubs:
	@(echo .R1; echo database ${.CURDIR}/ref.bib; \
	    echo accumulate; echo .R2) > ${.TARGET}

.include <bsd.doc.mk>
