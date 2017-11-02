FROM alpine:3.6

COPY entrypoint /

RUN set -eux; \
	apk add --no-cache --update tzdata ca-certificates; \
	chmod +x /entrypoint

ENTRYPOINT ["/entrypoint"]