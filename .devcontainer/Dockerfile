# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.195.0/containers/java/.devcontainer/base.Dockerfile
# [Choice] Java version (use -bullseye variants on local arm64/Apple Silicon): 8, 11, 16, 8-bullseye, 11-bullseye, 16-bullseye, 8-buster, 11-buster, 16-buster
ARG VARIANT=11-bullseye
FROM mcr.microsoft.com/vscode/devcontainers/java:0-${VARIANT}

# [Optional] Uncomment this section to install additional OS packages.
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends openjdk-11-jdk-headless rlwrap clojure leiningen

# [Optional] Uncomment this line to install global node packages.
# RUN su vscode -c "source /usr/local/share/nvm/nvm.sh && npm install -g <your-package-here>" 2>&1