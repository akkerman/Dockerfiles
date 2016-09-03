FROM node
MAINTAINER Marcel Akkerman <ikbenMarcelAkkerman@hotmail.com>
RUN apt-get -y update && apt-get -y install --no-install-recommends rsync
RUN npm install -g bower grunt gulp phantomjs eslint
RUN echo '{ "allow_root": true }' > /root/.bowerrc
