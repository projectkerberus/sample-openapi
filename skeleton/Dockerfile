FROM node:15

WORKDIR /app
COPY . ./
RUN yarn
EXPOSE 8080
CMD [ "node", "server.js" ]