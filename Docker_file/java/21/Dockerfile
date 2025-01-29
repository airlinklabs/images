FROM --platform=$TARGETOS/$TARGETARCH openjdk:21-jdk-slim

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        curl \
        ca-certificates \
    && rm -rf /var/lib/apt/lists/*

RUN useradd -r -u 1000 -d /app javauser \
    && mkdir -p /app/data \
    && chown -R javauser:javauser /app

USER javauser

WORKDIR /app/data

CMD sh -c "$START"
