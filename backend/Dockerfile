FROM node:16.14.0

# Create app directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

RUN npm install


# Bundle app source
COPY . .

EXPOSE 5000
CMD [ "npm", "start" ]