# Use the official Ubuntu image as the base
FROM debian:12

# Install any necessary dependencies
RUN apt-get update && apt-get install -y \
    curl python3-dev git \
    xz-utils \
    pkgconf \
    libglib2.0-0 \
    libnss3 \
    && rm -rf /var/lib/apt/lists/*

ADD files/sccache /usr/local/bin
