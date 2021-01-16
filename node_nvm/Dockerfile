FROM ubuntu:latest

# Declare constants
ENV NVM_VERSION v0.37.2
ENV NODE_VERSION v14.15.4

# Replace shell with bash so we can source files
RUN rm /bin/sh && ln -s /bin/bash /bin/sh

# Install pre-reqs
RUN apt-get update
RUN apt-get -y install curl build-essential

# Install NVM
RUN curl -o- curl https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash

# Install NODE
RUN source ~/.nvm/nvm.sh; \
    nvm install $NODE_VERSION; \
    nvm use --delete-prefix $NODE_VERSION;



CMD bash