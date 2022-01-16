ARG VERSION=latest
ARG FIRST_NAME=jongwoo
FROM busybox:$VERSION
ARG LAST_NAME=Yoo
ARG FIRST_NAME
ARG EMAIL

RUN ["/bin/sh", "-c", "echo $VERSION"] # empty value
RUN ["/bin/sh", "-c", "echo $FIRST_NAME"]
RUN ["/bin/sh", "-c", "echo $LAST_NAME"]
RUN ["/bin/sh", "-c", "echo $EMAIL"]
