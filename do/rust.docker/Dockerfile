FROM ubuntu:14.04

RUN apt-get update \
 && apt-get install -y --no-install-recommends \
        build-essential \
        ca-certificates \
        curl \
        gdb \
        strace \
 && rm -rf /var/lib/apt/lists/* \
 && apt-get clean

RUN curl -sSf https://static.rust-lang.org/rustup.sh | sh
