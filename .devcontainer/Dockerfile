FROM mcr.microsoft.com/devcontainers/java:17

RUN sudo apt update \
    && sudo apt upgrade -y \
    && rm -rf /var/lists/apt/lists/* \
    && sudo apt clean