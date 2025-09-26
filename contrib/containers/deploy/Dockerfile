FROM phusion/baseimage:focal-1.0.0
LABEL maintainer="SquardCoin Developers <dev@squardcoin.org>"
LABEL description="Dockerised SquardCoin, built from Travis"

ARG USER_ID
ARG GROUP_ID

ENV HOME /home/squardcoin

# add user with specified (or default) user/group ids
ENV USER_ID ${USER_ID:-1000}
ENV GROUP_ID ${GROUP_ID:-1000}
RUN groupadd -g ${GROUP_ID} squardcoin && \
    useradd -u ${USER_ID} -g squardcoin -s /bin/bash -m -d /home/squardcoin squardcoin && \
    mkdir /home/squardcoin/.squardcoin && \
    chown ${USER_ID}:${GROUP_ID} -R /home/squardcoin

COPY bin/* /usr/local/bin/

RUN chmod a+x /usr/local/bin/*

USER squardcoin

VOLUME ["/home/squardcoin"]

EXPOSE 23531 9999 33531 33532

WORKDIR /home/squardcoin
