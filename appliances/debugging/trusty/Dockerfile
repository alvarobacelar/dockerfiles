FROM ubuntu:trusty

USER root

RUN apt-get update && \
    apt-get install -y \
            curl \
            gdb \
            lsof \
            pstack \
            strace && \
    apt-get clean

CMD ["bash"]
