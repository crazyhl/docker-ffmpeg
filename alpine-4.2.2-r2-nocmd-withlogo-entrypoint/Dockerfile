FROM alpine:3.11
MAINTAINER  M1racle Hao <crazyhl@163.com>

RUN     apk  add --no-cache --update ffmpeg

COPY live-logo.png /usr/local/share/
COPY docker-ffmpeg-entrypoint /usr/local/bin/

RUN set -eux \
    && ls -al /usr/local/bin/ \
    && chmod +x /usr/local/bin/docker-ffmpeg-* \
    && ffmpeg -version

CMD         ["ffmpeg"]
ENTRYPOINT ["docker-ffmpeg-entrypoint"]