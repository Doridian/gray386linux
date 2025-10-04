FROM nixos/nix:2.20.0
MAINTAINER Robin Hack <hack.robin@gmail.com>

WORKDIR /build

RUN ./graybuild.sh
ENTRYPOINT ["/bin/sh", "-i"]
