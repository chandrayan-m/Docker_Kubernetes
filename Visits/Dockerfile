# specify base image
FROM node:alpine

#set work directory
WORKDIR  '/app'

# install dependencies
COPY  package.json .
RUN npm install

COPY . .

#Run startup commands
CMD [ "npm", "start" ]