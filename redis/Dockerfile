FROM debian:jessie
MAINTAINER James Turnbull "james@example.com"

RUN apt-get -yqq update && apt-get -yqq install redis-server redis-tools

EXPOSE 6379

ENTRYPOINT ["/usr/bin/redis-server"]
