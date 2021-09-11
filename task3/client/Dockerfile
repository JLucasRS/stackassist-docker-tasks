FROM node
COPY . /client
WORKDIR /client
RUN npm install
# #9 0.419 useradd: UID 1000 is not unique, so i used 1001.
RUN useradd -u 1001 -g 1000 rootless
USER rootless