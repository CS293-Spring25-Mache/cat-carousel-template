# Use the existing PHP 8.2 with Apache image
FROM mcr.microsoft.com/devcontainers/php:8.2-apache

# Install any extra system packages
RUN apt-get update && apt-get install -y \
    nano \
    git \
    && rm -rf /var/lib/apt/lists/*