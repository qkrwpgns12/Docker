FROM debian
MAINTAINER Jehoon Park <qkrwpgns12@naver.com>

RUN apt-get update &&\
    apt-get install -y fortune &&\
    apt-get clean

COPY html-generator.sh /

CMD ["/bin/bash", "/html-generator.sh"]
