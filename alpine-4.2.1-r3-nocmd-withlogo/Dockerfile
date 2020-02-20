FROM alpine:3.11
MAINTAINER  M1racle Hao <crazyhl@163.com>

RUN     apk  add --no-cache --update ffmpeg

COPY live_logo.png /data/static/

CMD         ["--help"]
ENTRYPOINT  ["ffmpeg"]