# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Paul Roeland <paulroeland@rozefilmdagen.nl>" \
      org.label-schema.name="rfd26-varnish" \
      org.label-schema.description="rfd26 Varnish image." \
      org.label-schema.vendor="Paul Roeland"

COPY etc/varnish.vcl /etc/varnish/default.vcl
