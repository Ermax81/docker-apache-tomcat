# Source: https://hub.docker.com/_/httpd?tab=tags
# Source: https://hub.docker.com/r/nasoym/httpd-mod_jk/dockerfile
# Image alpine with apt-get update/install

FROM httpd:2.4.53

RUN apt-get update \
  && apt-get install -y --no-install-recommends libapache2-mod-jk

