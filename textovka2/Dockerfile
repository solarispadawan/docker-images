FROM python:alpine

ADD https://github.com/bletvaska/python-textovka/archive/refs/heads/2021.05-tsys.zip /

RUN unzip 2021.05-tsys.zip \
    && mkdir app \
    && mv /python-textovka-2021.05-tsys/* /app \
    && rm -rf 2021.05-tsys.zip python-textovka-2021.05-tsys

RUN adduser -S gamer -G users

USER gamer
WORKDIR /app/

CMD [ "/usr/bin/env", "python3", "game.py" ]

