FROM debian
MAINTAINER Jehoon Park <qkrwpgns12@naver.com>

RUN apt-get update && \
    apt-get install -y stress

CMD ["/bin/sh", "stress --cpu 8"]
