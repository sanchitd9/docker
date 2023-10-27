# Specify a base image
FROM node:alpine

# Install dependencies
WORKDIR /usr/app
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Startup command
CMD [ "npm", "start" ]