FROM node
MAINTAINER Marcel Akkerman <ikbenMarcelAkkerman@hotmail.com>
RUN apt-get -y update && apt-get -y install --no-install-recommends rsync
RUN npm install -g --silent bower grunt gulp phantomjs
RUN echo '{ "allow_root": true }' > /root/.bowerrc
