FROM node:8.11.1
RUN mkdir -p /usr/src/app
ENV HOME=/usr/src/app
WORKDIR $HOME
ADD . $HOME
WORKDIR $HOME/frontend
RUN npm install
