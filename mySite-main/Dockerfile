FROM node:18
WORKDIR /APP
COPY packages.json /app
RUN npm install
COPY ./app
CMD node server.js
EXPOSE 7667
