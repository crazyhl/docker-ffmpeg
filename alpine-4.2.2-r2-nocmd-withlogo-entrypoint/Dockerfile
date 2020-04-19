FROM alpine:3.11
MAINTAINER  M1racle Hao <crazyhl@163.com>

RUN     apk  add --no-cache --update ffmpeg

COPY live-logo.png /usr/local/share/
COPY docker-ffmpeg-entrypoint /usr/local/bin/

CMD         ["ffmpeg"]
ENTRYPOINT ["docker-ffmpeg-entrypoint"]