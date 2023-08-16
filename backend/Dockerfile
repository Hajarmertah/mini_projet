# Use an official Node.js runtime as the base image
FROM node:14

# Set the working directory
# WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the working directory
COPY . /app

WORKDIR /app

# Install app dependencies

RUN npm install 
# RUN npm install -g nodemon

# Expose the port the frontend runs on
EXPOSE 3000

# Start the frontend
CMD ["npm", "start"]