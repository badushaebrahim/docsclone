FROM node:alpine

WORKDIR /usr/app

COPY package*.json ./

# Install dependencies
RUN npm install

# copy local files to app folder
COPY . .


CMD ["npm","devStart"]