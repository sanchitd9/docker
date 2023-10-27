# Use an existing docker image as base
FROM node:alpine

# Download and install dependencies
WORKDIR /usr/app

COPY ./package.json ./
RUN npm install
COPY ./ ./

# Specify the starting command
CMD [ "npm", "start" ]