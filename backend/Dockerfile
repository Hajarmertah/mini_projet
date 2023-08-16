# Use an official Node.js runtime as the base image
FROM node:latest

# Set the working directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install app dependencies

RUN npm install 
RUN npm install -g nodemon

# Copy the rest of the frontend code
COPY . .

# Expose the port the frontend runs on
EXPOSE 3000

# Start the frontend
CMD ["npm", "start"]