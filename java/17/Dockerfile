#
# Copyright (c) 2026 IvanNovR (https://github.com/IvanNovR/pterodactyl-images)
#
# This image is licensed under the GPL-3.0 license.
#

FROM --platform=$TARGETOS/$TARGETARCH eclipse-temurin:17-jdk-jammy

LABEL maintainer="IvanNovR"
LABEL org.opencontainers.image.source="https://github.com/IvanNovR/pterodactyl-images"
LABEL org.opencontainers.image.licenses="GPL-3.0"

ENV USER=container \
    HOME=/home/container \
    LANG=C.UTF-8 \
    JAVA_VERSION=17

RUN apt-get update -y \
    && apt-get install -y --no-install-recommends \
        lsof curl ca-certificates openssl git tar sqlite3 fontconfig libfreetype6 tzdata iproute2 libstdc++6 \
    && rm -rf /var/lib/apt/lists/* \
    && useradd -d /home/container -m container

USER container
WORKDIR /home/container

COPY ./../entrypoint.sh /entrypoint.sh

CMD ["/bin/bash", "/entrypoint.sh"]
