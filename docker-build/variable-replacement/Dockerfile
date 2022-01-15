FROM busybox
ENV FOO=null
ENV BAR=
RUN ["/bin/sh", "-c", "echo ${FOO:-not empty value}"]
RUN ["/bin/sh", "-c", "echo ${FOO:+not empty value}"]
RUN ["/bin/sh", "-c", "echo ${BAR:-empty value}"]
RUN ["/bin/sh", "-c", "echo ${BAR:+empty value}"]
RUN ["/bin/sh", "-c", "echo ${BAZ:-not set value}"]
RUN ["/bin/sh", "-c", "echo ${BAZ:+not set value}"]
