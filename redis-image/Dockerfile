# Use an existing docker image as base
FROM alpine

# Download and install dependencies
RUN apk add --update redis

# Specify the starting command
CMD [ "redis-server" ]