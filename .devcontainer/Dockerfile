# Start from the universal base image
FROM mcr.microsoft.com/devcontainers/universal:2

# Install Fira Code font
RUN apt-get update && \
    apt-get install -y fonts-firacode && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
