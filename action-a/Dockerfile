FROM centos:8

ARG LAST_NAME="Son"
ARG FIRST_NAME="Bryant"

ENV LAST_NAME=$LAST_NAME
ENV FIRST_NAME=$FIRST_NAME

COPY hello-world.sh /hello-world.sh

RUN chmod +x /hello-world.sh

ENTRYPOINT ["/hello-world.sh"]