FROM scratch

LABEL maintainer="solarispadawan <solaris.padawan@gmail.com>"
LABEL homepage="https://solarispadawan.github.io"

ADD alpine-minirootfs-3.13.5-x86_64.tar.gz /

RUN apk add cmatrix sl 

CMD ["/usr/bin/cmatrix"]

