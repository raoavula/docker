FROM node
RUN apt-get update && apt-get install -y --no-install-recommends apt-utils && apt-get -y install sudo
RUN DEBIAN_FRONTEND='noninteractive' apt-get install -y --no-install-recommends build-essential
RUN DEBIAN_FRONTEND='noninteractive' apt-get install -y --no-install-recommends software-properties-common
RUN curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
RUN DEBIAN_FRONTEND='noninteractive' apt-get install  -y --no-install-recommends nodejs
RUN npm install pm2 -g
RUN npm install -g @angular/cli


