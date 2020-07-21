FROM scratch

LABEL maintainer="Mata <mata.glosova@gmail.com>"
LABEL description="Toto je moj Matrix image."

ADD alpine-minirootfs-3.12.0-x86_64.tar.gz /

RUN apk add cmatrix

CMD cmatrix
