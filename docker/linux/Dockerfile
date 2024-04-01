# Use the official Ubuntu image as the base
FROM debian:12

# Install any necessary dependencies
RUN apt-get update && apt-get install -y \
    curl python3-dev git \
    xz-utils \
    && rm -rf /var/lib/apt/lists/*
