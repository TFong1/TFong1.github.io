FROM mcr.microsoft.com/devcontainers/base:jammy

# Install Hugo Extended
RUN apt update && apt install -y wget
RUN wget https://github.com/gohugoio/hugo/releases/download/v0.143.1/hugo_extended_0.143.1_linux-amd64.deb
RUN dpkg -i hugo_extended_0.143.1_linux-amd64.deb
RUN rm hugo_extended_0.143.1_linux-amd64.deb

# Clean up
RUN apt clean -y && rm -rf /var/lib/apt/lists/*
