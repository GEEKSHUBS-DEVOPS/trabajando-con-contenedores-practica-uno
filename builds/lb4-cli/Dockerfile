# Check out https://hub.docker.com/_/node to select a new base image
FROM node:10-slim
# Install LoopbackCli
RUN npm install -g @loopback/cli nodemon

# Set to a non-root built-in user `node`
# USER node

# Create app directory (with user `node`)
RUN mkdir /app
WORKDIR /app