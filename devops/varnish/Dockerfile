# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Luxcas <luxcas@gmail.com>" \
      org.label-schema.name="hmadv-classic-varnish" \
      org.label-schema.description="hmadv_classic Varnish image." \
      org.label-schema.vendor="Luxcas"

COPY etc/varnish.vcl /etc/varnish/default.vcl
