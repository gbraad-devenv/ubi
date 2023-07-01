FROM --platform=linux/amd64 ghcr.io/gbraad-devenv/ubi/dotfiles:9

USER root

RUN  dnf update -y tailscale \
     && dnf clean all \
     && rm -rf /var/cache/yum

USER gbraad
