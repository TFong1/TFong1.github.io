FROM mcr.microsoft.com/devcontainers/base:jammy

# Install Hugo Extended
RUN apt update && apt install -y hugo

# Clean up
RUN apt clean -y && rm -rf /var/lib/apt/lists/*
