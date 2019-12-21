FROM bitnami/minideb:stretch

LABEL MAINTAINER="Branson Fox <bransonf@wustl.edu>"

# Install System Dependencies
RUN apt-get update && apt-get install -y \
	r-base \
	r-base-dev \
	libssl-dev \
	libcurl4-gnutls-dev \
	libgit2-dev \
	libssh2-1-dev

# Still Needs to Be Tested
