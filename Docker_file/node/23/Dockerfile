FROM --platform=$TARGETOS/$TARGETARCH node:23-bookworm-slim

RUN apt update -y && apt install -y curl wget 
RUN useradd -r -u 1000 -d /app nodeu && mkdir -p /app/data && chown -R nodeu:nodeu /app

USER nodeu

WORKDIR /app/data

CMD sh -c "$START"
