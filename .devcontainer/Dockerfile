FROM ubuntu:22.04

# Install ONLY absolute essentials
RUN apt-get update && \
    apt-get install -y --no-install-recommends \
    curl \
    ca-certificates \
    sudo \
    && rm -rf /var/lib/apt/lists/*
