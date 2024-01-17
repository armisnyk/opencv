FROM ubuntu:focal

RUN apt-get update && apt-get --no-install-recommends install -y \
        libgstreamer-plugins-base1.0-dev \
        libgstreamer-plugins-good1.0-dev \
        libgstreamer1.0-dev \
        cmake \
        g++ \
        ninja-build \
    && \
    rm -rf /var/lib/apt/lists/*

WORKDIR /tmp
