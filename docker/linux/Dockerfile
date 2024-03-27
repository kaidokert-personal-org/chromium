FROM debian:12

RUN apt update -qqy \
    && apt -qqy upgrade \
    && apt install -qqy --no-install-recommends \
        generate-ninja \
        python3-dev \
    && apt-get clean autoclean \
    && apt-get autoremove -y --purge \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* \
    && rm -rf /var/lib/{apt,cache,log}