FROM redis:4.0.6

MAINTAINER Kyrylo Lubynets <dev.lubinets@gmail.com>

ARG HOST_UID=1000

RUN usermod -u ${HOST_UID} redis
RUN groupmod -g ${HOST_UID} redis
