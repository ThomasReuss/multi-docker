# use minimal base image
FROM node:alpine

# set work dir for the app
WORKDIR '/app'

# install np, copy dependencies first
COPY ./package.json ./
RUN npm install
COPY . .

# start npm
CMD ["npm", "run", "start"]