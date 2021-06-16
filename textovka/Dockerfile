FROM alpine

LABEL maintainer "solarispadawan <solaris.padawan@gmail.com>"

RUN apk add python3

ADD textovka.tgz /

WORKDIR /textovka

CMD [ "/usr/bin/env", "python3", "/textovka/game.py" ]

