FROM node:18

RUN apt-get update \
  && apt-get install -y \
    xdg-utils \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

RUN npm install -g @aws-amplify/cli
